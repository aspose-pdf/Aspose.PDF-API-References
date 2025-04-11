---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del font. A volte i font PDF (di solito i font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà del font PDF "BaseFont" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge direttamente questo nome, potrebbe essere rappresentato in forma illeggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi utilizzala per i casi in cui ti imbatti in un [`FontName`](../fontname/) illeggibile. Se la proprietà [`FontName`](../fontname/) ha una forma leggibile, questa proprietà sarà la stessa di [`FontName`](../fontname/), quindi puoi utilizzare questa proprietà per qualsiasi caso in cui hai bisogno di ottenere il nome del font in una forma leggibile.
type: docs
weight: 20
url: /it/net/aspose.pdf.text/font/decodedfontname/
---
## Proprietà Font.DecodedFontName

A volte i font PDF (di solito i font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà del font PDF "BaseFont" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge direttamente questo nome, potrebbe essere rappresentato in forma illeggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi utilizzala per i casi in cui ti imbatti in un [`FontName`](../fontname/) illeggibile. Se la proprietà [`FontName`](../fontname/) ha una forma leggibile, questa proprietà sarà la stessa di [`FontName`](../fontname/), quindi puoi utilizzare questa proprietà per qualsiasi caso in cui hai bisogno di ottenere il nome del font in una forma leggibile.

```csharp
public string DecodedFontName { get; }
```

### Vedi Anche

* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)