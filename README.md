# camera-calibration
ubuntu操作系统下实现
1. 建立文件夹　cameraCalibration         
    mkdir cameraCalibration
2.  cd ./cameraCalibration
3. （1）建立文件夹　iamge 保存标定所需的图片 src保存程序
   （2）创建文件　　Cmakelists.txt 并写入
   （3）在src文件夹内创建calibration.cpp;calibration.txt保存标定所用文件的路径;CMakeLists.txt
4.  编译运行
    cd ./cameraCalibration　
    mkdir  build 
    cd build 
    cmake ..   make 
    会生成bin文件夹，里面有可执行文件，运行后会得到结果文件在bin中保存。

