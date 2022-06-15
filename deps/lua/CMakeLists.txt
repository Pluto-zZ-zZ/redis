#这个指令是把整个目录的所有文件作为变量，免得一个一个的加
aux_source_directory (${PROJECT_SOURCE_DIR}/deps/lua/src LUA_SRC)
add_library(lua STATIC ${LUA_SRC})
