---
title: "Aspose::Pdf::Annotations::AnnotationFlags enum"
linktitle: "AnnotationFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AnnotationFlags enum. En uppsättning flaggor som specificerar olika egenskaper hos annotationen i C++."
type: docs
weight: 12100
url: /sv/cpp/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enum


En uppsättning flaggor som specificerar olika egenskaper hos annotationen.

```cpp
enum class AnnotationFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Standardvärde. |
| Invisible | 1 | Om flaggan är satt, visa inte annotationen om den inte tillhör någon av de standardannotationstyperna och ingen annotation‑hanterare är tillgänglig. Om flaggan är avstängd, visa en sådan okänd annotation med hjälp av en appearance stream som specificeras i dess appearance dictionary, om någon finns. |
| Dolt | 2 | Om flaggan är satt, visa eller skriv inte ut annotationen eller låt den interagera med användaren, oavsett dess annotationstyp eller om en annotation‑hanterare är tillgänglig. I situationer där skärmutrymmet är begränsat kan möjligheten att selektivt dölja och visa annotationer användas i kombination med appearance streams för att visa extra popup‑information som fungerar likt onlinesystem för hjälp. |
| Print | 4 | Om flaggan är satt, skriv ut annotationen när sidan skrivs ut. Om flaggan är avstängd, skriv aldrig ut annotationen, oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annotationer som representerar interaktiva push‑knappar, vilka inte har någon meningsfull funktion på den utskrivna sidan. |
| NoZoom | 8 | Om flaggan är satt, skala inte annotationens utseende för att matcha sidans förstoring. Annotationens placering på sidan (definierad av det övre vänstra hörnet av dess annotation‑rektangel) förblir fast, oavsett sidans förstoring. |
| NoRotate | 16 | Om flaggan är satt, rotera inte annotationens utseende för att matcha sidans rotation. Det övre vänstra hörnet av annotation‑rektangeln förblir på en fast plats på sidan, oavsett sidans rotation. |
| NoView | 32 | Om flaggan är satt, visa inte annotationen på skärmen eller låt den interagera med användaren. Annotationen kan skrivas ut (beroende på inställningen av Print‑flaggan) men bör betraktas som dold för skärmvisning och användarinteraktion. |
| ReadOnly | 64 | Om flaggan är satt, tillåt inte annotationen att interagera med användaren. Annotationen kan visas eller skrivas ut (beroende på inställningarna för NoView‑ och Print‑flaggorna) men bör inte svara på musklick eller ändra sitt utseende vid musrörelser. Denna flagga ignoreras för widget‑annotationer; dess funktion tas över av ReadOnly‑flaggan för det associerade formulärfältet. |
| Locked | 128 | Om flaggan är satt, tillåt inte att annotationen tas bort eller att dess egenskaper (inklusive position och storlek) ändras av användaren. Denna flagga begränsar dock inte ändringar av annotationens innehåll, såsom värdet i ett formulärfält. |
| ToggleNoView | 256 | Om flaggan är satt, invertera tolkningen av NoView‑flaggan för vissa händelser. Ett typiskt användningsområde är att ha en annotation som bara visas när muspekaren hålls över den. |
| LockedContents | 512 | Om flaggan är satt, tillåt inte att annotationens innehåll ändras av användaren. Denna flagga begränsar inte borttagning av annotationen eller förändringar av andra annotationsegenskaper, såsom position och storlek. |

## Se även

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
