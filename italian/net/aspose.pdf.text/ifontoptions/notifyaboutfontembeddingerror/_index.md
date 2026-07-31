---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "IFontOptions property. A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione. Quando si verifica questa situazione non è semplice da rilevare perché il font desiderato è incorporato tramite la proprietà flag Font.IsEmbedded  true. Naturalmente è possibile leggere questa proprietà subito dopo che è stata impostata, ma non è un approccio conveniente. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font fallisce. Se questo flag è impostato verrà sollevata un'eccezione di tipo FontEmbeddingException. Per impostazione predefinita false"
type: docs
weight: 10
url: /it/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione. Quando si verifica questa situazione non è semplice da rilevare, perché il font desiderato è incorporato tramite la proprietà flag Font.IsEmbedded = true; Naturalmente è possibile leggere questa proprietà subito dopo che è stata impostata, ma non è un approccio conveniente. Il flag NotifyAboutFontEmbeddingError impone un meccanismo di eccezione per i casi in cui il tentativo di incorporare il font fallisce. Se questo flag è impostato verrà sollevata un'eccezione di tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Per impostazione predefinita false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Vedi anche

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


