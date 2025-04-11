---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Méthode MarkupAnnotation. Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au modèle d'état de révision. Notez l'état stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état.
type: docs
weight: 140
url: /fr/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au modèle d'état de révision. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Statut pour l'attribution. |
| userName | String | Le nom d'utilisateur qui apparaît dans l'en-tête des commentaires. Le nom peut être le même que celui du titre de l'annotation cible ou différent si le statut est défini par un autre utilisateur. |

### Voir aussi

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au modèle d'état de révision. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est tirée de la propriété Titre de l'annotation cible. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état.

```csharp
public void SetReviewState(AnnotationState state)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Statut pour l'attribution. |

### Voir aussi

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)