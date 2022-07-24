# Desafio entregable 42: TESTEAMOS NUESTRA API REST

## Para probar el código:

```bash
# Clonar el repositorio
git clone https://github.com/emmapinto/backend-30920-entrega-clase42.git

# Instalar dependencias
npm install

# Iniciar el servidor con los diferentes modos de persistencia
node index.js # --> Por defecto con MongoDB

# Modificar la variable de entorno PERSISTENCIA en el .ENV:
PERSISTENCIA=firebase # --> para Firebase
PERSISTENCIA=memory # --> para memoria

```

## Para realizar las pruebas implementadas: 

- Pruebas con cliente AXIOS:
    - Visitar http://localhost:8080/pruebas
    - Las pruebas se muestran por consola

- Pruebas con Mocha, Chai y Supertest ejecutar el servidor y luego correr el comando:
```bash
# Con el servidor iniciado en el modo que se quiera probar:
npm run test
```

#### Los reportes para cada uno de los métodos de persistencia se encuentran en el directorio tests/reports