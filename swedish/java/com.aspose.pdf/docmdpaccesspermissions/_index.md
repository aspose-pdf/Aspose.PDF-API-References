---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Aspose.PDF för Java API-referens"
description: "Åtkomstbehörigheterna som beviljas för detta dokument. Giltiga värden är: 1 - Inga ändringar i dokumentet är tillåtna; varje ändring i dokumentet ogiltigförklarar signaturen. 2 -."
type: docs
weight: 1010
url: /sv/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Åtkomstbehörigheterna som beviljas för detta dokument. Giltiga värden är: 1 - Inga ändringar i dokumentet är tillåtna; varje ändring i dokumentet ogiltigförklarar signaturen. 2 - Tillåtna ändringar är ifyllning av formulär, instansiering av sidmallar och signering; andra ändringar ogiltigförklarar signaturen. 3 - Tillåtna ändringar är samma som för 2, samt skapande, borttagning och modifiering av annotationer; andra ändringar ogiltigförklarar signaturen.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Tillåtna ändringar är samma som för 2, samt skapande, borttagning och modifiering av annotationer; andra ändringar ogiltigförklarar signaturen. |
| [FillingInForms](#FillingInForms) | 2 - Tillåtna ändringar är ifyllning av formulär, instansiering av sidmallar och signering; andra ändringar ogiltigförklarar signaturen. |
| [NoChanges](#NoChanges) | 1 - Inga ändringar i dokumentet är tillåtna; varje ändring i dokumentet ogiltigförklarar signaturen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Tillåtna ändringar är samma som för 2, samt skapande, borttagning och modifiering av annotationer; andra ändringar ogiltigförklarar signaturen.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Tillåtna ändringar är ifyllning av formulär, instansiering av sidmallar och signering; andra ändringar ogiltigförklarar signaturen.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Inga ändringar i dokumentet är tillåtna; varje ändring i dokumentet ogiltigförklarar signaturen.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
