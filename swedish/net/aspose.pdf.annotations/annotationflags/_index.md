---
title: AnnotationFlags
second_title: Aspose.PDF för .NET API Referens
description: En uppsättning flaggor som anger olika egenskaper hos annoteringen.
type: docs
weight: 110
url: /sv/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

En uppsättning flaggor som anger olika egenskaper hos annoteringen.

```csharp
[Flags]
public enum AnnotationFlags
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Standardvärde. |
| Invisible | `1` | Om angivet, visa inte anteckningen om den inte tillhör någon av standardanteckningstyperna och ingen anteckningshanterare är tillgänglig. Om den är ren, visa en sådan okänd annotation med hjälp av en utseendeström som specificeras av dess utseendeordbok, om någon. |
| Hidden | `2` | Om det är inställt, visa eller skriv inte ut anteckningen eller låt den interagera med användaren, oavsett dess anteckningstyp eller om en anteckningshanterare är tillgänglig. I fall där skärmutrymmet är begränsat, möjligheten att dölja och visa anteckningar selectively kan användas i kombination med utseendeströmmar för att visa extra popup-information liknande funktion som onlinehjälpsystem. |
| Print | `4` | Om inställt, skriv ut annoteringen när sidan skrivs ut. Om den är ren, skriv aldrig ut annoteringen, oavsett om den visas på skärmen. Detta kan till exempel vara användbart för annotations som representerar interaktiva tryckknappar, som inte skulle tjäna något meningsfullt syfte på den utskrivna sidan. |
| NoZoom | `8` | Om det är inställt, skala inte anteckningens utseende för att matcha sidans förstoring. Placeringen av anteckningen på sidan (definieras av det övre vänstra hörnet av dess anteckningsrektangel) förblir fixerad, oavsett sida förstoring. |
| NoRotate | `10` | Om inställt, rotera inte annoteringens utseende för att matcha sidans rotation. Det övre vänstra hörnet av anteckningsrektangeln förblir på en fast plats på sidan, oavsett sidans rotation. |
| NoView | `20` | Om det är inställt, visa inte annoteringen på skärmen eller låt den interagera med användaren. Annoteringen kan skrivas ut (beroende på inställningen av utskriftsflaggan) men bör betraktas som dold för visning på skärmen och användarinteraktion. |
| ReadOnly | `40` | Om inställt, tillåt inte anteckningen att interagera med användaren. Anteckningen kan visas eller skrivas ut (beroende på inställningarna för flaggorna NoView och Print) men bör inte svara på mouse -klick eller ändra dess utseende som svar på musrörelser. Denna flagga ignoreras för widgetannoteringar; dess funktion subsumeras av ReadOnly-flaggan för det associerade formulärfältet. |
| Locked | `80` | Om angivet, tillåt inte att anteckningen tas bort eller att dess egenskaper (inklusive position och storlek) ändras av användaren. Den här flaggan begränsar dock inte ändringar av annoteringens innehåll, såsom värdet på ett formulärfält. |
| ToggleNoView | `100` | Om inställt, invertera tolkningen av NoView-flaggan för vissa händelser. En typisk användning är att ha en anteckning som endast visas när en muspekare hålls över den. |
| LockedContents | `200` | Om angivet, tillåt inte innehållet i anteckningen att ändras av användaren. Denna flagga begränsar inte radering av anteckningen eller ändringar av andra anteckningsegenskaper, såsom position och storlek. |

### Se även

* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
