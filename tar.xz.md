创建tar.xz文件
    command (tar cvf xxx.tar xxx/) ------> xxx.tar ----> command (xz -z xxx.tar) ----> xxx.tar.xz 
解压tar.xz文件
    command (xz -d xxx.tar.xz) -----> xxx.tar -----> command (tar xvf xxx.tar) -----> xxx