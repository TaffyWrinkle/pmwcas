set(ENVIRONMENT_SOURCES
  ${CMAKE_CURRENT_SOURCE_DIR}/environment.cc
)

set_property(GLOBAL APPEND PROPERTY PMWCAS_SRC ${ENVIRONMENT_SOURCES})

ADD_PMWCAS_TEST(environment_tests)
