#make modbus_mapper
.PHONY: default modbus_mapper
modbus_mapper: 
	cd src && npm install --unsafe-perm=true
	docker build --build-arg http_proxy=http://165.225.76.40:80 --build-arg https_proxy=http://165.225.76.40:80 -t modbus_mapper:v1.0 .
