---
title: "IFontOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Proprietà utili per regolare il comportamento del font"
type: docs
weight: 180
url: /it/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Proprietà utili per regolare il comportamento del font

Il tipo IFontOptions espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| notify_about_font_embedding_error | A volte non è possibile incorporare il font desiderato nel documento. Ci sono molte ragioni, ad esempio<br/>            restrizioni di licenza o quando il font desiderato non è stato trovato sul computer di destinazione.<br/>            Quando si verifica questa situazione non è semplice da rilevare, perché il font desiderato è incorporato tramite l'impostazione <br/>            della proprietà flag Font.IsEmbedded = true; Naturalmente è possibile leggere questa proprietà subito dopo che è stata impostata ma<br/>            non è un approccio comodo. Il flag NotifyAboutFontEmbeddingError attiva un meccanismo di eccezione <br/>            per i casi in cui il tentativo di incorporare il font fallisce. Se questo flag è impostato verrà sollevata un'eccezione di tipo<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) . Per impostazione predefinita è false. |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

