set(SOURCES app_main.c)
idf_component_register(SRCS ${SOURCES}
                    INCLUDE_DIRS .
                    REQUIRES camera http_server)

target_compile_definitions(${COMPONENT_LIB} )