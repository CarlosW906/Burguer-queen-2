Nombre del proyecto: Aplicación Burguer Queen
Framework: Ionic + Angular
Tipo de aplicación: Móvil
Funcionalidad principal: Simular la gestión de pedidos más su precio al momento de ordenar y pagar vía stripe. 

crear un proyecto de ionic y reemplazar carpeta src con esta carpeta de repositorio
por motivos de seguridad está prohibido subir algo relacionado con lo siguiente:

remote:       —— Stripe Test API Secret Key ————————————————————————
remote:        locations:
remote:          - commit: 032ab7bbbc16829df2262e10f3dea2553af5caf6
remote:            path: src/environments/environment.prod.ts:7
remote:          - commit: 032ab7bbbc16829df2262e10f3dea2553af5caf6
remote:            path: src/environments/environment.ts:11
remote:

una vez reemplazado activad los servicios en docker con el comando:

docker compose -p "burguer-queen" up -d

ya levantado docker se ejecuta la aplicación de ionic con ionic serve y listo.
