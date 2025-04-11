---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation-Methode. Setzt den Überprüfungsstatus für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungsstatusmodell gehören. Beachten Sie den Status, der in anderen Textannotationen gespeichert ist, die Schlüssel für Status und Statusmodell haben.
type: docs
weight: 140
url: /de/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Setzt den Überprüfungsstatus für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungsstatusmodell gehören. Beachten Sie, dass der Status in anderen Textannotationen gespeichert ist, die Schlüssel für Status und Statusmodell haben.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| state | AnnotationState | Status für die Zuweisung. |
| userName | String | Der Benutzername, der im Kommentarheader erscheint. Der Name kann derselbe sein wie der Name im Titel der Zielannotation oder anders, wenn der Status von einem anderen Benutzer gesetzt wird. |

### Siehe auch

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Setzt den Überprüfungsstatus für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungsstatusmodell gehören. Der Status wird von dem Benutzer gesetzt, der die Zielannotation erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielannotation entnommen. Beachten Sie, dass der Status in anderen Textannotationen gespeichert ist, die Schlüssel für Status und Statusmodell haben.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| state | AnnotationState | Status für die Zuweisung. |

### Siehe auch

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)