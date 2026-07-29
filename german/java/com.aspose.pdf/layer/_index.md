---
title: "Layer"
linktitle: "Layer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Ebene innerhalb einer PDF‑Seite dar."
type: docs
weight: 2640
url: /de/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Stellt eine Ebene innerhalb einer PDF‑Seite dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der {@code Layer}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [delete](#delete--) | Löscht die aktuelle Ebene aus dem PDF‑Dokument. |
| [flatten](#flatten-boolean-) | Flacht die angegebene Ebene ab. |
| [getContents](#getContents--) | <p> Ruft den Ebeneninhalt ab. </p> |
| [getDefaultState](#getDefaultState--) | Ruft den Standardzustand der PDF‑Ebene ab. |
| [getId](#getId--) | Ruft die Ebenen‑ID ab. |
| [getLocked](#getLocked--) | Ruft einen Wert ab, der angibt, ob die Ebene gesperrt ist. |
| [getName](#getName--) | Ruft den Ebenennamen ab. |
| [lock](#lock--) | Sperrt die Ebene. |
| [save](#save-java.io.OutputStream-) | Speichert die aktuelle Ebene in ein PDF‑Dokument. |
| [save](#save-java.lang.String-) | Speichert die aktuelle Ebene in ein PDF‑Dokument. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Setzt den Standardzustand der PDF‑Ebene. |
| [unlock](#unlock--) | Entsperrt die Ebene. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Initialisiert eine neue Instanz der {@code Layer}-Klasse.

### delete {#delete--}
```
public final void delete()
```

Löscht die aktuelle Ebene aus dem PDF‑Dokument.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Flacht die angegebene Ebene ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cleanupContentStream |  | Gibt an, ob optionale Inhaltsgruppen‑Marker aus dem Inhaltsstrom entfernt werden sollen. Das Setzen des {@code cleanupContentStream}-Parameters auf false beschleunigt den Vorgang des Flattenings. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Ruft den Ebeneninhalt ab. </p>

**Returns:**
{@code List<Operator>} Objekt

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Ruft den Standardzustand der PDF‑Ebene ab.

**Returns:**
der Standardzustand der PDF‑Ebene.

### getId {#getId--}
```
public String getId()
```

Ruft die Ebenen‑ID ab.

**Returns:**
String Wert

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Ruft einen Wert ab, der angibt, ob die Ebene gesperrt ist.

**Returns:**
boolescher Wert

### getName {#getName--}
```
public String getName()
```

Ruft den Ebenennamen ab.

**Returns:**
String Wert

### lock {#lock--}
```
public final void lock()
```

Sperrt die Ebene.

### save {#save-java.io.OutputStream-}
Speichert die aktuelle Ebene in ein PDF‑Dokument.

### save {#save-java.lang.String-}
Speichert die aktuelle Ebene in ein PDF‑Dokument.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Setzt den Standardzustand der PDF‑Ebene.

### unlock {#unlock--}
```
public final void unlock()
```

Entsperrt die Ebene.
