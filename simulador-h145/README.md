# Simulador hidráulico · H145 (BK117 D-3)

Simulador didáctico del sistema hidráulico de los controles de vuelo del Airbus H145 (BK117 D-3): dos sistemas a 103 bar, bombas principales y auxiliar, depósito y bloque de válvulas, actuadores del rotor principal y de cola, indicaciones VMS/FND, prueba en tierra y fallas.

**Abrir el simulador:** https://sozin0512.github.io/SOZIN-/simulador-h145/

No hace falta instalar nada ni iniciar sesión: funciona en cualquier navegador moderno (computadora, TV con navegador, tablet o celular).

## Controlarlo desde el celular

1. Abre el simulador en la pantalla grande y pulsa **📱 Conectar celular**.
2. Escanea el código QR con el celular, o abre la página en el celular y escribe el código (5 letras y un número) que aparece en la pantalla.
3. El celular muestra un control remoto con el cíclico, colectivo, pedales, switches del overhead, fallas y escenarios. Pueden conectarse varios celulares a la misma pantalla.

El enlace entre celular y pantalla pasa por un servidor MQTT público (HiveMQ, EMQX o Mosquitto, el primero que responda), así que ambos necesitan internet, aunque pueden estar en redes distintas (Wi-Fi y datos móviles). El código tiene 5 letras y un número. Si la red bloquea los puertos 8084/8884/8081, la ventana «Conectar celular» lo indica; prueba con datos móviles. El simulador sigue funcionando en la pantalla con mouse o teclado.

## Qué incluye

- Esquema animado con flujo de alta presión (naranja) y retorno (azul).
- Detalle del servo del actuador: spool, cámaras A/B, bypass, shut-off, check valve y override mecánico.
- Bomba de 9 pistones con plato de ángulo variable.
- Bomba auxiliar con límites de 90 s (solo batería) y 5 min (con EPU).
- HYD TEST SYS 1 / SYS 2, autoprueba Helionix y todos los mensajes hidráulicos del FND.
- 8 fallas y 6 escenarios rápidos, con explicación en vivo de lo que ocurre.

## Aviso

Modelo didáctico basado en el Training Manual Pilot, cap. 05 Flight Control (rev. 4, marzo 2024). Las presiones, fuerzas, carreras, velocidades, umbrales y tiempos son los del manual; el caudal de las bombas, las cargas aerodinámicas y las constantes de tiempo son aproximaciones para la animación. **No sustituye al manual de vuelo, al manual de mantenimiento ni a la instrucción aprobada.** Proyecto independiente, sin relación con Airbus Helicopters.

## Modelos 3D

En https://sozin0512.github.io/SOZIN-/simulador-h145/modelos-3d.html (o con el botón «🧊 Modelos 3D» del simulador): bomba de pistones, bomba auxiliar de engranajes, depósito con pistón doble 1:60, válvulas del bloque, actuador tándem y conjunto del rotor principal con SEMA. Se giran con el dedo o el mouse; tienen corte, vista explosionada y animación. Modelos ilustrativos, no a escala.
