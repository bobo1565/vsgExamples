set(SOURCES vsginterleaved.cpp)

add_executable(vsginterleaved ${SOURCES})

target_link_libraries(vsginterleaved vsg::vsg)
