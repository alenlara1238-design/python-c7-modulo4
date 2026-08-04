# Caso de Estudio

## Desarrollo del Sistema de Gestión de Inventario y Ventas para Dev Store

## Contexto

La empresa Dev Store es un pequeño negocio dedicado a la venta de equipos y accesorios tecnológicos. Entre sus productos se encuentran computadores, monitores, teclados, mouse, discos SSD, memorias RAM, audífonos y otros periféricos.

Durante los últimos años el negocio ha crecido considerablemente. Lo que antes era una tienda pequeña con pocos productos ahora recibe decenas de clientes diariamente y maneja un inventario mucho más amplio.

A pesar de ese crecimiento, la empresa continúa administrando toda su información de manera manual. Los empleados registran los productos en hojas de cálculo y anotan las ventas en cuadernos físicos. Este método ha comenzado a generar numerosos inconvenientes que afectan tanto la operación diaria como la atención al cliente.

Por esta razón, la gerencia de Dev Store ha decidido contratar un equipo de desarrollo de software para construir una aplicación que permita administrar el inventario y registrar las ventas de forma organizada, segura y eficiente.

Ese equipo de desarrollo serán ustedes.

## Situación actual

Actualmente la tienda enfrenta los siguientes problemas.

### Problema 1. Productos duplicados

Con frecuencia un mismo producto es registrado varias veces utilizando códigos diferentes o escribiendo nuevamente la información por error.

Por ejemplo:

```text
Código: P001
Mouse Logitech G203

Código: P001
Mouse Logitech G203
```

Esto provoca inconsistencias en el inventario.

### Problema 2. No conocen el inventario real

Muchas veces un vendedor ofrece un producto al cliente sin saber si realmente existe en bodega.

Cuando el cliente llega a pagar, descubren que el producto ya no está disponible.

Esto genera pérdida de ventas y mala experiencia para el cliente.

### Problema 3. El stock nunca coincide

Cuando se vende un producto, el empleado debe descontarlo manualmente del inventario.

En ocasiones olvida hacerlo.

Como consecuencia, el sistema muestra cantidades incorrectas.

**Ejemplo:**

```text
Monitor Samsung

Stock registrado:
12

Stock real:
7
```

### Problema 4. No existe historial de ventas

Después de vender un producto, la información desaparece o queda registrada únicamente en un cuaderno.

La empresa no puede responder preguntas como:

- ¿Cuántas ventas realizamos hoy?
- ¿Cuál fue el producto más vendido?
- ¿Cuánto dinero ingresó esta semana?

### Problema 5. Se pierde toda la información

Cada vez que cambian de computador o cierran un archivo, parte de la información desaparece.

No existe una forma organizada de conservar los registros.

## Nuestra misión

La empresa ha contratado a Dev Senior Code para desarrollar la primera versión del sistema.

Nuestro objetivo será construir una aplicación de consola que permita administrar toda la operación básica del negocio.

Durante las próximas ocho clases iremos desarrollando el sistema paso a paso, agregando nuevas funcionalidades hasta obtener una aplicación completamente funcional.

## Requerimientos del cliente

Después de varias reuniones con la gerencia de Dev Store, se definieron los siguientes requerimientos.

El sistema debe permitir:

- Registrar nuevos productos.
- Consultar todos los productos registrados.
- Buscar un producto mediante su código.
- Eliminar productos del inventario.
- Registrar ventas.
- Verificar que exista suficiente stock antes de vender.
- Descontar automáticamente las unidades vendidas.
- Consultar el historial de ventas.
- Calcular el valor total vendido.
- Guardar toda la información para que permanezca disponible al cerrar y volver a abrir el programa.
