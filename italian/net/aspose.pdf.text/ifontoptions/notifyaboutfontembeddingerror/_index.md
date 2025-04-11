---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Proprietà IFontOptions. A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione. Quando si verifica questa situazione, non è semplice da rilevare, perché il font desiderato è incorporato tramite un insieme di flag di proprietà Font.IsEmbedded = true; Certamente è possibile leggere questa proprietà immediatamente dopo che è stata impostata, ma non è un approccio conveniente. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font è fallito. Se questo flag è impostato, verrà generata un'eccezione di tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Per impostazione predefinita false.
type: docs
weight: 10
url: /it/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Proprietà IFontOptions.NotifyAboutFontEmbeddingError

A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione. Quando si verifica questa situazione, non è semplice da rilevare, perché il font desiderato è incorporato tramite un insieme di flag di proprietà Font.IsEmbedded = true; Certamente è possibile leggere questa proprietà immediatamente dopo che è stata impostata, ma non è un approccio conveniente. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font è fallito. Se questo flag è impostato, verrà generata un'eccezione di tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Per impostazione predefinita false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Vedi Anche

* interfaccia [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)