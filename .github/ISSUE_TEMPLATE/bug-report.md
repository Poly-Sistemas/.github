---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug
assignees: asayesm
type: Bug

---

## 📖 Descripción del Incidente
> **Comportamiento Detectado:** [Describa qué está pasando actualmente]
> **Comportamiento Esperado:** [Describa cómo debería funcionar correctamente]
> **Impacto:** [Bajo / Medio / Crítico - ¿Afecta la operación del Colegio Médico?]

---

## 🛠️ Análisis de Capas Afectadas (Diagnóstico)

### 🏗️ Base de Datos (SQL Server)
- [ ] **SP/Función:** (Identificar si el error viene de un `pa...` o `fn...`)
- [ ] **Data:** (¿Hay registros inconsistentes o nulos en las tablas?)

### ⚡ API & Backend (Node)
- [ ] **Endpoint/Route:** (Ej: El error se dispara en `GET /inscripciones`)
- [ ] **Logs/Excepción:** (Pegar aquí el error del `try/catch` o la consola)

### 🎨 Frontend (Vue 3)
- [ ] **Componente:** (Ej: El problema está en el modal de `CursosPlan.vue`)
- [ ] **Estado/Consola:** (¿Hay errores 400/500 en el Network del navegador?)

---

## 👣 Pasos para Reproducir
1. Ingresar al sistema con el rol de...
2. Navegar hasta la sección de...
3. Realizar la acción de...
4. **Resultado:** [Describa el error visual o mensaje obtenido]

---

## ✅ Verificación de la Solución (Fix)
*Puntos que deben cumplirse para dar el bug por resuelto:*

- [ ] **Corrección Técnica:** El código ha sido ajustado en la capa correspondiente.
- [ ] **Prueba de Regresión:** El cambio no afecta las inscripciones normales existentes.
- [ ] **Validación de Usuario:** El flujo ahora permite completar la acción sin interrupciones.

---

## 🖼️ Evidencia / Capturas
> [Arrastra aquí capturas del error o logs de Visual Studio]

---
**Prioridad:** 🔴 Alta | 🟡 Media | 🔵 Baja
**Relacionado con:** # (Vincular al Issue del Feature original si aplica)
