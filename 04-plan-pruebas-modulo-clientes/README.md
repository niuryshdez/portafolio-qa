# Plan de pruebas — ERP contable

**Período:** Julio – Noviembre 2026
**Contexto:** Trabajo freelance para una empresa de software (ERP contable)
**Mi rol:** QA Tester

## Mantenimiento de Clientes — Diseño y ejecución de pruebas

**Qué es:** Módulo de clientes de un ERP contable recién migrado de AngularJS a Angular, probado en ambiente de integración antes de declarar el sistema Release Candidate.
**Qué hice:** Diseñé un plan de 49 casos organizados en 5 bloques (camino feliz, campos obligatorios, formato y límites, reglas de negocio, y buscar, editar y exportar), y sumé 9 casos exploratorios durante la ejecución. De los 58 casos, pasaron 50 y fallaron 8. Reporté 4 defectos y 1 mejora, cada uno vinculado a sus casos de prueba.
**Técnicas:** Partición de equivalencias, valores límite, casos positivos y negativos, reglas de negocio, testing exploratorio.

| Archivo | Qué es |
|---------|--------|
| [plan-de-pruebas-clientes.pdf](./plan-de-pruebas-clientes.pdf) | Plan de pruebas con los casos y sus datos de prueba |
| [matriz-casos-clientes.pdf](./matriz-casos-clientes.pdf) | Casos de prueba con su estado y defecto asociado (también en .xlsx) |
| [reporte-de-defectos-clientes.pdf](./reporte-de-defectos-clientes.pdf) | Defectos y mejora reportados (también en .xlsx) |

> Documentos anonimizados: sin nombres de empresas, personas, código ni endpoints.

## Herramientas
Excel · Herramienta Recortes de Windows · Jira ·SQL· Claude (asistente de IA): consulta y revisión del diseño de casos