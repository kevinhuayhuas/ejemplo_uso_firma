🔐 ¿Por qué es importante usar el script firma.min.js de Firma Perú?
Para que el proceso de firma digital funcione correctamente en el sistema, es obligatorio incluir e invocar el script firma.min.js proporcionado por Firma Perú desde el frontend.

Este script se conecta automáticamente con una aplicación local instalada en la computadora del usuario (el firmador local), la cual es responsable de:

Detectar y acceder al certificado digital del usuario (ej. DNI electrónico)

Generar la firma digital segura y válida legalmente

Insertar la firma en el documento PDF en la posición y página definidas

Enviar el archivo firmado nuevamente al servidor

💡 ¿Por qué no se firma directamente desde el backend?
La firma digital debe realizarse desde el equipo del firmante, porque:

🔐 El certificado digital está en su máquina o DNI electrónico

⚖️ Solo el titular puede autorizar la firma (cumpliendo la normativa legal)

🧩 El firmador local garantiza la validez de la firma al aplicar los algoritmos y protocolos oficiales