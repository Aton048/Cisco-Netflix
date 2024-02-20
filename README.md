# Cisco-Netflix

I: Introduccion
│ 1. Contexto Problematica
│  2. Explicacion Topografia

II: Funcionamiento Dispositivos
│  1. Ip Laptop
│   2. Conexion inalambrica
│    3. Configuraciones Requeridas
│     4. Ip router
│      5. Subnet Mask


III: Conexion con la Nube y Servidor
│ 1. Conexion netflix y Internet

--------------------------------------------------------
**Introduccion:**
Se presentara una solucion de redes donde donde veremos como conectar una familia con distintos dispositivos a los servidores de Netflix

Se presento el problema de que la familia de Anita Gonzales desea desde sus distintos dispositivos conectarse a Netflix para poder ver distintas peliculas, por ello acudieron a nosotros para que les presentemos una solucion eficas a su problema


**Topografia**
En la topografia se ven 2 distintos cuadrados donde 1 es la red interna de la casa de Anita, mientras que en la otra seccion se ve la nube y el servidor de netflix que es a donde navegan las solicitudes desde
la casa de la familia de Anita

---------------------------------------------------------

**II:**
En la imagen, un cable Ethernet conecta el módem al router. Este cable permite la comunicación física entre ambos dispositivos.

**Dirección IP:**

**Módem:** El módem tiene una dirección IP pública asignada por el proveedor de internet. Esta dirección identifica al módem en Internet.

**Router:** El router tiene una dirección IP privada asignada por el propio router. Esta dirección identifica al router dentro de la red local.


**Máscara de subred:**

**Módem:** La máscara de subred del módem define qué parte de la dirección IP pública se usa para identificar la red y qué parte se usa para identificar el dispositivo dentro de la red.

**Router:** La máscara de subred del router define qué parte de la dirección IP privada se usa para identificar la subred local y qué parte se usa para identificar el dispositivo dentro de la subred local.



**Funcionamiento:**

**Comunicación con Internet:** Cuando un dispositivo en la red local (como la laptop o el PC) quiere acceder a Internet, envía una solicitud al router. El router utiliza la dirección IP pública del módem para enviar la solicitud a Internet.

**Comunicación dentro de la red local:** Cuando un dispositivo en la red local quiere comunicarse con otro dispositivo en la misma red, el router utiliza la dirección IP privada del dispositivo de destino para enviar la información.

  
