---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: Propiedad HtmlSaveOptions. Con esta propiedad puedes definir explícitamente qué páginas del documento deben ser convertidas. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de las páginas deben tomarse del rango 1...NumberOfPagesInConvertedDocument. El orden de aparición de las páginas en esta lista no afecta su orden en las páginas HTML resultantes; en las páginas resultantes siempre irán en el orden en que están presentes en el PDF de origen. Si esta lista es nula, como es por defecto, todas las páginas serán convertidas. Si algún número de página de esta lista sale del rango de las páginas presentes (1-[amountOfPagesInDocument]), se lanzará una excepción.
type: docs
weight: 70
url: /es/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## Propiedad HtmlSaveOptions.ExplicitListOfSavedPages

Con esta propiedad puedes definir explícitamente qué páginas del documento deben ser convertidas. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de las páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre irán en el orden en que están presentes en el PDF de origen. Si esta lista es nula (como es por defecto), todas las páginas serán convertidas. Si algún número de página de esta lista sale del rango de las páginas presentes (1-[amountOfPagesInDocument]), se lanzará una excepción.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Ver También

* clase [HtmlSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)