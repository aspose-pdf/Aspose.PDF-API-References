---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar konfigurationsalternativen för sanering av dolda data i ett dokument."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Representerar konfigurationsalternativen för sanering av dolda data i ett dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [all](#all--) | Skapar en ny instans av klassen {@link HiddenDataSanitizationOptions} med alla alternativ inställda för sanering. Detta inkluderar att aktivera borttagning av annotationer, JavaScript, metadata, bilagor, sökindex, privat information, plattläggning av formulär och lager, samtidigt som alternativet att konvertera sidor till bilder inaktiveras. Valfria konfigurationer som {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) eller {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) kan ändras manuellt efter att instansen erhållits, eftersom de inte är aktiva som standard. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Hämtar alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. Konverteringen av sidor till bilder sker efter att huvuddatan har rensats, vilket styrs av andra alternativ. |
| [getFlattenForms](#getFlattenForms--) | Hämtar ett värde som indikerar om formulär i dokumentet ska plattläggas under saneringsprocessen. Plattläggning av formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke‑redigerbara eller ifyllbara. |
| [getFlattenLayers](#getFlattenLayers--) | Hämtar alternativet för att plattlägga lagerna i PDF‑dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lager. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Hämtar alternativet för bildkonvertering av dokumentet. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. |
| [getImageDpi](#getImageDpi--) | Hämtar alternativet för att lösa upp sidbilder under konvertering. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Hämtar ett värde som indikerar om annotationer ska tas bort från dokumentet. När det är aktiverat kommer alla annotationer i dokumentet att tas bort under saneringsprocessen. Redigering av annotationer kommer att tillämpas. |
| [getRemoveAttachments](#getRemoveAttachments--) | Hämtar alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att eventuella bilagor i PDF‑filen elimineras under saneringsprocessen. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Hämtar ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetssårbarheter som införts av inbäddade skript. |
| [getRemoveMetadata](#getRemoveMetadata--) | Hämtar ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadatainformation att tas bort under saneringen. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Hämtar ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privata data för att förbättra dokumentets säkerhet och integritet. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Ställer in alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. Konverteringen av sidor till bilder sker efter att huvuddolda data har rensats, vilket styrs av andra alternativ. |
| [setFlattenForms](#setFlattenForms-boolean-) | Ställer in ett värde som indikerar om formulär i dokumentet ska plattas ut under saneringsprocessen. Att platta ut formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke‑redigerbara eller ifyllbara. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Ställer in alternativet för att platta ut lagren i PDF‑dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lagren. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Ställer in alternativet för dokumentbildkonvertering. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. |
| [setImageDpi](#setImageDpi-int-) | Ställer in alternativet för att lösa upp sidbilder under konverteringen. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Ställer in ett värde som indikerar om annotationer ska tas bort från dokumentet. När det är aktiverat kommer alla annotationer i dokumentet att tas bort under saneringsprocessen. Redigeringsannotationer kommer att tillämpas. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Ställer in alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att alla bilagor i PDF‑filen elimineras under saneringsprocessen. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Ställer in ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetssårbarheter som införts av inbäddade skript. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Ställer in ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadatainformation att tas bort under saneringen. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Ställer in ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privata data för att förbättra dokumentets säkerhet och integritet. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Skapar en ny instans av klassen {@link HiddenDataSanitizationOptions} med alla alternativ inställda för sanering. Detta inkluderar att aktivera borttagning av annotationer, JavaScript, metadata, bilagor, sökindex, privat information, plattläggning av formulär och lager, samtidigt som alternativet att konvertera sidor till bilder inaktiveras. Valfria konfigurationer som {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) eller {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) kan ändras manuellt efter att instansen erhållits, eftersom de inte är aktiva som standard.

**Returns:**
En {@link HiddenDataSanitizationOptions}‑instans med alla saneringsalternativ förkonfigurerade.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Hämtar alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. Konverteringen av sidor till bilder sker efter att huvuddatan har rensats, vilket styrs av andra alternativ.

**Returns:**
alternativet för att konvertera sidor till bilder.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Hämtar ett värde som indikerar om formulär i dokumentet ska plattläggas under saneringsprocessen. Plattläggning av formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke‑redigerbara eller ifyllbara.

**Returns:**
ett värde som indikerar om formulär i dokumentet ska plattas ut under saneringsprocessen.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Hämtar alternativet för att plattlägga lagerna i PDF‑dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lager.

**Returns:**
alternativet för att platta ut lagren i PDF‑dokumentet.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Hämtar alternativet för bildkonvertering av dokumentet. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs.

**Returns:**
alternativet för dokumentbildkonvertering.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Hämtar alternativet för att lösa upp sidbilder under konvertering.

**Returns:**
alternativet för att lösa upp sidbilder under konverteringen.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Hämtar ett värde som indikerar om annotationer ska tas bort från dokumentet. När det är aktiverat kommer alla annotationer i dokumentet att tas bort under saneringsprocessen. Redigering av annotationer kommer att tillämpas.

**Returns:**
ett värde som indikerar om annotationer ska tas bort från dokumentet.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Hämtar alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att eventuella bilagor i PDF‑filen elimineras under saneringsprocessen.

**Returns:**
alternativet för att ta bort alla bifogade filer från dokumentet.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Hämtar ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetssårbarheter som införts av inbäddade skript.

**Returns:**
ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Hämtar ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadatainformation att tas bort under saneringen.

**Returns:**
ett alternativ för att ta bort metadata från dokumentet.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Hämtar ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privata data för att förbättra dokumentets säkerhet och integritet.

**Returns:**
ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Ställer in alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs. Konverteringen av sidor till bilder sker efter att huvuddolda data har rensats, vilket styrs av andra alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | alternativet för att konvertera sidor till bilder. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Ställer in ett värde som indikerar om formulär i dokumentet ska plattas ut under saneringsprocessen. Att platta ut formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke‑redigerbara eller ifyllbara.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ett värde som indikerar om formulär i dokumentet ska plattas ut under saneringsprocessen. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Ställer in alternativet för att platta ut lagren i PDF‑dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lagren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | alternativet för att platta ut lagren i PDF‑dokumentet. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Ställer in alternativet för dokumentbildkonvertering. Alternativet måste aktiveras manuellt när {@code #All()}‑metoden används om det krävs.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Ställer in alternativet för att lösa upp sidbilder under konverteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | alternativet för att lösa upp sidbilder under konverteringen. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Ställer in ett värde som indikerar om annotationer ska tas bort från dokumentet. När det är aktiverat kommer alla annotationer i dokumentet att tas bort under saneringsprocessen. Redigeringsannotationer kommer att tillämpas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ett värde som indikerar om annotationer ska tas bort från dokumentet. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Ställer in alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att alla bilagor i PDF‑filen elimineras under saneringsprocessen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | alternativet för att ta bort alla bifogade filer från dokumentet. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Ställer in ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetssårbarheter som införts av inbäddade skript.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ett värde som indikerar om JavaScript och associerade åtgärder ska tas bort från dokumentet. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Ställer in ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadatainformation att tas bort under saneringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ett alternativ för att ta bort metadata från dokumentet. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Ställer in ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privata data för att förbättra dokumentets säkerhet och integritet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. |
