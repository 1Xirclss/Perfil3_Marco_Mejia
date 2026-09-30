# Fake Store Explorer

Aplicación móvil realizada con React Native y Expo para la evaluación práctica del 15 %.

## Datos del estudiante

- Nombre: Marco Mejía
- Carnet: 20210318
- Sección: B1
- Grupo: 1

## Enlaces

- [Descargar e instalar el APK](https://expo.dev/accounts/1xirclss/projects/evaluacion-fakestore-20210318/builds/9c5dc515-3c0c-4861-9bab-d2b9a40df9f6)
- Video de demostración: pendiente

## Funciones

- Muestra los datos del estudiante en la pantalla de inicio.
- Consulta los productos de [Fake Store API](https://fakestoreapi.com/products).
- Permite buscar productos por nombre o descripción.
- Incluye estados de carga, error y actualización del catálogo.
- Utiliza React Navigation para cambiar entre las pantallas.

## Ejecutar el proyecto

```bash
npm install
npx expo start
```

Para probarlo en un teléfono se puede escanear el código QR con Expo Go. La consulta de productos necesita conexión a internet.

## Generar un nuevo APK

```bash
npx eas-cli login
npx eas-cli build --platform android --profile preview
```
