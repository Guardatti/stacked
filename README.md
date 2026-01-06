# 🍔 Stacked

**Stacked** es un sistema de pedidos en tiempo real para una hamburguesería, desarrollado con el stack **MERN** y **Socket.io**.  
Permite a los clientes realizar pedidos y ver su estado en vivo, mientras que la cocina y el administrador gestionan los pedidos desde un panel operativo.

---

## 🧠 Descripción general

El objetivo del proyecto es simular un sistema real de pedidos de comida, incorporando:
- Roles de usuario
- Flujo de estados del pedido
- Comunicación en tiempo real
- Separación clara entre lógica HTTP y WebSockets

---

## 👥 Roles del sistema

### 👤 Cliente
- Ver menú
- Agregar productos al carrito
- Crear pedidos
- Ver el estado del pedido en tiempo real

### 👨‍🍳 Operador (Cocina)
- Ver pedidos entrantes en vivo
- Cambiar el estado del pedido

### 🧑‍💼 Administrador
- Gestión de productos
- Gestión de usuarios
- Vista general del sistema

---

## 🔁 Flujo de pedidos

```txt
PENNDIENTE → EN PROGRESO → PREPARADO → ENTREGADO
           ↘ CANCELLED
