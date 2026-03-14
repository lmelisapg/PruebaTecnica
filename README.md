# Prueba Técnica – Consultor Analítico
Laura Melisa Patarroyo Godoy

## Problema de negocio
Una compañía de telecomunicaciones peruana busca establecer accionables estratégicos y de negocio orientados a reducir las intenciones de cancelación de servicio y el abandono de clientes (churn). Para lo anterior, se realizó una segmentación de clientes y se identificó un clúster crítico (cluster 3) con alta propensión al churn y elevadas intenciones de cancelación. O
El objetivo de este análisis es identificar los principales motivos de cancelación y diseñar iniciativas focalizadas para este Cluster clave (cluster3), con el fin de reducir el churn

---

# Estructura del análisis
El análisis se desarrolló en las siguientes etapas:

1. Exploración de datos (EDA) y Perfilamiento del cluster crítico
2. Análisis de transcripciones de llamadas usando NLP
3. Identificación de motivos de churn (Relacion hallazagos EDA y NLP)
4. Diseño de estrategias de retención (reactivas y proactivas)
5. Definición de métricas de impacto

---

# Principales hallazgos

Perfil del Cliente: Clientes con alta antigüedad (~80 meses) y usuarios de Triple Play.
Puntos de dolor: El 37.8% presenta reclamos mensuales y el 12.1% sufre interrupciones de servicio (downtime).
Motivos de cancelación: Facturación, fallas técnicas y deficiencias en la experiencia del cliente.

---

# Iniciativas estratégicas propuestas
1. Acciones Reactivas
- Gestión prioritaria de reclamos.
- Protocolo de resolución acelerada para fallas técnicas.
- Resolución rápida de inconsistencias en facturación.

2.Proactivas
- Alertas preventivas de facturación.
- Monitoreo preventivo de red.
- Programas de seguimiento para clientes con reclamos recurrentes.
- Bundles de fidelización con servicios de streaming.

---

# Métricas de impacto

| Métrica | Valor actual | Objetivo |
Intención de cancelación | 19.5% | 14–16% |
Clientes con reclamos | 37.8% | <34% |
Clientes con downtime | 12.1% | <10% |

---

# Tecnologías utilizadas
- Python
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-learn
- NLP (CountVectorizer)

---

# Ejecución del análisis

El dataset principal se carga desde Google Drive debido a su tamaño.
Las transcripciones de llamadas se cargan desde este repositorio
El análisis completo se encuentra en el notebook: notebooks/PruebaTecnica_Melisa.ipynb
