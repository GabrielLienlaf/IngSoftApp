# Sistema Web de Reservas - El Toldo

## Descripción

Aplicación web académica para configurar reservas de matrimonio en El Toldo.

El cliente completa una encuesta/formulario, selecciona uno de los cuatro menús disponibles y recibe un comprobante con los datos comerciales de su reserva. El cliente no ve cantidades de suministros.

El administrador ingresa al panel interno y, usando los mismos datos ingresados por el cliente en la encuesta, ejecuta el motor lógico de cálculo de suministros para preparar los requerimientos del maestro de cocina y maestro parrillero.

## Tecnologías

- HTML5
- CSS3
- JavaScript Vanilla
- localStorage
- Live Server

## Flujo de uso

1. Abrir `formulario.html` con Live Server.
2. Registrar una reserva de matrimonio.
3. Revisar el comprobante del cliente en `comprobante.html`.
4. Abrir `admin.html` con Live Server.
5. Ingresar al panel administrador.
6. Presionar `Recargar`.
7. Presionar `Gestionar` sobre la reserva.
8. Revisar el cálculo interno de suministros, requerimiento de cocina y requerimiento de parrilla.

## Credenciales demo administrador

- Email: `admin@eltoldo.cl`
- Contraseña: cualquier contraseña no vacía para la demo local, sugerida: `Admin123456`

## Importante

Esta versión está preparada para demo académica local. No depende de Firebase para mostrar los suministros internos. La información se mantiene en el navegador mediante `localStorage`, por lo que debe probarse en el mismo navegador donde se creó la reserva.

Para una versión productiva, la mejora futura es activar persistencia en Firebase con reglas de seguridad y autenticación real.
