# Solución de Problemas

Sabemos que a veces pueden surgir inconvenientes al desplegar o ejecutar tu aplicación. En esta sección te ofrecemos una guía rápida para resolver los errores más frecuentes en Akirax.

---

## El servidor no arranca

- **Revisá los logs** desde la consola en el panel. Muchas veces, el error estará detallado ahí (por ejemplo: puertos ocupados, errores de sintaxis, módulos faltantes, etc.).
- **Verificá que el punto de entrada esté correctamente definido** en tu proyecto (`index.js`, `main.go`, etc.).
- **Asegurate de tener las dependencias instaladas** (`npm install`, `go mod tidy`, etc.).
- Confirmá que no estés usando un puerto bloqueado; por defecto, Akirax asigna uno automáticamente que puedes pedir que lo cambiemos.

![akirax](https://files.catbox.moe/wwdvmp.jpg)

En la imagen se ve donde puedes encontrar el puerto de tu servidor de forma rápida. 

---

## Mi app se cae después de unos segundos

- Posiblemente esté lanzando una excepción no capturada. Revisá los logs detenidamente.
- Confirmá que no estés accediendo a servicios externos que estén fallando (APIs, bases de datos).
- Asegurate de que no estés excediendo el límite de uso del plan (RAM, CPU o almacenamiento).

---

## ¿Nada de esto funcionó?

No te preocupes. Podés contactarnos desde el chat de soporte en el panel o abrir un ticket desde tu cuenta. Nuestro equipo técnico está para ayudarte.

![ticket](https://files.catbox.moe/8vf5e1.jpg)

Ejemplo de como enviar un ticket en [Nuestro sistema de tickets](https://home.akirax.net/tickets).

**¡Tu proyecto merece estar online sin interrupciones!**
