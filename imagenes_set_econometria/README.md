#

# Test AB

graph TD
    A[Audiencia] --> B{División en dos grupos aleatorios};
    B --> C[Grupo A (50%)];
    B --> D[Grupo B (50%)];
    C --> E[Expuesto a la Versión A (ej. Botón azul)];
    D --> F[Expuesto a la Versión B (ej. Botón rojo)];
    E --> G{Resultados (Tasa de clics, conversiones, etc.)};
    F --> H{Resultados (Tasa de clics, conversiones, etc.)};
    G & H --> I[Análisis de datos];
    I --> J{¿Versión A o B es mejor?};
    J --> K[Implementación de la versión ganadora];
