ADD_EXECUTABLE(
  test-suite-fh-2023-06-23

  sensor-mock-nopoly-basic.cpp
  switch-mock-nopoly-basic.cpp
  )

TARGET_LINK_LIBRARIES(
  test-suite-fh-2023-06-23

  lib-fh-2023-06-23
  gtest_main 
  )
