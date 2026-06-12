# Resuelve el Crimen — Detective Lógico

**Casos disponibles:**
- Caso 1: Asesinato en Hollywood
- Caso 2: Y luego hubo otro

Juego de deducción noir (estilo Murdle). Examina sospechosos, armas y lugares,
lee las pistas, cruza las pruebas en el tablero de deducción y nombra al asesino.

🔒 **Etapa de prueba:** el acceso está protegido con una contraseña para personas autorizadas.

## Jugar

Abrí la página publicada en GitHub Pages e ingresá la contraseña del caso.

## Tecnología

Aplicación de una sola página, autocontenida y offline: React (UMD) + audio sintetizado
con la Web Audio API, sin dependencias en tiempo de ejecución. Todo el código del juego
queda inerte hasta validar el acceso.

> Nota: al ser un sitio estático, la contraseña (guardada como hash SHA-256, nunca en texto plano)
> frena el acceso casual durante las pruebas, pero no es seguridad de nivel producción.
> Eso llegará si se conecta a un backend/base de datos más adelante.
