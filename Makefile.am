AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = examples/sml_server
examples_sml_server_SOURCES = examples/sml_server.c
examples_sml_server_LDFLAGS = -Isml/include/ -g -Wall -luuid ./.libs/libsml.a

TEST = test/test

ACLOCAL_AMFLAGS = -I m4

lib_LTLIBRARIES = libsml.la

libsml_la_SOURCES = sml/src/sml_attention_response.c sml/src/sml_boolean.c sml/src/sml_close_request.c sml/src/sml_close_response.c sml/src/sml_crc16.c sml/src/sml_file.c sml/src/sml_get_list_request.c sml/src/sml_get_list_response.c sml/src/sml_get_proc_parameter_request.c sml/src/sml_get_proc_parameter_response.c sml/src/sml_get_profile_list_request.c sml/src/sml_get_profile_list_response.c sml/src/sml_get_profile_pack_request.c sml/src/sml_get_profile_pack_response.c sml/src/sml_list.c sml/src/sml_message.c sml/src/sml_number.c sml/src/sml_octet_string.c sml/src/sml_open_request.c sml/src/sml_open_response.c sml/src/sml_set_proc_parameter_request.c sml/src/sml_shared.c sml/src/sml_status.c sml/src/sml_time.c sml/src/sml_transport.c sml/src/sml_tree.c sml/src/sml_value.c 
libsml_la_LIBADD = -luuid
libsml_la_LDFLAGS = -I./sml/include/ -fPIC -fno-stack-protector -g -Wall
pkginclude_HEADERS = sml/include/sml/sml_attention_response.h sml/include/sml/sml_boolean.h sml/include/sml/sml_close_request.h sml/include/sml/sml_close_response.h sml/include/sml/sml_crc16.h sml/include/sml/sml_file.h sml/include/sml/sml_get_list_request.h sml/include/sml/sml_get_list_response.h sml/include/sml/sml_get_proc_parameter_request.h sml/include/sml/sml_get_proc_parameter_response.h sml/include/sml/sml_get_profile_list_request.h sml/include/sml/sml_get_profile_list_response.h sml/include/sml/sml_get_profile_pack_request.h sml/include/sml/sml_get_profile_pack_response.h sml/include/sml/sml_list.h sml/include/sml/sml_message.h sml/include/sml/sml_number.h sml/include/sml/sml_octet_string.h sml/include/sml/sml_open_request.h sml/include/sml/sml_open_response.h sml/include/sml/sml_set_proc_parameter_request.h sml/include/sml/sml_shared.h sml/include/sml/sml_status.h sml/include/sml/sml_time.h sml/include/sml/sml_transport.h sml/include/sml/sml_tree.h sml/include/sml/sml_value.h

