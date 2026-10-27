# AstroShield — Evolucionar una constelación inteligente

Algoritmo evolutivo que diseña una constelación de 8 satélites para observar 6 regiones de la Tierra, respetando zonas restringidas por desechos espaciales y posiciones ocupadas. Incluye pruebas automáticas, análisis y un **centro de mando 2D/3D** con estética Cyberpunk.

> Modelo educativo y simplificado: satélites estáticos sobre una esfera, sin mecánica orbital real.

## Resultados (semilla 2026)

- Calidad final F = 0.8923, igual a la cota teórica; 6 de 6 regiones cubiertas.
- Zonas de desechos y posiciones ocupadas respetadas (margen mínimo 17.37°).
- 20 ejecuciones: F = 0.8908 ± 0.0069; 19 de 20 llegan a la cota.
- Evolutivo vs. búsqueda aleatoria con el mismo presupuesto: 0.8908 contra 0.5040 (p = 5.1e-9).

## Limitaciones

Cobertura circular y estática; el radio del sensor (1 000 km), los pesos de prioridad y el umbral de cobertura son supuestos del equipo; el algoritmo no penaliza mover satélites al reoptimizar. Ver el documento en `docs/`.

## Declaración de uso de IA

Ver la sección 5 del documento técnico.
