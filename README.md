# mysql-zh

MySQL Server 8.x 源代码分析，主要是自己学习用的。

# 安装开发环境

```shell
sudo apt-get install build-essential cmake flex bison openssl libssl-dev libaio1 libaio-dev libncurses-dev libncurses6 libncursesw6 libudev-dev libude1
```

# 编译

```shell
mkdir build
cd build
cmake -DWITH_BOOST=../boost/boost_1_73_0 -DWITH_SSL=system ..
make
```
