# CHALLENGE ALURA STORE LATAM

## Challenge Alura Store Latam

Este repositorio contiene mi progreso en el Challenge de Data Science de Alura Latam.  
El objetivo es practicar Python y análisis de datos con los archivos de ventas de la tienda.

## Primer análisis: Ingreso total por tienda
En esta etapa calculé el ingreso total de cada tienda sumando la columna **Precio**.  
Usé un bucle `for` con `enumerate` porque me resulta más claro para entender cada DataFrame.

### Código utilizado
```python
tiendas = [tienda, tienda2, tienda3, tienda4]

for i, t in enumerate(tiendas, start=1):
    ingreso = t["Precio"].sum()
    print(f"Ingreso tienda {i}: {ingreso}")

Ingreso tienda 1: 1150880400.0
Ingreso tienda 2: 1116343500.0
Ingreso tienda 3: 1098019600.0
Ingreso tienda 4: 1038375700.0


---

👉 Este bloque mantiene un estilo **sobrio y junior**:  
- Explica el propósito sin sonar demasiado técnico.  
- Muestra el código limpio y claro.  
- Incluye un ejemplo de salida para que sea fácil de visualizar.  
- Deja explícito que el README se irá completando más adelante.  

¿Quieres que lo dejemos así como tu **primer bloque oficial de README** y luego, cuando lleguemos a la parte de gráficos, añadimos otro bloque debajo con las visualizaciones?

