
set(SOURCES led_test.c)
add_executable(led_test ${SOURCES})
target_link_libraries(led_test soem)
install(TARGETS led_test DESTINATION bin)
