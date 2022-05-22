find_package(GTest CONFIG REQUIRED)

add_executable(unit_tests tests.cpp)
target_link_libraries(unit_tests PRIVATE GTest::gmock GTest::gmock_main)
