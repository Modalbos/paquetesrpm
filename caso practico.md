# Gestión de Paquetes en Rocky Linux

1. **Actualizar el sistema:**
    ```bash
    sudo dnf update
    ```

    ![Licencia](img/imagen_2024-01-30_221557034.png)
    ![Licencia](img/imagen_2024-01-30_221754537.png)
   

3. **Buscar paquetes:**
    ```bash
    sudo dnf search el_paquete
    ```
   ![Licencia](img/imagen_2024-01-30_222155319.png)

4. **Instalar un paquete:**
    ```bash
    sudo dnf install el_paquete
    ```
     ![Licencia](img/imagen_2024-01-30_222536891.png)
    
  
5. **Comprobar si el paquete está instalado:**
    ```bash
    rpm -q el_paquete
    ```
    ![Licencia](img/imagen_2024-01-30_222827495.png)
    
6. **Comprobar más información sobre el paquete:**
    ```bash
    rpm -ql el_paquete
    ```
     ![Licencia](img/imagen_2024-01-30_223354484.png)

7. **Desinstalar el paquete:**
    ```bash
    sudo dnf erase el_paquete
    # O
    sudo dnf remove el_paquete
    ```
![Licencia](img/imagen_2024-01-30_223719662.png)
    


    
## LICENCIA
![Licencia](img/licencia.png)
