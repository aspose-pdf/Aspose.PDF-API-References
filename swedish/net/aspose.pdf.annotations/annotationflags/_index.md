---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationFlags enum. En uppsättning flaggor som specificerar olika egenskaper för annotationen
type: docs
weight: 1440
url: /sv/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

En uppsättning flaggor som specificerar olika egenskaper för annotationen.

```csharp
[Flags]
public enum AnnotationFlags
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Standardvärde. |
| Invisible | `1` | Om inställd, visa inte annotationen om den inte tillhör en av de standardiserade annotationstyperna och ingen annotationhanterare är tillgänglig. Om avmarkerad, visa en sådan okänd annotation med hjälp av en utseendeström som specificeras av dess utseendedokument, om någon. |
| Hidden | `2` | Om inställd, visa eller skriv inte ut annotationen eller tillåt den att interagera med användaren, oavsett dess annotationstyp eller om en annotationhanterare är tillgänglig. I fall där skärmutrymmet är begränsat kan möjligheten att dölja och visa annotationer selektivt användas i kombination med utseendeströmmar för att visa hjälpinformation som liknar funktionaliteten hos onlinehjälpsystem. |
| Print | `4` | Om inställd, skriv ut annotationen när sidan skrivs ut. Om avmarkerad, skriv aldrig ut annotationen, oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annotationer som representerar interaktiva knappar, som inte skulle ha något meningsfullt syfte på den utskrivna sidan. |
| NoZoom | `8` | Om inställd, skala inte annotationens utseende för att matcha förstoring av sidan. Platsen för annotationen på sidan (definierad av det övre vänstra hörnet av dess annotationsrektangel) förblir fast, oavsett sidförstoring. |
| NoRotate | `10` | Om inställd, rotera inte annotationens utseende för att matcha rotationen av sidan. Det övre vänstra hörnet av annotationsrektangeln förblir på en fast plats på sidan, oavsett sidrotation. |
| NoView | `20` | Om inställd, visa inte annotationen på skärmen eller tillåt den att interagera med användaren. Annotationen kan skrivas ut (beroende på inställningen av Print-flaggan) men bör betraktas som dold för syften med visning på skärmen och användarinteraktion. |
| ReadOnly | `40` | Om inställd, tillåt inte annotationen att interagera med användaren. Annotationen kan visas eller skrivas ut (beroende på inställningarna för NoView och Print-flaggarna) men bör inte svara på musklik eller ändra sitt utseende som svar på musrörelser. Denna flagga ignoreras för widgetannotationer; dess funktion är underordnad ReadOnly-flaggan för det associerade formulärfältet. |
| Locked | `80` | Om inställd, tillåt inte att annotationen raderas eller dess egenskaper (inklusive position och storlek) ändras av användaren. Denna flagga begränsar dock inte ändringar av annotationens innehåll, såsom värdet av ett formulärfält. |
| ToggleNoView | `100` | Om inställd, invertera tolkningen av NoView-flaggan för vissa händelser. En typisk användning är att ha en annotation som endast visas när en muspekare hålls över den. |
| LockedContents | `200` | Om inställd, tillåt inte att innehållet i annotationen ändras av användaren. Denna flagga begränsar inte radering av annotationen eller ändringar av andra annotationsegenskaper, såsom position och storlek. |

### Se Även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)