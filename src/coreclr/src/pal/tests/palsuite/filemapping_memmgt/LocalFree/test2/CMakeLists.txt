set(SOURCES
  LocalFree.cpp
)

add_executable(paltest_localfree_test2
  ${SOURCES}
)

add_dependencies(paltest_localfree_test2 coreclrpal)

target_link_libraries(paltest_localfree_test2
  ${COMMON_TEST_LIBRARIES}
)
