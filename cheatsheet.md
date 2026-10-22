# Chuleta — fórmulas, constantes y reglas

## Constantes
| Símbolo | Valor | Qué es |
|---|---|---|
| π | 3.14159… | circunferencia/diámetro; irracional, trascendente |
| e | 2.71828… | crecimiento continuo; irracional, trascendente |
| φ | 1.61803… | áureo; φ²=φ+1 = (1+√5)/2 |
| i | √−1 | unidad imaginaria; i²=−1 |
| ℵ₀ | — | cardinal del infinito contable |

## Fórmulas que conviene tener a mano
| Tema | Fórmula |
|---|---|
| Círculo | C = 2πr · A = πr² |
| Esfera | A = 4πr² · V = (4/3)πr³ |
| Pitágoras | a² + b² = c² |
| Cuadrática | x = (−b ± √(b²−4ac)) / 2a |
| Euler (identidad) | e^(iπ) + 1 = 0 |
| Euler (poliedros) | V − E + F = 2 |
| Bayes | P(H|E) = P(E|H)·P(H) / P(E) |
| Interés compuesto | A = P(1 + r/n)^(nt) |
| Regla del 72 | años para duplicar ≈ 72 / tasa% |
| Nº primos < n | π(n) ≈ n / ln n |

## Reglas de decisión
- **¿Es irracional?** Si su decimal es infinito y no periódico → irracional. Periódico → fracción.
- **¿Correlación implica causa?** NO. r alto solo indica asociación.
- **Test positivo de enfermedad rara** → mira la tasa base antes de alarmarte (Bayes).
- **¿Cuántas personas para 50% de cumpleaños compartido?** 23 (cuenta pares, no personas).
- **Optimizar con restricciones lineales** → programación lineal (símplex); la solución está en un vértice.
- **Ruta por muchas ciudades (TSP)** → NP-difícil; usa heurística, no fuerza bruta.
- **Colorear un mapa plano** → 4 colores siempre bastan.
- **¿Camino que cruce cada arista una vez (euleriano)?** Existe si ≤2 vértices tienen grado impar.

## Regla 68–95–99.7 (curva normal)
Dentro de μ±1σ ≈ 68% · μ±2σ ≈ 95% · μ±3σ ≈ 99.7%.

## Tipos de demostración (elige)
| Meta | Técnica |
|---|---|
| Probar imposibilidad | reductio ad absurdum |
| Probar "para todo n" | inducción |
| Refutar una afirmación | un contraejemplo basta |
| Mostrar no-contable | diagonal de Cantor |
