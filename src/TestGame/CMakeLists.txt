add_executable(TestGame)
target_sources(TestGame PRIVATE TestGame.cpp)

target_include_directories(TestGame PRIVATE "../include")
target_link_libraries(TestGame PRIVATE RealityEngine)