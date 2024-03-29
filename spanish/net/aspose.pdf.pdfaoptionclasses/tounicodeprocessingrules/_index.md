---
title: ToUnicodeProcessingRules
second_title: Referencia de API de Aspose.PDF para .NET
description: Esta clase describe las reglas que se pueden usar para resolver el error de Adobe Preflight El texto no se puede asignar a Unicode.
type: docs
weight: 5970
url: /es/net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Esta clase describe las reglas que se pueden usar para resolver el error de Adobe Preflight "El texto no se puede asignar a Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules#constructor)() | Constructor |
| [ToUnicodeProcessingRules](tounicodeprocessingrules#constructor_1)(bool) | Constructor |
| [ToUnicodeProcessingRules](tounicodeprocessingrules#constructor_2)(bool, bool) | Constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/mapnonlinkedsymbolsonspace) { get; set; } | Algunas fuentes no proporcionan información sobre códigos Unicode para algunos símbolos de texto. Esta falta de información genera un error "El texto no se puede asignar a Unicode". Use esta bandera para asignar símbolos no vinculados en el "espacio" Unicode (código 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/removespacesfromcmapnames) { get; set; } | Algunas fuentes tienen mapas de código de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían llamar a errors con asignación de texto Unicode. Esta bandera ordena eliminar los espacios de los nombres de los mapas de código de caracteres ToUnicode. De forma predeterminada, false. |

### Ver también

* espacio de nombres [Aspose.Pdf.PdfAOptionClasses](../../aspose.pdf.pdfaoptionclasses)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
