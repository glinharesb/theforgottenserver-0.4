1. Compiled:
	* x32: https://github.com/glinharesb/binaries/blob/master/x32.zip
	* x64: https://github.com/glinharesb/binaries/blob/master/x64.zip

2. Source: https://github.com/glinharesb/theforgottenserver-0.4/archive/master.zip

3. VC14 (Visual Studio 2015) libs and includes: https://github.com/glinharesb/binaries/blob/master/vc14_pack.zip

4. Compile on linux:
	* apt-get install autoconf build-essential pkg-config automake libboost-all-dev libgmp3-dev libxml2-dev liblua5.1-0-dev libmysqlclient-dev libssl-dev libsqlite3-dev
	* cd /3777-master
	* chmod -R 777 src
	* cd src
	* ./autogen.sh && ./configure --enable-mysql --enable-root-permission --enable-server-diag && ./build.sh
