cmake_minimum_required(VERSION 3.12)

project(Chapter06-Ranges_And_Views)

file(GLOB CHAPTER_SRC_FILES "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp"
     "${CMAKE_CURRENT_SOURCE_DIR}/*.h")

add_executable(${PROJECT_NAME} ${CHAPTER_SRC_FILES})

target_link_libraries(${PROJECT_NAME} GTest::gtest)
