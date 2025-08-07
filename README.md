# 🛡️ Asignación de Roles en Microsoft Entra ID

Este documento describe el proceso de asignación de roles administrativos en Microsoft Entra ID, utilizando como ejemplo el usuario **Analista Seguridad**. El objetivo es demostrar cómo se puede otorgar acceso de solo lectura a información sensible sin comprometer la integridad del sistema.

---

## 🎯 Objetivo

Asignar el rol **Lector de seguridad** a un usuario para permitirle visualizar reportes y datos de seguridad en Microsoft Entra ID y Microsoft 365.

---

## 🪜 Pasos realizados

1. Acceder al portal: [entra.microsoft.com](https://entra.microsoft.com)
2. Navegar a: `Identidad > Roles y administradores`
3. Seleccionar el rol: `Lector de seguridad`
4. Asignar el rol al usuario `Analista Seguridad` desde la sección `Usuarios > Roles asignados`
5. Confirmar la asignación con `Revisar y asignar`

---

## 📋 Resultado

| Usuario             | Rol asignado        | Permisos principales                                                                 | Tipo de recurso | Ruta de acceso | Tipo     |
|---------------------|---------------------|----------------------------------------------------------------------------------------|------------------|----------------|----------|
| Analista Seguridad  | Lector de seguridad | Leer información de seguridad y reportes en Entra ID y Microsoft 365                  | Organization     | Directo        | Integrado |

---

## 🔍 Verificación

La asignación se confirmó desde el perfil del usuario, en la sección `Roles asignados`. El acceso es directo e integrado a nivel organizacional.

---

## 💡 Reflexión

Este ejercicio refuerza la importancia de una gestión de permisos precisa en entornos empresariales. En el contexto de proyectos como **EmpleoJusto-AI**, aplicar roles con acceso limitado permite auditar sin comprometer la seguridad, promoviendo transparencia y control.

---

## 📁 Archivos relacionados

- `roles-en-microsoft-entra.html`: Documento visual con el proceso completo.
- `README.md`: Este archivo, como documentación técnica del ejercicio.

---

## ✍️ Autor

**Martha** – En transición hacia ciberseguridad, con enfoque en proyectos de impacto social y documentación técnica.

---

¿Quieres que te ayude a vincular este README a tu portafolio o agregar una sección de badges y tecnologías usadas? También podemos incluir una nota sobre cómo este ejercicio se conecta con tus metas en EmpleoJusto-AI.
