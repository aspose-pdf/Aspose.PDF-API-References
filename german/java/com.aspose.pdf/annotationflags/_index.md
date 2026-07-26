---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Flags Eine Menge binärer Flags, die verschiedene Eigenschaften der Annotation spezifizieren."
type: docs
weight: 90
url: /de/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flags Eine Menge binärer Flags, die verschiedene Eigenschaften der Annotation spezifizieren.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Standardwert. |
| [Hidden](#Hidden) | Wenn gesetzt, wird die Annotation weder angezeigt noch gedruckt und darf nicht mit dem Benutzer interagieren, unabhängig von ihrem Annotationstyp oder davon, ob ein Annotation‑Handler verfügbar ist. In Fällen, in denen der Bildschirmplatz begrenzt ist, kann die Möglichkeit, Annotationen selektiv ein- und auszublenden, in Kombination mit Erscheinungs‑Streams verwendet werden, um ergänzende Popup‑Informationen anzuzeigen, die in ihrer Funktion Online‑Hilfesystemen ähneln. |
| [Invisible](#Invisible) | Wenn gesetzt, wird die Annotation nicht angezeigt, wenn sie nicht zu einem der Standard‑Annotationstypen gehört und kein Annotation‑Handler verfügbar ist. Wenn nicht gesetzt, wird eine solche unbekannte Annotation mithilfe eines Erscheinungs‑Streams angezeigt, der in ihrem Erscheinungs‑Dictionary, falls vorhanden, angegeben ist. |
| [Locked](#Locked) | Wenn gesetzt, darf die Annotation vom Benutzer weder gelöscht noch dürfen ihre Eigenschaften (einschließlich Position und Größe) geändert werden. Dieses Flag schränkt jedoch Änderungen am Inhalt der Annotation, wie den Wert eines Formularfeldes, nicht ein. |
| [LockedContents](#LockedContents) | Wenn gesetzt, darf der Benutzer den Inhalt der Annotation nicht ändern. Dieses Flag schränkt das Löschen der Annotation oder Änderungen anderer Annotationseigenschaften, wie Position und Größe, nicht ein. |
| [NoRotate](#NoRotate) | Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht gedreht, um der Seitenrotation zu entsprechen. Die obere linke Ecke des Annotationsrechtecks bleibt an einer festen Position auf der Seite, unabhängig von der Seitenrotation. |
| [NoView](#NoView) | Wenn gesetzt, wird die Annotation nicht auf dem Bildschirm angezeigt und darf nicht mit dem Benutzer interagieren. Die Annotation kann gedruckt werden (abhängig von der Einstellung des Print‑Flags), sollte jedoch für die Anzeige auf dem Bildschirm und die Benutzerinteraktion als verborgen betrachtet werden. |
| [NoZoom](#NoZoom) | Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht skaliert, um der Vergrößerung der Seite zu entsprechen. Die Position der Annotation auf der Seite (definiert durch die obere linke Ecke ihres Annotationsrechtecks) bleibt fest, unabhängig von der Seitenvergrößerung. |
| [Print](#Print) | Wenn gesetzt, wird die Annotation beim Drucken der Seite gedruckt. Wenn nicht gesetzt, wird die Annotation niemals gedruckt, unabhängig davon, ob sie auf dem Bildschirm angezeigt wird. Dies kann beispielsweise nützlich sein für Annotationen, die interaktive Schaltflächen darstellen, die auf der gedruckten Seite keinen sinnvollen Zweck erfüllen. |
| [ReadOnly](#ReadOnly) | Wenn gesetzt, darf die Annotation nicht mit dem Benutzer interagieren. Die Annotation kann angezeigt oder gedruckt werden (abhängig von den Einstellungen der NoView- und Print-Flags), sollte jedoch nicht auf Mausklicks reagieren oder ihr Aussehen bei Mausbewegungen ändern. Dieses Flag wird bei Widget-Annotationen ignoriert; seine Funktion wird vom ReadOnly-Flag des zugehörigen Formularfelds übernommen. |
| [ToggleNoView](#ToggleNoView) | Wenn gesetzt, wird die Interpretation des NoView-Flags für bestimmte Ereignisse umgekehrt. Ein typischer Anwendungsfall ist eine Annotation, die nur erscheint, wenn der Mauszeiger darüber gehalten wird. |

### Default {#Default}
```
public static final int Default
```

Standardwert.

### Hidden {#Hidden}
```
public static final int Hidden
```

Wenn gesetzt, wird die Annotation weder angezeigt noch gedruckt und darf nicht mit dem Benutzer interagieren, unabhängig von ihrem Annotationstyp oder davon, ob ein Annotation‑Handler verfügbar ist. In Fällen, in denen der Bildschirmplatz begrenzt ist, kann die Möglichkeit, Annotationen selektiv ein- und auszublenden, in Kombination mit Erscheinungs‑Streams verwendet werden, um ergänzende Popup‑Informationen anzuzeigen, die in ihrer Funktion Online‑Hilfesystemen ähneln.

### Invisible {#Invisible}
```
public static final int Invisible
```

Wenn gesetzt, wird die Annotation nicht angezeigt, wenn sie nicht zu einem der Standard‑Annotationstypen gehört und kein Annotation‑Handler verfügbar ist. Wenn nicht gesetzt, wird eine solche unbekannte Annotation mithilfe eines Erscheinungs‑Streams angezeigt, der in ihrem Erscheinungs‑Dictionary, falls vorhanden, angegeben ist.

### Locked {#Locked}
```
public static final int Locked
```

Wenn gesetzt, darf die Annotation vom Benutzer weder gelöscht noch dürfen ihre Eigenschaften (einschließlich Position und Größe) geändert werden. Dieses Flag schränkt jedoch Änderungen am Inhalt der Annotation, wie den Wert eines Formularfeldes, nicht ein.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Wenn gesetzt, darf der Benutzer den Inhalt der Annotation nicht ändern. Dieses Flag schränkt das Löschen der Annotation oder Änderungen anderer Annotationseigenschaften, wie Position und Größe, nicht ein.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht gedreht, um der Seitenrotation zu entsprechen. Die obere linke Ecke des Annotationsrechtecks bleibt an einer festen Position auf der Seite, unabhängig von der Seitenrotation.

### NoView {#NoView}
```
public static final int NoView
```

Wenn gesetzt, wird die Annotation nicht auf dem Bildschirm angezeigt und darf nicht mit dem Benutzer interagieren. Die Annotation kann gedruckt werden (abhängig von der Einstellung des Print‑Flags), sollte jedoch für die Anzeige auf dem Bildschirm und die Benutzerinteraktion als verborgen betrachtet werden.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht skaliert, um der Vergrößerung der Seite zu entsprechen. Die Position der Annotation auf der Seite (definiert durch die obere linke Ecke ihres Annotationsrechtecks) bleibt fest, unabhängig von der Seitenvergrößerung.

### Print {#Print}
```
public static final int Print
```

Wenn gesetzt, wird die Annotation beim Drucken der Seite gedruckt. Wenn nicht gesetzt, wird die Annotation niemals gedruckt, unabhängig davon, ob sie auf dem Bildschirm angezeigt wird. Dies kann beispielsweise nützlich sein für Annotationen, die interaktive Schaltflächen darstellen, die auf der gedruckten Seite keinen sinnvollen Zweck erfüllen.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Wenn gesetzt, darf die Annotation nicht mit dem Benutzer interagieren. Die Annotation kann angezeigt oder gedruckt werden (abhängig von den Einstellungen der NoView- und Print-Flags), sollte jedoch nicht auf Mausklicks reagieren oder ihr Aussehen bei Mausbewegungen ändern. Dieses Flag wird bei Widget-Annotationen ignoriert; seine Funktion wird vom ReadOnly-Flag des zugehörigen Formularfelds übernommen.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Wenn gesetzt, wird die Interpretation des NoView-Flags für bestimmte Ereignisse umgekehrt. Ein typischer Anwendungsfall ist eine Annotation, die nur erscheint, wenn der Mauszeiger darüber gehalten wird.
