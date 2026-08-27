---
title: "Font.DecodedFontName"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Font. A volte i font PDF (solitamente font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà PDF del font BaseFont e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente potrebbe risultare non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo le regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi usala nei casi in cui incontri un FontName non leggibile. Se la proprietà FontName ha una forma leggibile, questa proprietà sarà identica a FontName, così puoi usarla in qualsiasi caso in cui sia necessario ottenere il nome del font in una forma leggibile."
type: docs
weight: 20
url: /it/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName property

A volte i font PDF (solitamente font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà PDF del font "BaseFont" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente potrebbe risultare non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo le regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi usala nei casi in cui incontri un [`FontName`](../fontname/) non leggibile. Se la proprietà [`FontName`](../fontname/) ha una forma leggibile, questa proprietà sarà identica a [`FontName`](../fontname/), così puoi usarla in qualsiasi caso in cui sia necessario ottenere il nome del font in una forma leggibile.

```csharp
public string DecodedFontName { get; }
```

### Vedi anche

* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


