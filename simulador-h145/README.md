# Simulador hidráulico · H145 (BK117 D-3)

Simulador didáctico del sistema hidráulico de los controles de vuelo del Airbus H145 (BK117 D-3): dos sistemas a 103 bar, bombas principales y auxiliar, depósito y bloque de válvulas, actuadores del rotor principal y de cola, indicaciones VMS/FND, prueba en tierra y fallas.

**Abrir el simulador:** https://sozin0512.github.io/SOZIN-/simulador-h145/

No hace falta instalar nada ni iniciar sesión: funciona en cualquier navegador moderno (computadora, TV con navegador, tablet o celular).

## Controlarlo desde el celular

1. Abre el simulador en la pantalla grande y pulsa **📱 Conectar celular**.
2. Escanea el código QR con el celular, o abre la página en el celular y escribe el código de 5 letras que aparece en la pantalla.
3. El celular muestra un control remoto con el cíclico, colectivo, pedales, switches del overhead, fallas y escenarios. Pueden conectarse varios celulares a la misma pantalla.

El enlace entre celular y pantalla usa WebRTC a través del servidor público gratuito de [PeerJS](https://peerjs.com/), así que ambos necesitan internet. Si la red del taller bloquea WebRTC, el simulador sigue funcionando en la pantalla con mouse o teclado.

## Qué incluye

- Esquema animado con flujo de alta presión (naranja) y retorno (azul).
- Detalle del servo del actuador: spool, cámaras A/B, bypass, shut-off, check valve y override mecánico.
- Bomba de 9 pistones con plato de ángulo variable.
- Bomba auxiliar con límites de 90 s (solo batería) y 5 min (con EPU).
- HYD TEST SYS 1 / SYS 2, autoprueba Helionix y todos los mensajes hidráulicos del FND.
- 8 fallas y 6 escenarios rápidos, con explicación en vivo de lo que ocurre.

## Aviso

Modelo didáctico basado en el Training Manual Pilot, cap. 05 Flight Control (rev. 4, marzo 2024). Las presiones, fuerzas, carreras, velocidades, umbrales y tiempos son los del manual; el caudal de las bombas, las cargas aerodinámicas y las constantes de tiempo son aproximaciones para la animación. **No sustituye al manual de vuelo, al manual de mantenimiento ni a la instrucción aprobada.** Proyecto independiente, sin relación con Airbus Helicopters.
