add_executable(tcpclient tcpclient.c)
target_link_libraries(tcpclient yolanda)

add_executable(tcpserver tcp_server.c)
target_link_libraries(tcpserver yolanda)

INCLUDE_DIRECTORIES(                          #相关头文件的目录
     /usr/local/include
     /${PROJET_SOURCE_DIR}/
     /home/yolanda/lib/
     )


