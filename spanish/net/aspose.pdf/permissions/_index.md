---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Enum de Aspose.Pdf.Permissions. Este enum representa los permisos de los usuarios para un pdf
type: docs
weight: 8480
url: /es/net/aspose.pdf/permissions/
---
## Enumeración de permisos

Este enum representa los permisos del usuario para un pdf.

```csharp
[Flags]
public enum Permissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PrintDocument | `4` | (Controladores de seguridad de la revisión 2) Imprimir el documento. (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento (posiblemente no en el nivel de calidad más alto, dependiendo de si PrintingQuality también está configurado). |
| ModifyContent | `8` | Modificar el contenido del documento mediante operaciones distintas de las controladas por ModifyTextAnnotations, FillForm y 11. |
| ExtractContent | `10` | (Controladores de seguridad de la revisión 2) Copiar o extraer de otro modo texto y gráficos del documento, incluyendo la extracción de texto y gráficos (en apoyo a la accesibilidad para usuarios con discapacidades u otros propósitos). (Controladores de seguridad de la revisión 3 o superior) Copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas de las controladas por ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Agregar o modificar anotaciones de texto, completar campos de formularios interactivos y, si ModifyContent también está configurado, crear o modificar campos de formularios interactivos (incluidos los campos de firma). |
| FillForm | `100` | (Controladores de seguridad de la revisión 3 o superior) Completar campos de formularios interactivos existentes (incluidos los campos de firma), incluso si ModifyTextAnnotations está claro. |
| ExtractContentWithDisabilities | `200` | (Controladores de seguridad de la revisión 3 o superior) Extraer texto y gráficos (en apoyo a la accesibilidad para usuarios con discapacidades u otros propósitos). |
| AssembleDocument | `400` | (Controladores de seguridad de la revisión 3 o superior) Ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si ModifyContent está claro. |
| PrintingQuality | `800` | (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento en una representación de la cual se podría generar una copia digital fiel del contenido PDF. Cuando este bit está claro (y el bit 3 está configurado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)