# Pinturería UTN - Parcial Programación III

## Objetivo
Desarrollar una aplicación web con **HTML, CSS, JavaScript y Bootstrap 5** que permita gestionar un inventario de pinturas conectándose a la **API REST** provista por la cátedra.  
El proyecto cumple con todas las partes del examen: CRUD completo, validaciones, filtros, estadísticas y modo oscuro.

---

## Cómo ejecutar el proyecto
1. Descargar la carpeta completa del proyecto (manteniendo la estructura original).  
2. Abrir el archivo **`pintureria.html`** en un navegador.  
3. Asegurarse de tener conexión a Internet (la API se aloja en Render).  
4. Interactuar con las tres pestañas principales del sitio: **Alta**, **Listado** y **Estadísticas**.

---

## Funcionalidades desarrolladas

### Parte 1 – Listado y Alta
- Carga de pinturas desde la API (`GET /pinturas`).
- Alta de nuevas pinturas (`POST /pinturas`).
- Formulario validado con Bootstrap y JavaScript.

### Parte 2 – Modificación y Eliminación
- Seleccionar pintura para editar (`PUT /pinturas/:id`).
- Eliminar con confirmación (`DELETE /pinturas/:id`).

### Parte 3 – Validaciones
- Validaciones HTML5 + JS:  
  - Precio entre **50 y 5000**  
  - Cantidad entre **1 y 400**  
  - Campos obligatorios con feedback visual (`is-valid`, `is-invalid`).

### Parte 4 – UX mejorado y Filtros
- Spinner Bootstrap al cargar datos.  
- Botones para **promedio de precios**, **filtro por marca** y **exportar a CSV**.  
- Limpieza automática del formulario tras agregar o modificar.

### Parte 5 – Diseño y Navegación
- Interfaz moderna, responsive y profesional con **Bootstrap 5**.  
- Navbar fija con logo UTN y sistema de **tabs** (Alta / Listado / Estadísticas).  
- Modo oscuro/claro persistente con `localStorage`.

### Parte 6 – Estadísticas
- Cálculo de métricas básicas:
  - Total de pinturas  
  - Marca más común  
  - Pintura más cara  
  - Promedio general de precios  
- Exportación del listado a **CSV**.

---

## Consignas resueltas por parte

| Parte | Descripción | Estado |
|--------|--------------|--------|
| 1 | Listado inicial y alta básica | ✅ |
| 2 | Modificar y eliminar | ✅ |
| 3 | Validaciones | ✅ |
| 4 | UX mejorado, filtros y promedio | ✅ |
| 5 | Diseño moderno y tabs | ✅ |
| 6 | Estadísticas, CSV y modo oscuro | ✅ |

---

**Alumno:** [Facundo Martin Farias]  
**Materia:** Programación III  
**Año:** 2025  
**Institución:** UTN - Facultad Regional Avellaneda
