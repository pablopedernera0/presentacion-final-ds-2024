# Presentacion√trabajos finales

## Analisis  preliminar
  
  - Presentacion de la empresa
  - Debe incluir:
    - Historia
    - Rubro
  - Analisis  de la problematica  actual de la empresa, con enfoque en los problemas tecnologicos detectados
## Solucion propuesta
   ### Diagramas:
     - Modelo de Entidad Relacion 4 entidades)
         Usuarios
         Roles
         Ventas
         Ventas_detalle
         Productos
         Proveedores
         Clientes

    ### Diagrama de clases
        Usuario
            id
            nombre
            apellido
            username
            password
            email
            telefono
            rol_id (Roles)
        Roles
            id
            nombre_rol
        Ventas
            id
            cliente_id(Clientes)
            fecha
            monto_total
            vendedor (usuario)
            condicion
        Ventas_detalle
            id
            venta_id(Ventas)
            producto_id(Productos)
            cantidad
            precio_unitario
            precio_total
        Productos
            id
            nombre_producto
            descripcion
            precio
            proveedor_id(Proveedores)
            existencia
        Proveedores
            id
            nombre
            direccion
            email
            pagina_web
            telefono
            condiciones
            cuit
        Clientes
            id
            nombre
            direccion
            email
            telefono
            condiciones
            cuit
