# Módulo de Gestión de Proyectos y Facturación – Nébula Software S.R.L.

> Trabajo Práctico Integrador y Progresivo (TPI) – Organización Empresarial
> Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional (UTN)

## Descripción del sistema

Nébula Software S.R.L. es una empresa argentina (ficticia, caso de estudio) dedicada al desarrollo de software a medida y productos digitales para pymes.

El **Módulo de Gestión de Proyectos y Facturación** centraliza tres funciones que hoy se resuelven de forma manual:

1. El registro de las horas trabajadas por cada desarrollador en cada proyecto.
2. El seguimiento del avance de cada proyecto frente a lo estimado.
3. La generación automática de la factura al cliente a partir de las horas aprobadas.

## Integrantes

| Nombre | Rol |
|---|---|
| Giuliano Giarrosso | Autor (entrega individual) |

## Estructura del repositorio

```
/
├── README.md
├── docs/
│   ├── bpmn/diagrama_bpmn.png        # Proceso de facturación (BPMN 2.0)
│   ├── historias-de-usuario.md       # HU-01, HU-02 y HU-03
│   └── indicadores-de-control.md     # KPIs y estándares de desempeño
└── entregas/                         # Entregas 1 a 3 del TPI
```

## Flujo de trabajo en Git

- `main`: rama estable, solo recibe cambios mediante Pull Request.
- `docs/<tema>`: ramas secundarias de documentación (por ejemplo `docs/bpmn`, `docs/indicadores`).
- Mensajes de commit descriptivos, en imperativo y con prefijo: `docs:`, `fix:`, `chore:`.
- Todo cambio a `main` se integra con un Pull Request revisado por al menos una persona.

## Tablero de gestión

El backlog se gestiona en GitHub Projects: **[PEGAR ENLACE DEL TABLERO]**

| Historia | Descripción |
|---|---|
| HU-01 | Registro y aprobación de horas trabajadas |
| HU-02 | Seguimiento del avance de proyectos |
| HU-03 | Facturación automática |

Estados del tablero: **Por Hacer → En Progreso → Listo**.

## Indicadores de control

Derivados de las metas de la Entrega N°2 del TPI.

| Indicador | Fórmula | Estándar |
|---|---|---|
| Reducción del tiempo de facturación manual | (Horas semanales previas − actuales) / previas × 100 (base: 3 h semanales por administrativo) | ≥ 80 % (menos de 30 min semanales) |
| Horas cargadas en el módulo | Horas registradas dentro de las 24 h / horas trabajadas × 100 | 100 % con latencia máxima de 24 h |
| Tiempo de respuesta por consulta | Promedio de segundos por consulta con 50 proyectos activos | < 2 segundos |
| Cumplimiento del plazo | Semanas reales de desarrollo e implementación | ≤ 10 semanas |
| Facturas emitidas sin reclamo (complementario) | Facturas sin reclamo / facturas emitidas × 100 | ≥ 95 % |

## Declaración de Uso de IA

**[COMPLETAR CON TU PROPIA REDACCIÓN: ver la sección 4.2 del documento de la entrega.]**

Se utilizó un asistente de IA generativa (Claude, de Anthropic) como apoyo para estructurar el trabajo. Esta sección debe indicar:

- Qué prompts se usaron y para qué.
- Qué devolvió el asistente.
- Qué corrigió, descartó o agregó el autor, y por qué.

La responsabilidad sobre la veracidad y coherencia del contenido es del autor.
