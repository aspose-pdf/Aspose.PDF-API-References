---
title: "Interfaccia IFontOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Interfaccia Aspose.Pdf.Text.IFontOptions. Proprietà utili per regolare il comportamento dei Font"
type: docs
weight: 10790
url: /it/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Proprietà utili per regolare il comportamento del Font

```csharp
public interface IFontOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o il fatto che il font desiderato non sia stato trovato sul computer di destinazione. Quando si verifica questa situazione non è semplice da rilevare, perché il font desiderato è incorporato tramite l'impostazione della proprietà `Font.IsEmbedded = true;`. Naturalmente è possibile leggere questa proprietà subito dopo che è stata impostata, ma non è un approccio comodo. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font fallisce. Se questo flag è impostato verrà sollevata un'eccezione di tipo [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). Per impostazione predefinita è false. |

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


