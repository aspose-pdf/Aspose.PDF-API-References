---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions-fält. Detta fält kan innehålla en sparstrategi som måste användas om den finns under konvertering för anpassad hantering av skapade refererade externa bildfiler som inbäddade BMP eller JPEG inbäddade i den sparade SVG. Den strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen ställ in i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo'. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod.
type: docs
weight: 30
url: /sv/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving-fält

Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) inbäddade i den sparade SVG. Den strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen ställ in i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo'. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Se Även

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)