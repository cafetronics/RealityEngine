add_library(RealityEngine)
target_sources(RealityEngine PRIVATE RealityEngine.cpp)

find_package(Vulkan REQUIRED)

target_include_directories(RealityEngine PRIVATE "../include" ${Vulkan_INCLUDE_DIRS})
target_link_libraries(RealityEngine PRIVATE vendor Vulkan)