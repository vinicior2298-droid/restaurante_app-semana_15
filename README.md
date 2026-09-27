# Sistema de Gestión de Restaurante 

# Richard Morocho 

Aplicación de escritorio modular desarrollada en **Python** utilizando **Tkinter** para la interfaz gráfica y una arquitectura basada en servicios orientada a la gestión de un restaurante. Este proyecto forma parte de la entrega de la **Semana 15**.

## 🚀 Características Principales

* **Autenticación de Usuarios:** Sistema de inicio de sesión seguro validando credenciales contra una base de datos local en formato JSON.
* **Gestión de Productos:** Permite registrar, consultar, actualizar y eliminar platos, bebidas, postres y entradas, controlando sus códigos, nombres, categorías, precios y stock.
* **Consulta de Usuarios:** Muestra de manera limpia la lista de usuarios registrados en el sistema.
* **Gestión y Registro de Ventas:** Permite asociar una venta a un usuario registrado y un producto disponible especificando la cantidad, calculando el total automáticamente y registrando la transacción.
* **Persistencia de Datos:** Todos los registros (usuarios, productos y ventas) se almacenan de forma persistente utilizando archivos JSON (`usuarios.json`, `productos.json`, `ventas.json`).
* **Interfaz Gráfica Moderna:** Diseño organizado con menús laterales y soporte para íconos visuales mediante la librería **Pillow**.


##  Estructura del Proyecto

restaurante_app/
│
├── assets/                  # Íconos e imágenes de la interfaz (PNG)
├── datos/                   # Archivos de persistencia JSON (usuarios, productos, ventas)
├── modelos/                 # Clases de dominio (usuario.py, producto.py, venta.py)
├── servicios/               # Lógica de negocio y manejo de archivos (archivo_servicio.py, restaurante_servicio.py)
├── ui/                      # Vistas e interfaz gráfica (login_view.py, main_view.py)
├── main.py                  # Punto de entrada principal de la aplicación
└── README.md                # Documentación del proyecto