# 🤖 Proceso RPA: Automatización Tienda Online
Proyecto desarrollado mediante RPA (Automatización Robótica de Procesos) para la automatización de tareas cotidianas que se realizan en una tienda online.

## 🚀 Objetivos del Proyecto

1. Consumo de una API pública (Fake Store API).
2. Guardar los datos originales en un archivo `.json` y subirlo a Drive.
3. Almacenar los productos estructurados en una base de datos local.
4. Generar un reporte de Excel con estadísticas clave.
5. Enviar el reporte Excel mediante un formulario web.

## 🧰 Tecnologías y Herramientas

- **PIX Studio**
- **C#**
- **MySQl** como base de datos local

## ⚙️ Estructura del Proyecto
- [Base de Datos](./DB/ddl.sql)
- [Datos JSON](./Json/Productos_2025-08-23_114500.json)
- [Reporte EXCEL](./Reporte/Reporte_2025-08-23_115638.xlsx)
- [Desarrollo Pix Studio](./Main.pix)

## Pasos de Ejecución:
1. Configurar la [base de datos](./DB/ddl.sql)
2. Configure los orígenes de los datos [ODBC](https://youtu.be/qltVns9_3BM)
3. Configure sus credenciales de google drive y agregué el archivo en la carpeta Data.
4. Ingrese a Pix Studio:
- Configure el parámetro universal para la conexión a la base de datos:
```
@"Driver={MySQL ODBC 9.3 Unicode Driver};Server=127.0.0.1;Database=productos;UID=root;PWD={contraseña}"
```
- En la carpeta Json encontrará el archivo .json obtenido del consumo de API.
- En la carpeta Reporte encontrará el archivo excel con las estadísticas generadas.

## Pix Automation:
En este proyecto C# realizado se encontrará la parte número 4 de la prueba técnica la cual consiste en el envio del reporte generado por medio de un formulario tomando como evidencia la [captura de pantalla](./Evidencias/Evidencia_2025-08-23_120916.png).

### Requisitos:
- Chrome Driver
- Pix Studio

### Formulario Usado:
[Formulario Web](https://form.jotform.com/251738143039053)

## 📽️ Video Explicativo

🎥 El siguiente video muestra la ejecución completa del flujo automatizado:  
📎 *[Video Explicativo](https://www.canva.com/design/DAGq2TTcyOY/t6Nt74vpg6Na5SP27sgcFA/edit?utm_content=DAGq2TTcyOY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)*

## 👩‍💻 Desarrollado por

**Laura Vargas Rojas**  
Email: [lauramarianavargasrojas22@gmail.com]  
GitHub: [https://github.com/LauraVargas22](https://github.com/LauraVargas22)