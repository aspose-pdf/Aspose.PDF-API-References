---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Aspose.PDF för Java API-referens"
description: "Flaggor En uppsättning binära flaggor som specificerar olika egenskaper hos annoteringen."
type: docs
weight: 90
url: /sv/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flaggor En uppsättning binära flaggor som specificerar olika egenskaper hos annoteringen.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Default](#Default) | Standardvärde. |
| [Hidden](#Hidden) | Om flaggan är satt, visa inte eller skriv inte ut annoteringen och tillåt inte att den interagerar med användaren, oavsett dess annoteringstyp eller om en annoteringshanterare är tillgänglig. I situationer där skärmutrymmet är begränsat kan möjligheten att selektivt dölja och visa annoteringar användas i kombination med utseendeströmmar för att visa extra popup‑information som fungerar på liknande sätt som onlinhjälpsystem. |
| [Invisible](#Invisible) | Om flaggan är satt, visa inte annoteringen om den inte tillhör någon av de standardannoteringstyperna och ingen annoteringshanterare är tillgänglig. Om flaggan är avstängd, visa en sådan okänd annotering med en utseendeström som anges i dess utseendedictionary, om sådan finns. |
| [Locked](#Locked) | Om flaggan är satt, tillåt inte att annoteringen tas bort eller att dess egenskaper (inklusive position och storlek) ändras av användaren. Denna flagga begränsar dock inte ändringar av annoteringens innehåll, såsom värdet i ett formulärfält. |
| [LockedContents](#LockedContents) | Om flaggan är satt, tillåt inte att annoteringens innehåll ändras av användaren. Denna flagga begränsar inte borttagning av annoteringen eller förändringar av andra annoteringsegenskaper, såsom position och storlek. |
| [NoRotate](#NoRotate) | Om flaggan är satt, rotera inte annoteringens utseende för att matcha sidans rotation. Det övre vänstra hörnet av annoteringsrektangeln förblir på en fast plats på sidan, oavsett sidrotation. |
| [NoView](#NoView) | Om flaggan är satt, visa inte annoteringen på skärmen eller låt den interagera med användaren. Annoteringen kan skrivas ut (beroende på inställningen för Print‑flaggan) men bör betraktas som dold för skärmvisning och användarinteraktion. |
| [NoZoom](#NoZoom) | Om flaggan är satt, skala inte annoteringens utseende för att matcha sidans förstoring. Annoteringens position på sidan (definierad av det övre vänstra hörnet av dess annoteringsrektangel) förblir fast, oavsett sidans förstoring. |
| [Print](#Print) | Om flaggan är satt, skriv ut annoteringen när sidan skrivs ut. Om flaggan är avstängd, skriv aldrig ut annoteringen, oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annoteringar som representerar interaktiva tryckknappar, vilka inte har någon meningsfull funktion på den utskrivna sidan. |
| [ReadOnly](#ReadOnly) | Om flaggan är satt, tillåt inte att annoteringen interagerar med användaren. Annoteringen kan visas eller skrivas ut (beroende på inställningarna för NoView‑ och Print‑flaggorna) men ska inte svara på musklick eller ändra sitt utseende vid musrörelser. Denna flagga ignoreras för widget‑annoteringar; dess funktion tas över av ReadOnly‑flaggan för det associerade formulärfältet. |
| [ToggleNoView](#ToggleNoView) | Om flaggan är satt, invertera tolkningen av NoView‑flaggan för vissa händelser. Ett typiskt användningsområde är en annotering som bara visas när muspekaren hålls över den. |

### Default {#Default}
```
public static final int Default
```

Standardvärde.

### Hidden {#Hidden}
```
public static final int Hidden
```

Om flaggan är satt, visa inte eller skriv inte ut annoteringen och tillåt inte att den interagerar med användaren, oavsett dess annoteringstyp eller om en annoteringshanterare är tillgänglig. I situationer där skärmutrymmet är begränsat kan möjligheten att selektivt dölja och visa annoteringar användas i kombination med utseendeströmmar för att visa extra popup‑information som fungerar på liknande sätt som onlinhjälpsystem.

### Invisible {#Invisible}
```
public static final int Invisible
```

Om flaggan är satt, visa inte annoteringen om den inte tillhör någon av de standardannoteringstyperna och ingen annoteringshanterare är tillgänglig. Om flaggan är avstängd, visa en sådan okänd annotering med en utseendeström som anges i dess utseendedictionary, om sådan finns.

### Locked {#Locked}
```
public static final int Locked
```

Om flaggan är satt, tillåt inte att annoteringen tas bort eller att dess egenskaper (inklusive position och storlek) ändras av användaren. Denna flagga begränsar dock inte ändringar av annoteringens innehåll, såsom värdet i ett formulärfält.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Om flaggan är satt, tillåt inte att annoteringens innehåll ändras av användaren. Denna flagga begränsar inte borttagning av annoteringen eller förändringar av andra annoteringsegenskaper, såsom position och storlek.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Om flaggan är satt, rotera inte annoteringens utseende för att matcha sidans rotation. Det övre vänstra hörnet av annoteringsrektangeln förblir på en fast plats på sidan, oavsett sidrotation.

### NoView {#NoView}
```
public static final int NoView
```

Om flaggan är satt, visa inte annoteringen på skärmen eller låt den interagera med användaren. Annoteringen kan skrivas ut (beroende på inställningen för Print‑flaggan) men bör betraktas som dold för skärmvisning och användarinteraktion.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Om flaggan är satt, skala inte annoteringens utseende för att matcha sidans förstoring. Annoteringens position på sidan (definierad av det övre vänstra hörnet av dess annoteringsrektangel) förblir fast, oavsett sidans förstoring.

### Print {#Print}
```
public static final int Print
```

Om flaggan är satt, skriv ut annoteringen när sidan skrivs ut. Om flaggan är avstängd, skriv aldrig ut annoteringen, oavsett om den visas på skärmen. Detta kan vara användbart, till exempel för annoteringar som representerar interaktiva tryckknappar, vilka inte har någon meningsfull funktion på den utskrivna sidan.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Om flaggan är satt, tillåt inte att annoteringen interagerar med användaren. Annoteringen kan visas eller skrivas ut (beroende på inställningarna för NoView‑ och Print‑flaggorna) men ska inte svara på musklick eller ändra sitt utseende vid musrörelser. Denna flagga ignoreras för widget‑annoteringar; dess funktion tas över av ReadOnly‑flaggan för det associerade formulärfältet.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Om flaggan är satt, invertera tolkningen av NoView‑flaggan för vissa händelser. Ett typiskt användningsområde är en annotering som bara visas när muspekaren hålls över den.
