# Prueba Tecnica Double V Partners
Ecommerce ShopDVP

Este repositorio contiene las pruebas de API realizadas con **Postman** para la tienda de e-commerce ShopDVP. Las pruebas incluyen los endpoints para listar productos, agregar y eliminar un producto (Actualizar se encuentra en la documentacion de las pruebas pero no pudo ser probado debido a un error en el servidor)


La colección exportada está disponible en el archivo `Prueba Tecnica AF.postman_collection`. Para importarla en Postman:

## Endpoints probados

### 1. Listar Productos
- **Método**: `GET`
- **URL**: `https://fakestoreapi.com/products`
- **Descripción**: Obtiene la lista de productos disponibles en la tienda.

### 2. Agregar Producto
- **Método**: `POST`
- **URL**: `https://fakestoreapi.com/products`
- **Body**:
```json
{
  "title": "Nuevo Producto",
  "price": 49.99,
  "description": "Descripción del nuevo producto",
  "image": "https://example.com/nuevo-producto.jpg",
  "category": "electronics"
} 
```
### 3. Actualizar caracteristicas del producto
- **Método**: `PUT`
- **URL**: `https://fakestoreapi.com/products/7`
- **Body**:
```json
{
  "title": "Producto Actualizado",
  "price": 59.99,
  "description": "Descripción del producto actualizado.",
  "image": "https://i.pravatar.cc",
  "category": "electronics"
}
```
### 3. Eliminar producto
- **Método**: `PUT`
- **URL**: `https://fakestoreapi.com/products/7`
- **Descripción**: Elimina el producto que se filtre.











