---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptions klass. SaveOptions-typ håller en nivå av abstraktion på individuella spara alternativ
type: docs
weight: 9870
url: /sv/net/aspose.pdf/saveoptions/
---
## SaveOptions klass

SaveOptions-typ håller en nivå av abstraktion på individuella spara alternativ

```csharp
public abstract class SaveOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om teckensnittsglypher kommer att cachas medan aps-sidor förbereds. Förbättrar prestandan vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om Response-objektet kommer att stängas efter att dokumentet har sparats i svaret. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)