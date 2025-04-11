---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ToUnicodeProcessingRules. Esta clase describe reglas que se pueden utilizar para resolver el error de Adobe Preflight "El texto no se puede mapear a Unicode"
type: docs
weight: 11110
url: /es/net/aspose.pdf/tounicodeprocessingrules/
---
## Clase ToUnicodeProcessingRules

Esta clase describe reglas que se pueden utilizar para resolver el error de Adobe Preflight "El texto no se puede mapear a Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Inicializa una nueva instancia de la clase `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Inicializa una nueva instancia de la clase `ToUnicodeProcessingRules` con la opción especificada para eliminar espacios de los nombres de CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Inicializa una nueva instancia de la clase `ToUnicodeProcessingRules` con opciones especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información provoca un error "El texto no se puede mapear a Unicode". Utilice esta bandera para mapear símbolos no vinculados en unicode "espacio" (código 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían provocar errores con el mapeo de texto unicode. Esta bandera ordena eliminar espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto falso. |

### Véase también

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)