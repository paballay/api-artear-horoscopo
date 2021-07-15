# Landing Horóscopo

### Servidor
Instalar las dependencias del proyecto y ejecutar el script start.
Luego se pueden obtener los datos de la siguiente forma:
- obtener todos los datos: http://localhost:3001/zodiac_signs
- obtener un dato a partir de un par (key,value): http://localhost:3001/zodiac_signs?key=value

Para más información consultar https://github.com/typicode/json-server
### API
La API posee una validación de las peticiones mediante el envío del header "Authorization" cuyo valor debe ser "qazwsx"
