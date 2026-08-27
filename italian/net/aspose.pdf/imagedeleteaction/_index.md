---
title: "Enum ImageDeleteAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.ImageDeleteAction enum. Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine è rimosso"
type: docs
weight: 6000
url: /it/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine è rimosso

```csharp
public enum ImageDeleteAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| KeepContents | `0` | L'immagine verrà rimossa dalla collezione. Se il contenuto della pagina contiene riferimenti all'immagine, questi non verranno rimossi. Il documento potrebbe diventare non valido. |
| None | `1` | L'immagine verrà rimossa dalla collezione e dal contenuto della pagina, ma l'oggetto immagine non verrà eliminato. La dimensione del file non verrà ridotta. |
| ForceDelete | `2` | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso dal documento. Se esistono altri riferimenti allo stesso oggetto, il documento potrebbe risultare corrotto. |
| Check | `3` | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso solo se non ci sono altri riferimenti all'immagine da altre pagine. Questo potrebbe richiedere più tempo rispetto all'opzione ForceDelete. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


