# 增加一个可执行的二进制
ADD_EXECUTABLE(calibration calibration.cpp )

# 增加opencv的依赖
FIND_PACKAGE( OpenCV 3.4 REQUIRED )
INCLUDE_DIRECTORIES( ${OpenCV_INCLUDE_DIRS} ) 

TARGET_LINK_LIBRARIES( calibration    
${OpenCV_LIBS}     
)
