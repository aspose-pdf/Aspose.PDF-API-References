---
title: HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF för .NET API Referens
description: Du kan tilldela den här egenskapen anpassad strategi som implementerar processing eller/och sparande av en CSS-del som skapades under konverteringen av PDF till HTML . I sådana fall måste bearbetning som att spara till stream eller disk göras i den anpassade kod
type: docs
weight: 3460
url: /sv/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

Du kan tilldela den här egenskapen anpassad strategi som implementerar processing eller/och sparande av en CSS-del som skapades under konverteringen av PDF till HTML . I sådana fall måste bearbetning (som att spara till stream eller disk) göras i den anpassade kod

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | representerar uppsättning data som kan användas för att spara den medföljande CSS-delen |

### Se även

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->