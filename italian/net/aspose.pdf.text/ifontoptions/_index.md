---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Interfaccia Aspose.Pdf.Text.IFontOptions. Proprietà utili per regolare il comportamento del Font
type: docs
weight: 10610
url: /it/net/aspose.pdf.text/ifontoptions/
---
## Interfaccia IFontOptions

Proprietà utili per regolare il comportamento del Font

```csharp
public interface IFontOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione. Quando si verifica questa situazione, non è semplice da rilevare, perché il font desiderato è incorporato tramite il set di proprietà flag Font.IsEmbedded = true; Certo, è possibile leggere questa proprietà immediatamente dopo che è stata impostata, ma non è un approccio conveniente. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font è fallito. Se questo flag è impostato, verrà generata un'eccezione di tipo [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). Di default è falso. |

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)