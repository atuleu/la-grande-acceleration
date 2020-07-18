set(SRC_FILES main.cpp)
set(HDR_FILES )

add_executable(la-grande-acceleration ${SRC_FILES} ${HDR_FILES})

target_link_libraries(la-grande-acceleration ${OpenCV_LIBS})
