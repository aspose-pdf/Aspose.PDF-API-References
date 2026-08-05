---
title: "Permisos"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Este enumerado representa los permisos del usuario para un PDF."
type: docs
weight: 6560
url: /es/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Este enumerado representa los permisos del usuario para un PDF.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| PRINT_DOCUMENT | (Controladores de seguridad de la revisión 2) Imprimir el documento.<br/>            (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento <br/>            (posiblemente no en el nivel de calidad más alto, <br/>            dependiendo de si [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) también está activado). |
| MODIFY_CONTENT | Modificar el contenido del documento mediante operaciones distintas <br/>            de las controladas por  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), y 11. |
| EXTRACT_CONTENT | (Controladores de seguridad de la revisión 2) Copiar o extraer de otro modo <br/>            texto y gráficos del documento, incluyendo la extracción <br/>            de texto y gráficos (para apoyar la accesibilidad a usuarios <br/>            con discapacidades o para otros propósitos).<br/>            (Controladores de seguridad de la revisión 3 o superior) Copiar o extraer de otro modo <br/>            texto y gráficos del documento mediante operaciones <br/>            distintas a las controladas por [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Agregar o modificar anotaciones de texto, completar campos de formulario interactivo, <br/>            y, si [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) también está activado, crear o modificar campos de formulario interactivo <br/>            (incluidos los campos de firma). |
| FILL_FORM | (Controladores de seguridad de la revisión 3 o superior) Completar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) está desactivado. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Controladores de seguridad de la revisión 3 o superior) Extraer texto y <br/>            gráficos (para apoyar la accesibilidad a usuarios con discapacidades <br/>            o para otros propósitos). |
| ASSEMBLE_DOCUMENT | (Controladores de seguridad de la revisión 3 o superior) Ensamblar el documento <br/>            (insertar, rotar o eliminar páginas y crear marcadores o miniaturas <br/>            de imágenes), incluso si [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) está desactivado. |
| PRINTING_QUALITY | (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento a <br/>            una representación a partir de la cual se pueda generar una copia digital fiel del contenido PDF <br/>            . Cuando este bit está desactivado (y el bit 3 está activado), <br/>            la impresión se limita a una representación de bajo nivel de la apariencia, <br/>            posiblemente de calidad degradada. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

