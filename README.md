1. Compiled:
	* x32 (visual studio): https://github.com/Fir3element/binaries/raw/master/x32.rar
	* x32 (dev-cpp): https://github.com/Fir3element/binaries/raw/master/x32_dev.rar
	* x64 (visual studio): https://github.com/Fir3element/binaries/raw/master/x64.rar

2. Source: https://github.com/Fir3element/3777/archive/master.zip

3. Dev-cpp: https://github.com/Fir3element/binaries/raw/master/dev-cpp.rar

4. MSVC10 libs and includes: https://github.com/Fir3element/binaries/raw/master/vc10_pack.rar

5. Compile on linux:
	* apt-get install autoconf build-essential pkg-config automake libboost-all-dev libgmp3-dev libxml2-dev liblua5.1-0-dev libmysqlclient-dev libssl-dev libsqlite3-dev
	* cd /3777-master
	* chmod -R 777 src
	* cd src
	* ./autogen.sh && ./configure --enable-sqlite --enable-mysql --enable-root-permission --enable-server-diag && ./build.sh
