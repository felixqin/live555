
add_definitions(-DSOCKLEN_T=socklen_t)
add_definitions(-DNO_SSTREAM=1)
add_definitions(-DALLOW_RTSP_SERVER_PORT_REUSE=1)
add_definitions(-DLOCALE_NOT_USED)
add_definitions(-DUSE_OUR_BZERO=1)

add_subdirectory(liveMedia)
add_subdirectory(BasicUsageEnvironment)
add_subdirectory(UsageEnvironment)
add_subdirectory(groupsock)

