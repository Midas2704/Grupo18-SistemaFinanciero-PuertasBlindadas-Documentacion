# Documentación — Sistema Financiero Puertas Blindadas (Grupo 18)

Repositorio documental del **Módulo Financiero del ERP de Puertas Blindadas**, desarrollado por el Grupo 18.

Aquí se conservan los informes, presentaciones, anexos, diagramas, planificación y demás evidencias académicas del proyecto.

## Enlaces principales

- [Código fuente e instalación local](https://github.com/Midas2704/Grupo18-SistemaFinanciero-PuertasBlindadas-Codigo)
- [Videos del proyecto en Google Drive](https://drive.google.com/drive/folders/10XG32U7vbEGat61P43QDJm6zSbIfugd_?usp=sharing)

## Integrantes

- Sebastián Benjamín Bravo Núñez
- Gianella Belén Catalán Canales
- Vicente Andrés Hernández Olea
- Daniella Rosa Catalina Lecanda Garnham
- Angella Javiera Sánchez López
- Valentín Ignacio García Farías

## Estado documental

| Entrega | Contenido disponible | Estado |
| --- | --- | --- |
| **Documento 0** | Antecedentes, presentación, currículums, planificación, levantamiento y análisis iniciales | Disponible |
| **Incremento 1** | Informe, presentación, backlog, retrospectiva, diagramas y anexos técnicos | Disponible |

La estructura del repositorio se actualizará a medida que se incorporen formalmente los entregables de los siguientes incrementos.

---

## Documento 0

Contiene los antecedentes iniciales y el levantamiento del proyecto:

- documento e informe base;
- presentación del sistema financiero;
- currículums de los integrantes;
- correo de aceptación de requerimientos;
- planificación;
- levantamiento de procesos;
- estimación de costos y beneficios;
- análisis FODA, PESTEL, Porter y Cadena de Valor;
- análisis cuantitativo y cualitativo;
- matriz de requerimientos funcionales y casos de uso;
- descripción del proceso modelado en Bizagi.

## Incremento 1

El primer incremento concentra el desarrollo documental de clientes, cotizaciones y operaciones comerciales relacionadas.

### M1 — Clientes

- registro y administración de clientes;
- actualización, activación y desactivación;
- consulta, búsqueda y filtrado;
- catálogo de clientes;
- ficha financiera y antecedentes asociados.

### M2 — Cotizaciones y Notas de Venta

- selección y registro de clientes desde cotizaciones;
- configuración de productos y especificaciones;
- determinación de costos y precios sugeridos;
- descuentos, monedas, IVA y exenciones;
- guardado, recuperación, emisión y reactivación de cotizaciones;
- creación de notas de venta B2B y B2C;
- ventas directas;
- guías de despacho y documentos tributarios;
- condiciones y etapas de cobro.

### Informe y presentación

- `Informe Incremento 1_ULTRADEFINITIVO.docx`
- `Puertas Blindadas Sistema financiero.pptx`

### Retrospectiva y planificación

- backlog del incremento;
- sprint backlog;
- retrospectiva del trabajo realizado.

### Diagramas de casos de uso

La carpeta `Incremento 1/Diagramas Casos de Uso/` contiene los casos de uso **CU01 a CU41**, incluyendo clientes, cotizaciones, notas de venta, monedas, descuentos, IVA, guías de despacho, documentos tributarios y condiciones de cobro.

### Diagramas de secuencia

La carpeta `Incremento 1/Diagramas de Secuencia/` contiene los flujos de interacción correspondientes a las principales operaciones del incremento. Los archivos que requieren revisión se mantienen identificados en su nombre para conservar la trazabilidad documental.

### Anexos técnicos

El incremento incluye:

- modelo entidad-relación del módulo financiero;
- diagramas de componentes;
- diagrama de despliegue;
- árbol de navegación;
- guía de creación del modelo de datos.

---

## Organización del repositorio

```text
Grupo18-SistemaFinanciero-PuertasBlindadas-Documentacion/
├── Documento 0/
│   ├── Anexo/
│   ├── CV/
│   ├── Documento 0 _v1.docx
│   └── Sistema Financiero Puertas Blindadas.pptx
└── Incremento 1/
    ├── Anexo/
    ├── Diagramas Casos de Uso/
    ├── Diagramas de Secuencia/
    ├── Retrospectiva/
    ├── Informe Incremento 1_ULTRADEFINITIVO.docx
    └── Puertas Blindadas Sistema financiero.pptx
```

## Formatos utilizados

| Extensión | Contenido | Aplicación sugerida |
| --- | --- | --- |
| `.docx` | Informes, anexos y currículums | Microsoft Word o LibreOffice Writer |
| `.pptx` | Presentaciones | Microsoft PowerPoint o LibreOffice Impress |
| `.xlsx` | Planificación, backlog y análisis | Microsoft Excel o LibreOffice Calc |
| `.drawio` | Diagramas técnicos y funcionales | [diagrams.net](https://app.diagrams.net/) |
| `.png` | Evidencias e imágenes de apoyo | Visor de imágenes o navegador |

## Relación con el sistema

La implementación funcional se encuentra en el repositorio de código:

```text
Midas2704/Grupo18-SistemaFinanciero-PuertasBlindadas-Codigo
```

Ese repositorio contiene:

- frontend React y TypeScript;
- backend Node.js, Express y TypeScript;
- Prisma y PostgreSQL;
- migraciones;
- pruebas automatizadas;
- base de datos académica restaurable;
- instalación local mediante Docker Desktop.

## Consideraciones

- Mantener los nombres y la estructura de los entregables para conservar su trazabilidad.
- No incluir credenciales, archivos `.env`, claves privadas ni información sensible.
- Incorporar nuevas versiones sin eliminar arbitrariamente documentos históricos.
- Los diagramas marcados como pendientes de revisión no deben presentarse como versiones finales.
- Los cambios funcionales del sistema deben mantenerse sincronizados con la documentación correspondiente.

## Repositorio

`Midas2704/Grupo18-SistemaFinanciero-PuertasBlindadas-Documentacion`

---

Proyecto desarrollado por el Grupo 18 para Puertas Blindadas.
