# Guía 3.1. Integridad referencial, restricciones — Mapeo de herencia

**UTN - FRP - TUP - Programación aplicada 2025 - Acceso a datos - SQL Server**

[Home](https://docs.google.com/document/d/1fU7NQupaFc95iPifZDb__KNbMF07a2dEiJU1Emimv0g/preview) / [Aplicada 2025](https://docs.google.com/document/d/1ud7dv9qWv0ZHfpYGd17nKr_CpRopx7juKsI_9Bh1hsA/preview)

- **fork**: <https://github.com/UTN-FRP-TUP-Aplicada-2025/tup_aplicada_2025_guia3.1>
- **sol**: <https://github.com/fernandofilipuzzi-dev/tup_aplicada_2025_guia3.1>

---

## Índice

- **[Ejercicio 1. Curso-Alumno. Agregación](#ejercicio-1-curso-alumno-agregación)**
- **[Nota de la exportación](#nota-de-la-exportación)**

---

## Ejercicio 1. Curso-Alumno. Agregación

Si se tiene el siguiente modelo de datos

![Diagrama UML: clase Curso con Id:int y Nombre:string, relacionada por agregación —rombo blanco del lado de Curso— con la clase Alumno, que tiene Id:int y Nombre:string. El extremo del lado de Alumno lleva multiplicidad *, el rol -cursos y la etiqueta Cursan](Imagenes/fig-1-1-modelo-de-datos.png)

*Figura 1.1. Modelo de datos del dominio.*

---

Filipuzzi, Fernando -

---

## Nota de la exportación

*Esta sección no pertenece al documento original.*

### Cómo se hizo

| Paso | Cómo |
| --- | --- |
| Origen | [`Guia3.1.docx`](https://docs.google.com/document/d/1XjNqOeTfhhNEBd-yQbdXIK6jcKLvCzlj/edit), exportado el 2026-09-05 |
| Texto | Exportación a `.docx` y lectura del `word/document.xml`, cotejada con la lectura por el conector de Drive |
| Imágenes | Extraídas de `word/media/` — son los archivos originales, no capturas |
| Índice | Recreado con enlace interno; el original tenía número de página |

### Cuál es el documento de origen

**El prompt `02-Guia3.1.md` apunta a `1Wjnpf8ePnEhgrUPCFvDrfDwI5O7qO7E6`, que es la Guía 2.1** —el mismo identificador que ya arrastraban los prompts del Tema 2—. Se exportó en cambio el documento que sí es la Guía 3.1:

| Comprobación | Resultado |
| --- | --- |
| Identificador exportado | `1XjNqOeTfhhNEBd-yQbdXIK6jcKLvCzlj` |
| Título del archivo en Drive | `Guia3.1.docx` |
| Título dentro del documento | «*Guía 3.1. Integridad referencial restricciones - **Mapeo de herencia***» |
| Dónde vive | En la subcarpeta `nc/` de la carpeta del Tema 3 de Aplicada, junto al apunte «Integridad y restricciones. herencia.docx» |
| Repositorios que declara | `tup_aplicada_2025_guia3.1`, propios de esta guía |

### El documento está apenas empezado

**Lo que hay es todo lo que hay:** el encabezado, los dos repositorios, un índice de una sola entrada y un ejercicio con su figura. **No hay enunciado, ni actividades, ni tablas de datos.** Los tres ejercicios de la Guía 2.1 no tienen equivalente acá.

Y hay dos cosas que conviene tener presentes antes de continuarlo:

1. **La Figura 1.1 es la misma imagen que la Figura 1.1 de la Guía 2.1** — verificado por su huella: `md5 b11dcb08f20b36c54cf7b6c6dcf35cae` en los dos archivos. Es el modelo de **agregación** `Curso` ◇— `Alumno`, con rombo blanco.
2. **Por eso el título del ejercicio dice «Agregación»**, y no herencia. El encabezado del documento anuncia mapeo de herencia; el único ejercicio que tiene es el de agregación del tema anterior, copiado.

**No se completó nada.** Un ejercicio inventado no sería una exportación.

### El año

El encabezado dice «Programación aplicada **2025**» y los repositorios son `…-2025-…`, mientras que el resto del material del curso es de 2026. Se transcribió como está.
