# DalpexHax

Una librería increíble para manejar embeds de Discord.

## Instalación

Puedes instalar la librería usando npm:

```sh

npm install dalpexhax
Uso
Aquí tienes un ejemplo básico de cómo usar DalpexHax:

javascript
const { logLogin } = require('dalpexhax');

const p = { name: "John Doe", conn: "12345", auth: "xyz", id: 1 };
const w = 'https://discord.com/api/webhooks/WEBHOOK_ID/WEBHOOK_TOKEN';
logLogin(p, w).then(() => console.log('Embed enviado con éxito'));
Contribución
Si quieres contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.

Crea una nueva rama (git checkout -b feature-xyz).

Haz tus cambios.

Haz un commit de tus cambios (git commit -m 'Añadir feature xyz').

Haz push a la rama (git push origin feature-xyz).

Abre un Pull Request.

Licencia
Este proyecto está bajo la licencia MIT.

Contacto
Si tienes preguntas o necesitas soporte, puedes contactarme en tu.email@example.com.
