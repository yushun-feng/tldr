# This is my note
- 此文档路径
`$env:note`
- powershell中清空回收站
`Clear-RecycleBin`
- CMakeLists.txt中pkg-config的配置例子
- ########################################
- #启用 pkg-config 支持
`find_package(PkgConfig REQUIRED)`
- #查询 .pc 文件（例如：libssl）
`pkg_check_modules(SSL REQUIRED openssl)`
- #使用变量
`include_directories(${SSL_INCLUDE_DIRS})`
`target_link_libraries(your_target PRIVATE ${SSL_LIBRARIES})`
- ########################################

- 自动修复缺失依赖项
`aptitude --fix-broken install`

- 更新plocate的索引目录
`sudo updatedb --verbose`

- 设置python全局镜像源 pip.ini文件
`[global]`
`index-url = https://mirrors.tuna.tsinghua.edu.cn/pypi/web/simple`