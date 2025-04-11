---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Text.IFontOptions. Propriétés utiles pour ajuster le comportement de la police
type: docs
weight: 10610
url: /fr/net/aspose.pdf.text/ifontoptions/
---
## Interface IFontOptions

Propriétés utiles pour ajuster le comportement de la police

```csharp
public interface IFontOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Parfois, il n'est pas possible d'incorporer la police souhaitée dans le document. Il y a de nombreuses raisons, par exemple des restrictions de licence ou lorsque la police souhaitée n'a pas été trouvée sur l'ordinateur de destination. Lorsque cette situation se présente, il n'est pas simple de le détecter, car la police souhaitée est incorporée via un ensemble de propriétés avec le drapeau Font.IsEmbedded = true; Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle ait été définie, mais ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception pour les cas où la tentative d'incorporation de la police a échoué. Si ce drapeau est défini, une exception de type [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) sera levée. Par défaut, faux. |

### Voir aussi

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)