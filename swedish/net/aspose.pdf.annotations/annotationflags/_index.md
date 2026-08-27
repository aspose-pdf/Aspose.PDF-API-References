---
title: "Enum AnnotationFlags"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.AnnotationFlags enum. En uppsättning flaggor som specificerar olika egenskaper hos annoteringen"
type: docs
weight: 1530
url: /sv/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

En uppsättning flaggor som specificerar olika egenskaper hos annotationen.

```csharp
[Flags]
public enum AnnotationFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Standardvärde. |
| Invisible | `1` | Om flaggan är satt, visa inte annoteringen om den inte tillhör någon av de standardannotationstyperna och ingen annotation handler är tillgänglig. Om flaggan är avstängd, visa en sådan okänd annotation med hjälp av en appearance stream som specificeras i dess appearance dictionary, om någon finns. |
| Hidden | `2` | Om flaggan är satt, visa eller skriv inte ut annoteringen eller tillåt den att interagera med användaren, oavsett dess annotationstyp eller om en annotation handler är tillgänglig. I situationer där skärmutrymmet är begränsat kan möjligheten att selektivt dölja och visa annotationer användas i kombination med appearance streams för att visa extra popup‑information som fungerar liknande online‑hjälpsystem. |
| Print | `4` | Om flaggan är satt, skriv ut annoteringen när sidan skrivs ut. Om flaggan är avstängd, skriv aldrig ut annoteringen, oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annotationer som representerar interaktiva tryckknappar, vilka inte har någon meningsfull funktion på den utskrivna sidan. |
| NoZoom | `8` | Om flaggan är satt, skala inte annoteringens utseende för att matcha sidans förstoring. Annoteringens position på sidan (definierad av det övre vänstra hörnet av dess annotation‑rektangel) förblir fast, oavsett sidans förstoring. |
| NoRotate | `10` | Om flaggan är satt, rotera inte annoteringens utseende för att matcha sidans rotation. Det övre vänstra hörnet av annotation‑rektangeln förblir på en fast plats på sidan, oavsett sidans rotation. |
| NoView | `20` | Om flaggan är satt, visa inte annoteringen på skärmen eller låt den interagera med användaren. Annoteringen kan skrivas ut (beroende på Print‑flaggan) men bör betraktas som dold för skärmvisning och användarinteraktion. |
| ReadOnly | `40` | Om flaggan är satt, tillåt inte annoteringen att interagera med användaren. Annoteringen kan visas eller skrivas ut (beroende på inställningarna för NoView‑ och Print‑flaggorna) men ska inte svara på musklick eller ändra sitt utseende vid musrörelser. Denna flagga ignoreras för widget‑annotationer; dess funktion tas över av ReadOnly‑flaggan för det associerade formulärfältet. |
| Locked | `80` | Om flaggan är satt, tillåt inte att annoteringen tas bort eller att dess egenskaper (inklusive position och storlek) ändras av användaren. Denna flagga begränsar dock inte ändringar av annoteringens innehåll, såsom värdet i ett formulärfält. |
| ToggleNoView | `100` | Om flaggan är satt, invertera tolkningen av NoView‑flaggan för vissa händelser. Ett typiskt användningsområde är en annotation som bara visas när muspekaren hålls över den. |
| LockedContents | `200` | Om flaggan är satt, tillåt inte att annoteringens innehåll ändras av användaren. Denna flagga begränsar inte borttagning av annoteringen eller ändringar av andra annoteringsegenskaper, såsom position och storlek. |

### Se även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


