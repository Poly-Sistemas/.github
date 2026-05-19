---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: enhancement
assignees: asayesm
type: Feature

---

## 📖 Descripción del Requerimiento
> **Como** [Actor / Rol]
> **Quiero** [Acción que realiza el sistema]
> **Para** [Beneficio o valor de negocio]

---

## 🛠️ Especificaciones Técnicas

### 🏗️ Base de Datos
- [ ] **Tablas/Campos:** (Ej: Agregar `Email` a la tabla `Persona`)
- [ ] **Store Procedures:** (Ej: Actualizar `sp_Persona_Insertar`)

### ⚡ API & Backend
- [ ] **Endpoints:** (Ej: `POST /api/socios/registrar`)
- [ ] **Lógica de Negocio:** (Ej: Validar que el socio no sea "Renuente a pago")

### 🎨 Frontend
- [ ] **Componentes:** (Ej: Crear `FormularioInscripcion.vue`)
- [ ] **Validaciones:** (Ej: Máscara para DNI y formato de correo)

---

## ✅ Criterios de Aceptación (Escenarios)
*Estos puntos definen cuándo la tarea está terminada y funciona bien.*

- [ ] **Escenario Exitoso:** Al registrar un socio "Pagador", se genera la ficha y se guarda en la DB.
- [ ] **Escenario Error:** Si el Jefe de Atención al Cliente no aprueba, el sistema genera el documento de rechazo.
- [ ] **Validación:** Si el DNI ya existe, el sistema muestra un mensaje de advertencia.

---

## 🖼️ UI / Prototipo
> [Arrastra aquí tu captura de pantalla o mockup]

---
**Vinculado a:** # (ID de Issue relacionado si existe)
