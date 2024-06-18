# Evaluación final del Módulo 1 - Proyecto de tienda online

Este proyecto implementa una tienda en línea básica donde se pueden agregar, buscar, actualizar y eliminar productos del inventario. 
Además, permite registrar y gestionar clientes, procesar compras y calcular el valor total del inventario y las ventas.

## Instrucciones de instalación y uso

### Requisitos previos
- Python 3.x
- Editor de texto o IDE (por ejemplo, VSCode, PyCharm)

### Instalación

1. Clona el repositorio o descarga los archivos del proyecto.
2. Asegúrate de tener Python instalado en tu sistema. 

### Uso

La clase `OnlineStore` proporciona varios métodos para gestionar el inventario, los clientes y las ventas. Aquí se detallan algunos de los métodos principales:

#### Agregar un producto
```python
store.add_product('camisa', 20, 10)
```
#### Ver el inventario
```python
store.view_inventory()
```
#### Buscar un producto
```python
store.search_product('camisa')
```
#### Actualizar stock
```python
store.update_stock('camisa', 5)
```
#### Eliminar un producto
```python
store.remove_product('camisa')
```
#### Calcular el valor total del inventario
```python
store.calculate_inventory_value()
```
#### Registrar una compra
```python
store.make_purchase()
```
#### Procesar un pago
```python
store.process_payment(100)
```
#### Agregar un cliente
```python
store.add_customer('Juan López', 'juanlopez@example.com')
```
#### Ver todos los clientes
```python
store.view_customers()
```
#### Ver compras de un cliente
```python
store.view_customer_purchases('Juan López')
```
#### Calcular ventas totales
```python
store.calculate_total_sales()
```

### Ejemplos de uso

A continuación, se presentan algunos ejemplos de cómo usar la clase `OnlineStore`:

```python
# Crear una instancia de la tienda
store = OnlineStore()

# Agregar productos
store.add_product('camisa', 20, 10)
store.add_product('pantalón', 30, 5)

# Ver inventario
store.view_inventory()

# Buscar un producto
print(store.search_product('camisa'))

# Actualizar stock
store.update_stock('camisa', 5)

# Eliminar un producto
print(store.remove_product('pantalón'))

# Calcular el valor total del inventario
print(store.calculate_inventory_value())

# Registrar una compra
store.make_purchase()

# Agregar un cliente
store.add_customer('Juan López', 'juanlopez@example.com')

# Ver todos los clientes
store.view_customers()

# Ver compras de un cliente
store.view_customer_purchases('Juan López')

# Calcular ventas totales
print(store.calculate_total_sales())
```

## Licencia

No hay licencia.

## Información de contacto

Autor: Maíra Pitelli

Si tienes alguna pregunta o sugerencia, por favor contacta al autor.
