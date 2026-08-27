---
title: "AnnotationFlags"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "En uppsättning flaggor som specificerar olika egenskaper hos annotationen."
type: docs
weight: 930
url: /sv/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

En uppsättning flaggor som specificerar olika egenskaper hos annotationen.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| DEFAULT | Standardvärde. |
| INVISIBLE | Om satt, visa inte annoteringen om den inte tillhör någon av de standardannoteringstyperna<br/>            och ingen annoteringshanterare är tillgänglig. Om avmarkerad, visa en sådan okänd annotering<br/>            med ett utseendeström som anges i dess utseendedictionary, om någon. |
| HIDDEN | Om den är aktiverad, visa eller skriv inte ut annoteringen eller tillåt den att interagera med användaren,<br/>            oavsett dess annoteringstyp eller om en annoteringshanterare är tillgänglig.<br/>            I fall där skärmutrymmet är begränsat kan möjligheten att dölja och visa annoteringar selektivt<br/>            användas i kombination med utseendeströmmar för att visa extra popup‑information<br/>            som fungerar liknande online‑hjälpsystem. |
| PRINT | Om den är aktiverad, skriv ut annoteringen när sidan skrivs ut. Om den är avstängd, skriv aldrig ut annoteringen,<br/>            oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annoteringar<br/>            som representerar interaktiva tryckknappar, vilka inte skulle ha någon meningsfull funktion på den utskrivna sidan. |
| NO_ZOOM | Om den är aktiverad, skala inte annoteringens utseende för att matcha sidans förstoring.<br/>            Annoteringens placering på sidan (definierad av det övre vänstra hörnet av dess annoteringsrektangel)<br/>            förblir fast, oavsett sidans förstoring. |
| NO_ROTATE | Om den är aktiverad, rotera inte annoteringens utseende för att matcha sidans rotation.<br/>            Det övre vänstra hörnet av annoteringsrektangeln förblir på en fast plats på sidan,<br/>            oavsett sidans rotation. |
| NO_VIEW | Om den är aktiverad, visa inte annoteringen på skärmen eller tillåt den att interagera med användaren.<br/>            Annoteringen kan skrivas ut (beroende på inställningen för Print‑flaggan)<br/>            men bör betraktas som dold för skärmvisning och användarinteraktion. |
| READ_ONLY | Om den är aktiverad, tillåt inte annoteringen att interagera med användaren. Annoteringen kan visas<br/>            eller skrivas ut (beroende på inställningarna för NoView‑ och Print‑flaggorna) men bör inte svara på mus‑klick eller ändra sitt utseende som svar på musrörelser. Denna flagga ignoreras för widget‑annoteringar;<br/>            dess funktion tas över av ReadOnly‑flaggan för det associerade formulärfältet. |
| LOCKED | Om den är aktiverad, tillåt inte att annoteringen tas bort eller att dess egenskaper (inklusive position och storlek)<br/>            ändras av användaren. Denna flagga begränsar dock inte ändringar av annoteringens innehåll,<br/>            såsom värdet i ett formulärfält. |
| TOGGLE_NO_VIEW | Om den är aktiverad, invertera tolkningen av NoView‑flaggan för vissa händelser.<br/>            En typisk användning är att ha en annotering som bara visas när muspekaren hålls över den. |
| LOCKED_CONTENTS | Om den är aktiverad, tillåt inte att innehållet i annoteringen ändras av användaren.<br/>            Denna flagga begränsar inte borttagning av annoteringen eller ändringar av andra annoteringsegenskaper,<br/>            såsom position och storlek. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

