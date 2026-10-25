# Datos

El generador y los totales del perfil de aula ya están en esta carpeta. La semilla es 2026. No cambiéis argumentos: otro perfil produciría otros totales.

Desde la raíz del repositorio:

```text
python datos/generar_cierre.py --salida datos/bruto
python datos/generar_cierre.py --salida datos/bruto --comprobar datos/totales_esperados.json
```

La segunda orden vuelve a leer los CSV y tiene que terminar diciendo que coinciden. Si no coinciden, revisad la lectura, el filtro del cierre y la agregación. No corrijáis el JSON.

El bruto queda en `datos/bruto/` y no se sube. `totales_esperados.json` sí se sube: es pequeño y fija noches e importe por hotel, cancelaciones por canal y lecturas de sensores.

Anotad en cada evidencia la ruta local y el tamaño medido. El perfil de aula ocupa 1 037 243 783 bytes.
