# WinFind

**WinFind.exe** es una herramienta de auditoría post-explotación para sistemas Windows, desarrollada en C#. Su objetivo es facilitar la enumeración y detección de vectores de escalada de privilegios, configuraciones inseguras y posibles secretos en un sistema comprometido.

---

## Características

- Enumeración de información del sistema y usuarios
- Revisión de permisos y accesos a carpetas críticas
- Detección de máquinas virtuales y entornos sandbox
- Búsqueda de posibles contraseñas en archivos comunes
- Enumeración de tareas programadas, servicios y variables de entorno
- Comprobación del estado del antivirus y otras configuraciones de seguridad
- Recomendaciones automáticas de exploits y módulos de Metasploit
- Detección de secretos en navegadores, AWS, Git, Firefox, entre otros

---

## Requisitos

- Windows 7 o superior
- .NET Framework 4.7.2+ o .NET 5/6 (según la versión compilada)
- Permisos de ejecución adecuados para leer configuraciones del sistema

---

## Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/D1se0/winFind.git
```

2. Abre el proyecto en Visual Studio o tu IDE favorito.
3. Restaura los paquetes NuGet y compila el proyecto.

## Uso

Ejecuta el binario generado (`WinFind.exe`) con permisos adecuados o simplemente como usuario normal en el sistema objetivo.

```powershell
WinFind.exe
```

La herramienta mostrará en consola un reporte con la información recolectada y resaltará posibles vectores de escalada o hallazgos importantes.

## Contribuciones

¡Contribuciones, reportes de errores y sugerencias son bienvenidas!
Por favor, abre un `issue` o un `pull request`.

## Licencia

Este proyecto es de uso libre bajo la licencia `MIT`. Consulta el archivo `LICENSE` para más detalles.

## Disclaimer

`WinFind.exe` es una herramienta creada para fines educativos y pruebas de seguridad autorizadas únicamente. No nos hacemos responsables por el mal uso que se le pueda dar.

Autor
Creado por d1se0
