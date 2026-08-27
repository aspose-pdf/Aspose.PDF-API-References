---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse repräsentiert einen Datensatz, der mit dem Speichern externer Ressourcendateien zusammenhängt, das während der Konvertierung von PDF in ein anderes Format (z. B. HTML) auftritt."
type: docs
weight: 4440
url: /de/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Diese Klasse repräsentiert einen Datensatz, der mit dem Speichern externer Ressourcendateien zusammenhängt, das während der Konvertierung von PDF in ein anderes Format (z. B. HTML) auftritt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentStream](#getContentStream--) | Vom Konverter festgelegt. Stellt den Binärinhalt der gespeicherten Datei dar. |
| [getResourceType](#getResourceType--) | Vom Konverter festgelegt. Vorgesehener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |
| [getSupposedFileName](#getSupposedFileName--) | Vom Konverter festgelegt. Vorgesehener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn die vorgeschlagene Datei aus bestimmten Gründen nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters in der üblichen Weise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss (sowohl beim Speichern als auch bei der Benennung der referenzierten Datei). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn die vorgeschlagene Datei aus bestimmten Gründen nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters in der üblichen Weise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss (sowohl beim Speichern als auch bei der Benennung der referenzierten Datei). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Vom Konverter festgelegt. Stellt den Binärinhalt der gespeicherten Datei dar.

**Returns:**
Array von Bytes

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Vom Konverter festgelegt. Vorgesehener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll.

**Returns:**
NodeLevelResourceType-Element @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Vom Konverter festgelegt. Vorgesehener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll.

**Returns:**
String Wert

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn die vorgeschlagene Datei aus bestimmten Gründen nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters in der üblichen Weise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss (sowohl beim Speichern als auch bei der Benennung der referenzierten Datei).

**Returns:**
boolescher Wert

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn die vorgeschlagene Datei aus bestimmten Gründen nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters in der üblichen Weise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss (sowohl beim Speichern als auch bei der Benennung der referenzierten Datei).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| customProcessingCancelled |  | boolescher Wert |
