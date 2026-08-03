---
title: "Klass UnifiedSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.UnifiedSaveOptions-klass. Denna klass representerar sparalternativ för sparande som använder enhetlig konverteringsmetod med enhetlig intern dokumentmodell."
type: docs
weight: 11330
url: /sv/net/aspose.pdf/unifiedsaveoptions/
---
## UnifiedSaveOptions class

Denna klass representerar sparalternativ för sparande som använder en enhetlig konverteringsmetod (med en enhetlig intern dokumentmodell).

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

### Se även

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


