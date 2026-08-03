---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF för .NET API‑referens"
description: "MarkupAnnotation-metod. Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Observera att tillståndet lagras i andra textannotationer som har nycklarna state och statemodel."
type: docs
weight: 140
url: /sv/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Ställer in granskningsstatusen för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tillstånd | AnnotationState | Status för tilldelning. |
| userName | String | Användarnamnet som visas i kommentarsrubriken. Namnet kan vara samma som namnet i titeln för målannotation eller annorlunda om statusen har satts av en annan användare. |

### Se även

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Ställer in granskningsstatusen för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av den användare som skapade målannoteringen. Värdet hämtas från Title‑egenskapen för målannoteringen. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tillstånd | AnnotationState | Status för tilldelning. |

### Se även

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


