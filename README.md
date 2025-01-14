

Ingress-controller:

Definición: Es un componente que gestiona el acceso externo a los servicios internos del cluster de Kubernetes utilizando protocolo HTTP o HTTPS y balancea las cargas a traves de un recurso ingress que tiene definidos unas reglas de enrutamiento

Diferencia entre ingress e ingress-controller:

- Ingress: Define las reglas de enrutamiento.
- Ingress-controller: Motor que implementa el comportamiento segun las configuraciones del ingress.

Necesidad:

- Enrutar tráfico a un servicio especifico proveniente de un cliente que apunta a un dominio. Cada dominio corresponde a un servicio dentro del cluster segun como se configure.
- Balancear las cargas.

![image](https://github.com/user-attachments/assets/2b4fb9e5-5130-4606-b324-7a26327154a3)

  
Fuentes:

- https://kubernetes.io/docs/concepts/services-networking/ingress/
- https://docs.nginx.com/nginx-ingress-controller/installation/installing-nic/installation-with-manifests/
