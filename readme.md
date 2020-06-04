* 克隆仓库

 ```
 git clone https://github.com/Xilinx/u-boot-xlnx.git
 ```

* 安装工具链 

 ```
 sudo apt-get install gcc-arm-linux-gnueabi 
 ```

* 编译

 ```
 cd u-boot-xlnx
 export CROSS_COMPILE=arm-linux-gnueabihf-
 export ARCH=arm
 make distclean
 make zynq_microzed_defconfig
 make
 ```

