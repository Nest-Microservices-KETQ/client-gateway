## Cliente Gateway

El gateway es el punto de comunicacion entre nuestros clientes y servicios. Es el envargado de recibir las peticiones, enviarlas a los servicios correspondientes y devolver la respuesta al cliente.

## Dev
1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migracion del prisma `npx prisma migrate dev`
5. Ejecutar `npm run start:dev`


## Nats

docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats