	rpm -e --nodeps java-1.8.0-openjdk-headless-1.8.0.144-7.b01.fc27.x86_64
	dnf install -y docker docker-compose
	yum install -y gimp
	dnf install -y corebird
	dnf install -y go
	dnf install -y dnf-plugins-core
	dnnf copr enable heliocastro/hack-fonts
	dnf copr enable heliocastro/hack-fonts
	dnf install -y hack-fonts
	dnf install -y gnome-tweak-tool
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/doctormo/GimpPs/master/tools/install.sh)"
	dnf install -y gcc-c++
	dnf install -y p7zip p7zip-plugins
	dnf install -y unrar
	dnf remove -y libreoffice
	dnf install -y wps-office
	dnf install -y libpng12.x86_64
	dnf install -y mesa-libGLU.x86_64
	dnf install -y shutter
	dnf install -y peek
	dnf install -y mecab-ipadic.x86_64
	dnf install -y https://dev.mysql.com/get/mysql57-community-release-fc27-10.noarch.rpm
	dnf install -y mysql-community-server

	#grep 'A temporary password is generated for root@localhost' /var/log/mysqld.log |tail -1
	#/usr/bin/mysql_secure_installation

	dnf install -y pcre-cpp.x86_64
	dnf install -y  libzip
	dnf install -y  proj
	dnf install -y  lm_sensors
	dnf install -y  python2-crypto.x86_64
	dnf install -y  python-paramiko-doc.noarch
	dnf install -y  mingw64-libzip.noarch
	dnf install -y shadowsocks-qt5
	curl --silent --location https://rpm.nodesource.com/setup_8.x | sudo bash -
	yum install -y nodejs
	dnf install -y glibc.x86_64
	yum install -y shadowsocks-qt5
	yum install -y R-core
	dnf install -y redhat-lsb.x86_64

#	systemctl start mysqld.service
#	systemctl enable mysqld.service
#	systemctl disable firewalld.service
#	systemctl stop firewalld.service 
#	systemctl enable firewalld.service
#	systemctl start firewalld.service 

