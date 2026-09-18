# Servia TPV

Terminal punto de venta para bares y restaurantes, para Windows 10 y 11.

Este repositorio solo contiene los **instaladores** de Servia TPV. La aplicación instalada se actualiza sola
desde aquí.

## Descargar

El instalador de cada versión está en la sección **Releases** de este repositorio (a la derecha de esta página).
Abre la versión marcada como **Latest** y descarga el archivo `ServiaTPV-X.Y.Z-instalador.exe` de su apartado
*Assets*. Allí están también las notas de cada versión.

## Instalar

1. Abre el instalador descargado (`ServiaTPV-X.Y.Z-instalador.exe`).
2. Windows puede mostrar **«Windows protegió su PC»** porque el instalador no está firmado digitalmente.
   Pulsa **Más información → Ejecutar de todas formas**. Solo ocurre en la primera instalación.
3. Sigue el asistente: se instala para tu usuario (no hace falta ser administrador) y crea accesos directos en el
   escritorio y en el menú Inicio.
4. Al abrir Servia TPV por primera vez elige:
   - **Empezar con mi negocio**: indicas los datos del negocio y tu PIN de administrador, y añades la carta, las
     mesas y los empleados.
   - **Probar con datos de demostración**: un bar de ejemplo para conocer la aplicación. Los PIN de prueba se
     muestran en la pantalla de acceso. Para pasar después a tu negocio: *Ajustes → Datos y copias → Empezar de cero*.

## Actualizaciones

Servia TPV busca versiones nuevas al abrirse y cada pocas horas y las descarga en segundo plano. Cuando hay una
lista aparece **«Actualizar a X.Y.Z»** en la barra superior; si no se pulsa, se instala al cerrar la aplicación.
Antes de instalar se guarda una copia de seguridad de los datos. Se puede configurar en
*Ajustes → Datos y copias → Actualizaciones*.

## Tus datos

Los datos se guardan en tu equipo, en `%APPDATA%\Servia TPV\data`, con copias de seguridad diarias. No se borran
al actualizar ni al desinstalar. Desde *Ajustes → Datos y copias* puedes exportar y restaurar copias.

## Requisitos

- Windows 10 u 11 de 64 bits.
- Conexión a Internet para las actualizaciones, los pedidos online y el envío de facturas a la AEAT
  (VERI*FACTU). El resto funciona sin conexión.
