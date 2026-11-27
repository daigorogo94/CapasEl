# CapasEL — escaparate público

![CapasEL — plugin cosmético para Entertainment LAND](assets/capasel-showcase.jpg)

**CapasEL** es un sistema de cosméticos para servidores Minecraft Paper que permite a los jugadores equipar capas visuales personalizadas, con animación de movimiento, permisos y recursos gráficos propios.

Este repositorio es un **escaparate informativo**. No contiene el código fuente, las clases Java, los archivos Gradle ni la configuración interna del plugin.

## Qué ofrece

- **Capas personalizadas:** diseños visuales para distinguir jugadores y rangos.
- **Movimiento dinámico:** la capa acompaña al jugador al caminar, saltar o caer.
- **Control de acceso:** permisos configurables para decidir quién puede utilizar cada diseño.
- **Integración visual:** modelos y texturas se entregan mediante un resource pack.
- **Optimización:** el proyecto contempla actualización condicional y reducción de trabajo cuando no hay capas activas.

## Cómo funciona — explicación general

1. **Diseño:** se prepara una textura PNG a partir de una plantilla.
2. **Recurso visual:** el diseño se integra en un resource pack con sus modelos.
3. **Selección:** el jugador elige una capa disponible según sus permisos.
4. **Representación:** el servidor muestra el cosmético asociado al jugador.
5. **Movimiento:** el sistema actualiza la representación para acompañar las acciones del jugador.

> La descripción es deliberadamente de alto nivel. No se publican algoritmos, estructuras internas, código, parámetros sensibles ni detalles de implementación que permitan reconstruir el plugin.

## Plantillas de diseño

Las plantillas sirven como guía gráfica para crear texturas. Se incluyen varias resoluciones para trabajar con distintos niveles de detalle.

| Plantilla | Uso |
|---|---|
| 32 × 32 | Diseño muy compacto |
| 64 × 64 | Diseño compacto |
| 128 × 128 | Más detalle |
| 256 × 256 | Edición de alta resolución |

![Guía visual de las plantillas](assets/guia_visual.png)

## Tecnología

- Minecraft Java Edition
- Paper API 1.21.11
- Java 21
- Resource packs con modelos y texturas
- Integración opcional con PlaceholderAPI

La compatibilidad y el rendimiento deben verificarse en el entorno concreto del servidor y del cliente.

## Comandos para jugadores y administración

La interfaz de comandos contempla selección, consulta y retirada de capas, además de herramientas administrativas para asignar y gestionar cosméticos. Los comandos exactos pueden variar según la configuración instalada.

## Limitaciones conocidas

- La versión documentada está dirigida a clientes Java.
- La representación descrita no ofrece compatibilidad directa con Bedrock/Geyser.
- La capa es una pieza visual rígida con movimiento simulado; no es una tela física deformable.
- Las plantillas son recursos de diseño, no un editor gráfico completo.

## Privacidad y propiedad del código

Este repositorio muestra el producto y sus recursos gráficos de demostración. **El código fuente de CapasEL se mantiene privado** y no se distribuye desde este escaparate.

Para consultas sobre el proyecto: abre una discusión o contacta al mantenedor del repositorio.

---
**CapasEL · Entertainment LAND**
