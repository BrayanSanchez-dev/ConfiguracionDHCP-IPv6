## Configuracion DHCPv6 en Routers Cisco 1941

<p> para configurar la topologia presente se realizan pasos de configuracion esto es pendiente a como se desarrollo tambien la administracion de cada router
pendiente tambien puede de alterarse los resultados de una mala configuracion

</p>

![imagen-base](res/topologia-base.jpg)

<span> configuracion presente realizada en cisco packet tracert </span>


### configuracion y observaciones

la configuracion de esta topologia se encuentra en el archivo configuracion-dhcp-router tambien que esta configuracion es opcionalmente como una guia 
a como se puede de configurar estos espacios de experimentacion de desarrollo
la direccion de base para la configuracion aplicada es : 

	-> 2001:DB8:ACAD:1111::/64 

<span> esta direccion es publica </span>
tambien es opcional ya que se configura para cada interfaz otras direcciones para poder realizar el request de Dhcpv6 del router
finalmente se tiene las pruebas de conexion en este caso se realiza el ping a la direccion asignada por el router de la pc3 del router (2)

![router-ping](res/resultados.jpg)
	-> archivo-configuracion-adjunto
