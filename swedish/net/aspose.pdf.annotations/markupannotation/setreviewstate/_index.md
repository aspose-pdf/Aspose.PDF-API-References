---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation-metod. Ställer in granskningsstatus för en anteckning. Markerade och Omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Observera tillståndet som lagras i andra textanteckningar som har state och statemodel nycklar
type: docs
weight: 140
url: /sv/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Ställer in granskningsstatus för en anteckning. Markerade och Omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Observera, tillståndet som lagras i andra textanteckningar som har state och statemodel nycklar.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| state | AnnotationState | Status för tilldelning. |
| userName | String | Användarnamnet som visas i kommentarhuvudet. Namnet kan vara detsamma som namnet i titeln på den målanteckningen eller olika om statusen sätts av en annan användare. |

### Se Även

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Ställer in granskningsstatus för en anteckning. Markerade och Omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av användaren som skapade den målanteckningen. Värdet tas från Title-egenskapen för den målanteckningen. Observera, tillståndet som lagras i andra textanteckningar som har state och statemodel nycklar.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| state | AnnotationState | Status för tilldelning. |

### Se Även

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)