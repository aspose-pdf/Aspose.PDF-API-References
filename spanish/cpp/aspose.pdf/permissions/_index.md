---
title: "enumeración Aspose::Pdf::Permissions"
linktitle: "Permisos"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "enumeración Aspose::Pdf::Permissions. Esta enumeración representa los permisos del usuario para un pdf en C++."
type: docs
weight: 26000
url: /es/cpp/aspose.pdf/permissions/
---
## Permissions enum


Este enumerado representa los permisos del usuario para un PDF.

```cpp
enum class Permissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PrintDocument | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 2) Imprimir el documento. ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Imprimir el documento (posiblemente no al nivel de mayor calidad, dependiendo de si [PrintingQuality](./) también está establecido). |
| ModifyContent | n/a | Modificar el contenido del documento mediante operaciones distintas a las controladas por [ModifyTextAnnotations](./), [FillForm](./) y 11. |
| ExtractContent | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 2) Copiar o extraer de otro modo texto y gráficos del documento, incluyendo la extracción de texto y gráficos (para apoyar la accesibilidad a usuarios con discapacidades o para otros propósitos). ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a las controladas por [ExtractContentWithDisabilities](./). |
| ModifyTextAnnotations | n/a | Agregar o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si [ModifyContent](./) también está activado, crear o modificar campos de formulario interactivo (incluidos los campos de firma). |
| FillForm | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si [ModifyTextAnnotations](./) está desactivado. |
| ExtractContentWithDisabilities | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Extraer texto y gráficos (para apoyar la accesibilidad a usuarios con discapacidades o para otros propósitos). |
| AssembleDocument | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si [ModifyContent](./) está desactivado. |
| PrintingQuality | n/a | ([Security](../../aspose.pdf.security/) controladores de revisión 3 o superior) Imprimir el documento a una representación a partir de la cual se pueda generar una copia digital fiel del contenido del PDF. Cuando este bit está desactivado (y el bit 3 está activado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
