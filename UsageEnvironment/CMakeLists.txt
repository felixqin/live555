file(GLOB_RECURSE HEADERFILES "include/*")
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_LIBRARY(UsageEnvironment ${DIR_SRCS} ${HEADERFILES})
INCLUDE_DIRECTORIES(
    include
    ../groupsock/include
)
