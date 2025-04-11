---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationFlags-Enum. Eine Menge von Flags, die verschiedene Eigenschaften der Annotation spezifizieren
type: docs
weight: 1440
url: /de/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags-Enumeration

Eine Menge von Flags, die verschiedene Eigenschaften der Annotation spezifizieren.

```csharp
[Flags]
public enum AnnotationFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | `0` | Standardwert. |
| Invisible | `1` | Wenn gesetzt, die Annotation nicht anzeigen, wenn sie nicht zu einem der Standard-Annotationstypen gehört und kein Annotation-Handler verfügbar ist. Wenn gelöscht, eine solche unbekannte Annotation mit einem Erscheinungsstrom anzeigen, der durch ihr Erscheinungsdokument angegeben ist, falls vorhanden. |
| Hidden | `2` | Wenn gesetzt, die Annotation nicht anzeigen oder drucken oder ihre Interaktion mit dem Benutzer erlauben, unabhängig von ihrem Annotationstyp oder ob ein Annotation-Handler verfügbar ist. In Fällen, in denen der Bildschirmplatz begrenzt ist, kann die Fähigkeit, Annotationen selektiv zu verstecken und anzuzeigen, in Kombination mit Erscheinungsströmen verwendet werden, um Hilfsinformationen anzuzeigen, die in ihrer Funktion Online-Hilfesystemen ähnlich sind. |
| Print | `4` | Wenn gesetzt, die Annotation drucken, wenn die Seite gedruckt wird. Wenn gelöscht, die Annotation niemals drucken, unabhängig davon, ob sie auf dem Bildschirm angezeigt wird. Dies kann nützlich sein, zum Beispiel für Annotationen, die interaktive Drucktasten darstellen, die auf der gedruckten Seite keinen sinnvollen Zweck erfüllen würden. |
| NoZoom | `8` | Wenn gesetzt, das Erscheinungsbild der Annotation nicht skalieren, um der Vergrößerung der Seite zu entsprechen. Der Standort der Annotation auf der Seite (definiert durch die obere linke Ecke ihres Annotationsrechtecks) bleibt fix, unabhängig von der Seitenvergrößerung. |
| NoRotate | `10` | Wenn gesetzt, das Erscheinungsbild der Annotation nicht drehen, um der Drehung der Seite zu entsprechen. Die obere linke Ecke des Annotationsrechtecks bleibt an einem festen Ort auf der Seite, unabhängig von der Seitenrotation. |
| NoView | `20` | Wenn gesetzt, die Annotation nicht auf dem Bildschirm anzeigen oder ihre Interaktion mit dem Benutzer erlauben. Die Annotation kann gedruckt werden (abhängig von der Einstellung des Print-Flags), sollte jedoch für die Anzeige auf dem Bildschirm und die Benutzerinteraktion als verborgen betrachtet werden. |
| ReadOnly | `40` | Wenn gesetzt, die Interaktion der Annotation mit dem Benutzer nicht erlauben. Die Annotation kann angezeigt oder gedruckt werden (abhängig von den Einstellungen der NoView- und Print-Flags), sollte jedoch nicht auf Mausklicks reagieren oder ihr Erscheinungsbild als Reaktion auf Mausbewegungen ändern. Dieses Flag wird für Widget-Annotationen ignoriert; seine Funktion wird durch das ReadOnly-Flag des zugehörigen Formularfelds subsumiert. |
| Locked | `80` | Wenn gesetzt, die Annotation nicht löschen oder ihre Eigenschaften (einschließlich Position und Größe) vom Benutzer ändern lassen. Dieses Flag schränkt jedoch keine Änderungen am Inhalt der Annotation ein, wie den Wert eines Formularfelds. |
| ToggleNoView | `100` | Wenn gesetzt, die Interpretation des NoView-Flags für bestimmte Ereignisse umkehren. Eine typische Verwendung besteht darin, eine Annotation zu haben, die nur angezeigt wird, wenn der Mauszeiger darüber gehalten wird. |
| LockedContents | `200` | Wenn gesetzt, die Inhalte der Annotation nicht vom Benutzer ändern lassen. Dieses Flag schränkt das Löschen der Annotation oder Änderungen an anderen Annotations Eigenschaften, wie Position und Größe, nicht ein. |

### Siehe auch

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)