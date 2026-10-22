# Técnicas y demostraciones

## Reductio ad absurdum (prueba por contradicción)
**Cuándo**: demostrar que algo es imposible o que una propiedad debe cumplirse.
**Cómo**: supón lo contrario, razona con lógica estricta, llega a una contradicción.
**Ejemplo canónico**: √2 no es fracción (si √2=m/n sin factores comunes, m y n resultan ambos pares → contradicción).

## Inducción matemática
**Cuándo**: probar que algo vale para todos los enteros n.
**Cómo**: (1) base: vale para n=1; (2) paso: si vale para n, vale para n+1.

## Argumento diagonal de Cantor
**Cuándo**: mostrar que un conjunto no es contable.
**Cómo**: supón una lista completa; construye un elemento que difiere de cada fila en la diagonal → no estaba en la lista.
**Resultado**: los reales son "más infinitos" que los racionales.

## Correspondencia uno-a-uno
**Cuándo**: comparar tamaños de conjuntos infinitos.
**Cómo**: empareja elementos; si hay biyección, mismo cardinal (pares ↔ naturales).

## Criba de Eratóstenes
**Cuándo**: listar los primos hasta N.
**Cómo**: tacha múltiplos de 2, luego de 3, 5, 7…; lo que queda son primos.

## Algoritmo de Euclides (MCD)
**Cómo**: divide a entre b, toma el resto r; repite con (b, r) hasta r=0; el último divisor es el MCD.

## Factorización en primos
**Cómo**: divide por el primo más pequeño posible, repite con el cociente. El resultado es único (teorema fundamental).

## Conversión fracción → decimal
**Cómo**: divide numerador entre denominador llevando restos ×10; termina (finito) o se repite (periódico).

## Programación lineal (símplex)
**Cuándo**: minimizar/maximizar una función lineal con restricciones lineales (dieta, producción).
**Cómo**: la solución óptima está en un vértice del poliedro factible; el símplex recorre vértices mejorando.

## Teorema de Bayes (actualización)
**Cómo**: `P(H|E) = P(E|H)·P(H) / P(E)`. Parte de la tasa base P(H) y corrige con la evidencia.
**Trade-off**: ignorar la tasa base lleva a la "falacia del fiscal" (sobreestimar tras un test positivo raro).

## Aproximación por polígonos (método de exhaución)
**Cuándo**: calcular áreas/π antes del cálculo.
**Cómo**: inscribe/circunscribe polígonos de más y más lados; el límite da el valor exacto (Arquímedes).

## Multiplicación de complejos
**Cómo**: (a+bi)(c+di) = (ac−bd) + (ad+bc)i, usando i²=−1.

## Colorear grafos / mapas
**Cuándo**: asignar recursos evitando conflictos (horarios, frecuencias).
**Cómo**: modela como grafo; colorea vértices adyacentes distinto. Mapas planos: 4 colores bastan.
