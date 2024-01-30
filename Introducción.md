# ¿Qué son los paquetes RPM?
## Paquetes RPM en Rocky Linux

Los paquetes RPM (Red Hat Package Manager) son un formato de paquetes de software y un sistema de gestión de paquetes utilizado en distribuciones Linux basadas en Red Hat, como Rocky Linux.

Estos paquetes contienen archivos binarios, scripts de instalación y metadatos que describen la aplicación o software que están destinados a instalar en el sistema.

En Rocky Linux, puedes utilizar el comando `rpm` para gestionar estos paquetes. Algunas operaciones comunes incluyen la instalación, actualización y eliminación de paquetes.

Además, puedes utilizar herramientas como `yum` (anteriormente) o `dnf` (actualmente) para facilitar la gestión de dependencias y realizar instalaciones más sencillas.

Es aconsejable que para más seguridad uses repositorios confiables y verifiques la autenticidad de los paquetes que sean externos a los repositorios oficiales.

## Recursos Adicionales

Para obtener más información sobre la gestión de paquetes en Rocky Linux y otros temas relacionados, puedes consultar los siguientes recursos:

- [Sitio oficial de Rocky Linux](https://rockylinux.org/)
- [Documentación de Rocky Linux](https://docs.rockylinux.org/)
- [Foros de la comunidad de Rocky Linux](https://forums.rockylinux.org/)

Por ejemplo, para instalar un paquete RPM en Rocky Linux, puedes usar el siguiente comando:

```bash
sudo rpm -ivh nombre_del_paquete.rpm
```

## LICENCIA
![Licencia](img/licencia.png)
