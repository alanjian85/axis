project(laurel_engine)

set(LAUREL_ENGINE_SOURCE_FILES
    src/main.cpp)
add_executable(laurel_engine ${LAUREL_ENGINE_SOURCE_FILES})

target_include_directories(laurel_engine PRIVATE include)