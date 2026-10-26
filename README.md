# Pan Suizo · carta digital

Sitio público de Pan Suizo, panadería en Ciudad Salitre (Cra 69 # 25-11, Bogotá): https://jsbeltrang21-lang.github.io/pan-suizo/

| Dirección | Para qué |
|---|---|
| `/` | Portada de la carta (la abre el QR): lleva a Desayunos o a Almuerzos y muestra el club. Solo informa: la compra es en la caja. |
| `/desayunos/` | Carta de desayunos: platos, pan del horno, dulces y bebidas, con los precios de la panadería. |
| `/almuerzos/` | Almuerzo del día (lunes a viernes): menú de hoy, de la semana, precios y bebidas. |
| `/fotos/` | De dónde es cada foto de la carta y con qué licencia. |
| `/qr/` | Un código QR para cada carta (desayunos en rojo, almuerzos en azul): carteles y tarjetas de mesa listos para imprimir. |
| `/caja/` | Caja del Club Pan Suizo (uso interno): tarjetas de desayunos y almuerzos. Con el registro seguro activado, los datos viven en Cloud Firestore y solo entran las cuentas autorizadas. |
| `/pedidos/` | Lista diaria de pedidos a proveedores (uso interno). Los datos quedan en el celular donde se usa. |
| `/guia/` | Guía de cómo funciona todo: pedidos de clientes, cobros seguros, proveedores, sellos y manejo de la página. |
| `/encargos/` | Agenda de encargos (uso interno). Los datos quedan en el celular donde se usa. |
| `/costos/` | Costos de recetas y precio sugerido (uso interno). Los datos quedan en el celular donde se usa. |

Este repositorio se genera automáticamente con `construir_sitio.py`; no se edita a mano.
