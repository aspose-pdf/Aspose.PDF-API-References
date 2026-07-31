---
title: "Page.Duration"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Page. Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione. Restituisce 1 se la durata non è definita."
type: docs
weight: 110
url: /it/net/aspose.pdf/page/duration/
---
## Page.Duration property

Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione. Restituisce -1 se la durata non è definita.

```csharp
public double Duration { get; set; }
```

## Esempi

L'esempio mostra come ottenere la durata della pagina

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Vedi anche

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


