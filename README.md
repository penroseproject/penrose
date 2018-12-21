#### 下载源码

	$ git clone https://github.com/penroseproject/penrose.git
	$ cd penrose
	$ git submodule update --init --recursive

#### 编译源码

	$ ./eosio_build.sh
	$ sudo ./eosio_install.sh
	
注意：自动化编译过程可能会因为主机物理内存小于7G，boost库，mongodb等下载失败或其他原因而编译失败，请查找原因或修改脚本自行解决。