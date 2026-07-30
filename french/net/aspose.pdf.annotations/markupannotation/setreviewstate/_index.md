---
title: "MarkupAnnotation.SetReviewState"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "MarkupAnnotation méthode. Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Notez l'état stocké dans d'autres annotations de texte qui possèdent les clés state et statemodel."
type: docs
weight: 140
url: /fr/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Statut pour l'affectation. |
| userName | String | Le nom d'utilisateur qui apparaît dans l'en-tête des commentaires. Le nom peut être identique au nom dans le Title de l'annotation cible ou différent si le statut est défini par un autre utilisateur. |

### Voir aussi

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Statut pour l'affectation. |

### Voir aussi

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


