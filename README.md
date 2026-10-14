# Renkairo — instaladores

Aquí se publican los instaladores de **Renkairo** para Windows: captura de pantalla, grabación, reuniones
transcritas, pizarras y documentación en una sola aplicación. Este repositorio solo contiene instaladores y
notas de versión; el código fuente no es público.

## Descargar

**[Descargar la última versión (Renkairo-Setup.exe)](https://github.com/matricardi29/renkairo-releases/releases/latest/download/Renkairo-Setup.exe)**

Windows 10 u 11 de 64 bits. La instalación es por usuario y no pide permisos de administrador.

El instalador aún no está firmado, así que Windows puede mostrar «Windows protegió su PC»: pulsa
**Más información** y luego **Ejecutar de todas formas**.

## Actualizaciones

A partir de la 0.11.0 la aplicación avisa cuando hay una versión nueva y la instala cuando tú lo pides
(Ajustes › Ayuda › Actualizaciones). Antes de instalar comprueba que el archivo descargado coincide con el
SHA-512 publicado en `latest.yml`.

## Comprobar un instalador a mano

Cada versión indica su SHA-256 en sus notas. En PowerShell:

```powershell
Get-FileHash .\Renkairo-Setup.exe
```
