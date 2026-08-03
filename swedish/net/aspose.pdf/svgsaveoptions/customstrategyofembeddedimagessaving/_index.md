---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Aspose.PDF för .NET API‑referens"
description: "SvgSaveOptions-fält. Detta fält kan innehålla en sparstrategi som måste användas om den är närvarande under konvertering för anpassad hantering av skapade refererade externa bildfiler, såsom inbäddad BMP eller JPEG i den sparade SVG:n. Strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG:n. Om bearbetning av denna eller den där filen av någon anledning måste utföras av konverterarens kod själv och inte i anpassad kod, ange i anpassad kod flaggan CustomProcessingCancelled i variabeln imageSavingInfo-parametrar. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om ingen extern anpassad kod fanns."
type: docs
weight: 30
url: /sv/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (t.ex. inbäddade BMP‑ eller JPEG‑filer) som bäddas in i den sparade SVG‑filen. Strategin måste bearbeta resurser och returnera en sträng som representerar den önskade URI:n för den sparade resursen i den genererade SVG‑filen. Om bearbetning av denna eller den där filen av någon anledning måste utföras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo'-parameter. Detta signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Se även

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


