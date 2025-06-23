datos de maquina virtual 
****************************************
usuario de Linux :angel 
contraseña: razor18enk

***************[pasos para ejecutar servicios]**************
1.- abrir terminal desde la maquina virtual de Ubuntu Linux
2.- entrar a la carpeta donde se encuentra el docker-compose: cd infraestructura
3.-dentro de la carpeta correremos el Docke-compose con sudo Docker-compose up -d
4.- se puede indagar en la configuración dentro de las carpetas dentro de la misma 
infraestructura
	docker-composer.yml	
	dhcp  _
		dhcpd.conf  
		dhcpd.leases  
		dhcpd.leases~
	dnsq _
		dnsmasq.conf  
		hosts               
	docker-compose.yml.save  
	html  _ 
	logs_
		dhcp-2025-05-21.log  
		dns-2025-05-21.log  
		dnsmasq.log  
		dnsq_  
		ftp_  
		ftp.log  
		ssh_  
		vsftpd.log    
	ssh _
		banner.txt  
		Dockerfile
	dnsmasq _ 
		dnsmasq.conf  
		hosts
	ftp _
		angel_  
		Dockerfile  
		prueba _ 
		vsftpd.conf
                     
	html2  
	shared
5.- para visualizar los logs en tiempo real  dentro de /infraestructura se ejecuta el comando docker-compose logs -f
