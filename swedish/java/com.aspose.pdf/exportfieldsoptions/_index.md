---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar basklass för alternativ för export av formulärfält."
type: docs
weight: 1310
url: /sv/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Representerar basklass för alternativ för export av formulärfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Hämtar eller anger ett värde som indikerar om lösenordsvärdet ska exporteras. Värde: {@code true} om lösenordsvärdet ska exporteras; annars {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Hämtar en delegat som bestämmer om ett specifikt fält ska exporteras. Om delegaten är {@code null} exporteras alla fält (standardbeteendet). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Hämtar eller anger ett värde som indikerar om lösenordsvärdet ska exporteras. Värde: {@code true} om lösenordsvärdet ska exporteras; annars {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Anger en delegat som bestämmer om ett specifikt fält ska exporteras. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Hämtar eller anger ett värde som indikerar om lösenordsvärdet ska exporteras. Värde: {@code true} om lösenordsvärdet ska exporteras; annars {@code false}.

**Returns:**
booleskt värde

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Hämtar en delegat som bestämmer om ett specifikt fält ska exporteras. Om delegaten är {@code null} exporteras alla fält (standardbeteendet).

**Returns:**
en delegat som bestämmer om ett specifikt fält ska exporteras.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Hämtar eller anger ett värde som indikerar om lösenordsvärdet ska exporteras. Värde: {@code true} om lösenordsvärdet ska exporteras; annars {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Anger en delegat som bestämmer om ett specifikt fält ska exporteras.
