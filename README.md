Backend - Rutas disponibles

1. POST /api/auth/login
   - Body: { "email": "admin@admin.com", "password": "1234" }

2. GET /api/productos
   - Devuelve todos los productos disponibles

3. POST /api/pedidos
   - Body:
     {
       "id_usuario": 1,
       "productos": [
         { "id_producto": 1, "cantidad": 2, "subtotal": 130000 }
       ]
     }

4. GET /api/pedidos
   - Devuelve todos los pedidos guardados#   O L I M P I A D A S - 2 0 2 5 - - -  
 