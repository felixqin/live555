file(GLOB_RECURSE HEADERFILES "include/*")
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_LIBRARY(groupsock ${DIR_SRCS} ${HEADERFILES})
INCLUDE_DIRECTORIES(
    include
    ../UsageEnvironment/include
)
