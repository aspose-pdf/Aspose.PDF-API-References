---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till SVG-format"
type: docs
weight: 4720
url: /sv/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Spara alternativ för export till SVG-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) som är inbäddade i sparad SVG. Strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG:n. Om bearbetning av denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i anpassad kod flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om det inte fanns någon extern anpassad kod. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Anger om utdata ska skapas som ett zip-arkiv. Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se reglerna för namngivning av svg-filer för sidor i ett flersidigt källdokument, som också tillämpas på den zipade uppsättningen av utdatafiler. |
| [isScaleToPixels](#isScaleToPixels--) | Anger om utgångsdokumentet ska skalas från typografiska punkter till pixlar. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla utdata‑SVG‑bilder för sidor (som beskrivs nedan). Om nej, kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n], som definieras av sidnumret, t.ex. om du definierar utdatafilen "C:\\AsposeTests\\output.svg" och utdata innehåller flera svg‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\\AsposeTests\\" och ha namn 'output.svg', 'output_2.svg', 'output_3.svg' osv. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Anger om utdata ska skapas som ett zip-arkiv. Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se reglerna för namngivning av svg-filer för sidor i ett flersidigt källdokument, som också tillämpas på den zipade uppsättningen av utdatafiler. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) som är inbäddade i sparad SVG. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Anger om utgångsdokumentet ska skalas från typografiska punkter till pixlar. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla utdata‑SVG‑bilder för sidor (som beskrivs nedan). Om nej, kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n], som definieras av sidnumret, t.ex. om du definierar utdatafilen "C:\\AsposeTests\\output.svg" och utdata innehåller flera svg‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\\AsposeTests\\" och ha namn 'output.svg', 'output_2.svg', 'output_3.svg' osv. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Konstruktör

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) som är inbäddade i sparad SVG. Strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG:n. Om bearbetning av denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i anpassad kod flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om det inte fanns någon extern anpassad kod.

**Returns:**
EmbeddedImagesSavingStrategy-instans

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Anger om utdata ska skapas som ett zip-arkiv. Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se reglerna för namngivning av svg-filer för sidor i ett flersidigt källdokument, som också tillämpas på den zipade uppsättningen av utdatafiler.

**Returns:**
booleskt värde

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Anger om utgångsdokumentet ska skalas från typografiska punkter till pixlar.

**Returns:**
booleskt värde

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla utdata‑SVG‑bilder för sidor (som beskrivs nedan). Om nej, kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n], som definieras av sidnumret, t.ex. om du definierar utdatafilen "C:\\AsposeTests\\output.svg" och utdata innehåller flera svg‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\\AsposeTests\\" och ha namn 'output.svg', 'output_2.svg', 'output_3.svg' osv.

**Returns:**
booleskt värde

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Anger om utdata ska skapas som ett zip-arkiv. Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se reglerna för namngivning av svg-filer för sidor i ett flersidigt källdokument, som också tillämpas på den zipade uppsättningen av utdatafiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressOutputToZipArchive |  | booleskt värde |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) som är inbäddade i sparad SVG.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Anger om utgångsdokumentet ska skalas från typografiska punkter till pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleToPixels |  | booleskt värde |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla utdata‑SVG‑bilder för sidor (som beskrivs nedan). Om nej, kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n], som definieras av sidnumret, t.ex. om du definierar utdatafilen "C:\\AsposeTests\\output.svg" och utdata innehåller flera svg‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\\AsposeTests\\" och ha namn 'output.svg', 'output_2.svg', 'output_3.svg' osv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | booleskt värde |
