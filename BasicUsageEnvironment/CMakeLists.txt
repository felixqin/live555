file(GLOB_RECURSE HEADERFILES "include/*")
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_LIBRARY(BasicUsageEnvironment ${DIR_SRCS} ${HEADERFILES})
INCLUDE_DIRECTORIES(
    include
    ../groupsock/include
    ../UsageEnvironment/include
)
