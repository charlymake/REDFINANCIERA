# Red Financiera

Bitácora financiera personal y de negocio: ventas diarias, gastos, tarjetas de crédito y estadísticas.

## Qué hace

- **Bitácora**: registro diario de ventas, gastos de negocio y gastos personales
- **Tarjetas**: seguimiento de saldo, utilización y pagos de Nu y BBVA
- **Resumen**: tendencia de ventas, patrón por día de semana, margen real, costo de la deuda y gastos hormiga

## Sincronización

Los datos se guardan en el dispositivo y se sincronizan automáticamente en la nube (Supabase) al iniciar sesión.

El indicador en la esquina superior derecha muestra el estado:
- **Verde** — sincronizado con la nube
- **Naranja** — trabajando solo en este dispositivo

Si te quedas sin internet, la app sigue funcionando y sincroniza cuando vuelve la conexión.

## Configuración inicial

1. Ejecutar `supabase-setup.sql` en Supabase → SQL Editor
2. Pegar el Project URL y la anon key en las primeras líneas de `index.html`
3. Crear cuenta desde la app

## Respaldo manual

Resumen → Exportar respaldo genera un archivo `.json` con todos los movimientos. Se puede importar desde cualquier dispositivo.

## Instalar en el celular

**iPhone (Safari):** Compartir → "Agregar a pantalla de inicio"
**Android (Chrome):** menú ⋮ → "Agregar a pantalla principal"

## Archivos

- `index.html` — la aplicación completa
- `supabase-setup.sql` — configuración de la base de datos
