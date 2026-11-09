# Proyecto QA: Automation Exercise

Proyecto de portafolio de pruebas manuales sobre la tienda de práctica https://automationexercise.com.

## Objetivo
Verificar que la tienda permita registrarse, iniciar y cerrar sesión, buscar productos, usar el carrito, pagar, contactar, suscribirse y eliminar la cuenta según los requisitos, y documentar las fallas encontradas.

## Mi rol
Tester único (QA Junior): requisitos, plan de pruebas, diseño y ejecución de casos, y reporte de bugs.

## Alcance
- **Se prueba:** registro, login/logout, productos y búsqueda, carrito, checkout y pago, contacto, suscripción y eliminar cuenta.
- **Fuera de alcance:** carga y rendimiento, seguridad avanzada, otros navegadores y móviles (solo Google Chrome en Windows 11).

## Proceso
1. Exploración de la aplicación antes de escribir requisitos.
2. 27 requisitos verificables (positivos y negativos) con prioridad.
3. Plan de pruebas: objetivo, alcance, entorno, datos de prueba, riesgos, criterios de entrada y salida.
4. 30 casos de prueba con trazabilidad requisito a caso: los 27 requisitos tienen al menos un caso.
5. Prueba de humo (10 casos críticos) y matriz de regresión (14 casos).
6. Ejecución manual: en curso. El resultado de cada caso se registra en la hoja de casos (columnas Resultado obtenido y Estado).

## Hallazgos preliminares (a confirmar con la ejecución)
- El registro acepta correos con formato inválido y datos muy cortos sin mostrar aviso.
- La búsqueda sin resultados deja la página en blanco, sin mensaje.
- El formulario de contacto se envía con solo el correo lleno.

## Documentación
Hoja de cálculo (requisitos, plan de pruebas, casos, humo, bugs, regresión, trazabilidad y bitácora): https://docs.google.com/spreadsheets/d/12FoWTb0sP08oWDKCWhT_v8T1M3lVIOXmWt_xItA-sNE/edit

Bitácora de decisiones y desafíos: ver `BITACORA.md`.

## Siguiente etapa
Pruebas de API con Postman y automatización con Selenium, pytest y Page Object Model.
