Las imagenes estan subidas en Docker Hub, pero si quieres crear tus propias imagenes, solamente mueve los dockerfiles que hay en los subdirectorios hacia sus correspondientes subdirectorios de submodulos sobreescribiendo. Recuerda hacer `git submodule init --recursive`.
Ejemplo de `.env` para docker-compose:
```yaml
MONGO_USERNAME="superuser"
MONGO_PASSWORD="*******"
MONGO_URI="mongodb://mongodb:27017/vivebook_DB"
SERVER_PORT="1337"
JWT_ACCESS_SECRET="LLAVE TEMPORAL, PORFAVOR CAMBIAME"
JWT_REFRESH_SECRET="Lorem Ipsum"
JWT_ACCESS_EXPIRES_IN="15m"
JWT_REFRESH_EXPIRES_IN="7d"
SWAGGER_URL="localhost"
SWAGGER_PORT="1337"
```
## declaracion de IA:
Ninguno.

## Referencias
+ [Docker compose](https://anderfernandez.com/blog/tutorial-docker-compose/)
+ [Volumenes](https://therahulsarkar.medium.com/understanding-docker-volumes-a-comprehensive-guide-46339aa9ac53)
+ [Networking](https://medium.com/@triwicaksono.com/networks-in-docker-compose-0943abe3de54)
+ [Modern MERN full stack development](https://link.springer.com/book/10.1007/978-1-4842-5738-8)
