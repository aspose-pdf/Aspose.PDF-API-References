---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi in cui la pagina deve essere visualizzata durante la presentazione. Restituisce 1 se la durata non è definita
type: docs
weight: 110
url: /it/net/aspose.pdf/page/duration/
---
## Proprietà Page.Duration

Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi in cui la pagina deve essere visualizzata durante la presentazione. Restituisce -1 se la durata non è definita.

```csharp
public double Duration { get; set; }
```

## Esempi

L'esempio dimostra come ottenere la durata della pagina

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Vedi Anche

* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)