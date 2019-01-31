project(lua LANGUAGES C CXX)

file(GLOB LUA_SOURCES src/*.c)
add_library(lua STATIC ${LUA_SOURCES})
target_include_directories(lua include)