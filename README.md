# Pan Suizo · carta digital

Sitio público de Pan Suizo, panadería en Ciudad Salitre (Cra 69 # 25-11, Bogotá): https://jsbeltrang21-lang.github.io/pan-suizo/

| Dirección | Para qué |
|---|---|
| `/` | Carta para los clientes: productos, precios, almuerzo del día, horario y el club. Solo informa: la compra es en la caja. |
| `/qr/` | Cartel y tarjetas de mesa con el código QR, listos para imprimir. |
| `/caja/` | Caja del Club Pan Suizo (uso interno): tarjetas de desayunos y almuerzos. Con el registro seguro activado, los datos viven en Cloud Firestore y solo entran las cuentas autorizadas. |
| `/pedidos/` | Lista diaria de pedidos a proveedores (uso interno). Los datos quedan en el celular donde se usa. |
| `/guia/` | Guía de cómo funciona todo: pedidos de clientes, cobros seguros, proveedores, sellos y manejo de la página. |
| `/encargos/` | Agenda de encargos (uso interno). Los datos quedan en el celular donde se usa. |
| `/costos/` | Costos de recetas y precio sugerido (uso interno). Los datos quedan en el celular donde se usa. |

Este repositorio se genera automáticamente con `construir_sitio.py`; no se edita a mano.
