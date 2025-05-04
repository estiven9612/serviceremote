# serviceremote
# Administración Remota en Red Corporativa

Este proyecto contiene una aplicación de administración remota dentro de una red corporativa utilizando sockets. Permite a un servidor enviar comandos a un cliente y recibir los resultados, facilitando el soporte técnico y las pruebas en redes locales.

## Descripción

El proyecto está compuesto por dos scripts:

- **Servidor (server.py)**: Se encarga de escuchar las conexiones de los clientes en un puerto específico. Acepta comandos desde el servidor para ser ejecutados en el cliente.
  
- **Cliente (client.py)**: Se conecta al servidor y ejecuta los comandos recibidos, devolviendo los resultados de la ejecución.

## Requisitos

- Python 3.x
- Red local configurada para la comunicación entre el servidor y el cliente.
  
## Uso

1. **Servidor**: 
   - Ejecuta el script `server.py` en la máquina que actuará como servidor. El servidor escuchará por una conexión entrante en el puerto especificado.
  
2. **Cliente**: 
   - Ejecuta el script `client.py` en la máquina que actuará como cliente. El cliente debe conectarse al servidor proporcionando la IP y el puerto correctos.

## Propósito

Este sistema está diseñado para proporcionar administración remota dentro de redes locales y facilitar el soporte técnico. También puede ser útil en entornos de pruebas para automatizar la ejecución de comandos de diagnóstico.

## Seguridad

Este software **no está recomendado para entornos de producción sin una adecuada configuración de seguridad**. No se recomienda su uso fuera de redes controladas y seguras.

## Instalación

Para usar el proyecto, simplemente clona este repositorio y ejecuta los scripts:

```bash
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo
python server.py
python client.py
