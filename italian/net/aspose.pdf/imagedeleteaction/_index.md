---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction enum. Action which performed with image object when image is removed from collection. If image object is removed
type: docs
weight: 5870
url: /it/net/aspose.pdf/imagedeleteaction/
---
## Enumerazione ImageDeleteAction

Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine viene rimosso

```csharp
public enum ImageDeleteAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| KeepContents | `0` | L'immagine verrà rimossa dalla collezione. Se i contenuti della pagina contengono riferimenti all'immagine, questi non verranno rimossi. Il documento potrebbe diventare non valido. |
| None | `1` | L'immagine verrà rimossa dalla collezione e dai contenuti della pagina, ma l'oggetto immagine non verrà eliminato. La dimensione del file non verrà ridotta. |
| ForceDelete | `2` | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso dal documento. Se esistono altri riferimenti allo stesso oggetto, il documento potrebbe essere corrotto. |
| Check | `3` | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso solo se non ci sono altri riferimenti all'immagine da altre pagine. Questo potrebbe richiedere più tempo rispetto all'opzione ForceDelete. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)