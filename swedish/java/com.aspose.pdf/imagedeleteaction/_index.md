---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Aspose.PDF för Java API-referens"
description: "Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort"
type: docs
weight: 2290
url: /sv/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Check](#Check) | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort endast om det inte finns några andra referenser till bilden från andra sidor. Detta kan kräva mer tid jämfört med ForceDelete alternativ. |
| [ForceDelete](#ForceDelete) | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser till samma objekt finns kan dokumentet bli korrupt. |
| [KeepContents](#KeepContents) | Bilden kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. Dokumentet kan bli ogiltigt. |
| [None](#None) | Bilden kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas. |

### Check {#Check}
```
public static final int Check
```

Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort endast om det inte finns några andra referenser till bilden från andra sidor. Detta kan kräva mer tid jämfört med ForceDelete alternativ.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser till samma objekt finns kan dokumentet bli korrupt.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

Bilden kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. Dokumentet kan bli ogiltigt.

### None {#None}
```
public static final int None
```

Bilden kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas.
