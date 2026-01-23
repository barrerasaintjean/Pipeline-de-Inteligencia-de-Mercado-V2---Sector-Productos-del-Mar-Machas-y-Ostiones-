##en proceso##
Pipeline de Inteligencia de Mercado V2 - Sector Productos del Mar (Machas y Ostiones)
🎯 El Problema y la Evolución (V2)
En la fase inicial (V1), la prospección directa en minimarkets y locales pequeños demostró ser ineficiente: barreras de entrada con encargados de compras ausentes y baja receptividad al contacto frío presencial.

La V2 cambia el enfoque: * Geolocalización Estratégica: Foco en el eje logístico desde La Florida hacia el sector oriente (Macul, Peñalolén, Ñuñoa, Providencia y Las Condes), optimizando las rutas de despacho hacia los principales Malls y centros de consumo.

Automatización de Prospección: Filtrado inteligente de leads mediante bots para optimizar el tiempo humano.

🛠️ Arquitectura del Flujo (n8n)
El sistema utiliza un flujo automatizado en n8n que realiza las siguientes acciones:

Schedule Trigger: Ejecución programada para actualización constante.

Google Maps Search (via SerpApi): Extracción masiva de comercios (pescaderías, restaurantes, locales gourmet) en las comunas objetivo.

Procesamiento de Datos: Limpieza de duplicados y estructuración de información.

Almacenamiento: Inserción en base de datos PostgreSQL (ver tabla prospectos_mercado).

🚀 Próximas Mejoras (Roadmap de Desarrollo)
1. Bot de Nutrición y Mensajería Automática
Implementación de un sistema de mensajería (WhatsApp/Email) para contactar a los locales detectados. El objetivo es interactuar solo con prospectos que demuestren interés real, evitando visitas en frío infructuosas.

2. Clasificador Inteligente de Canales
Un bot analizará cada registro de la base de datos para dividirlos en dos flujos:

Con Sitio Web: Scraping automático de productos (Machas/Ostiones) para extraer precios de la competencia y generar un Estudio de Mercado en tiempo real.

Sin Sitio Web: Generación y envío de un formulario de registro/pedido simplificado para digitalizar su inventario y necesidades.
