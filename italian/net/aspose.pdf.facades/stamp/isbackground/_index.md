---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Stamp. Ottiene o imposta lo stato di sfondo. Se true il timbro verrà posizionato come sfondo della pagina spampata. Per impostazione predefinita è impostato su false"
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Ottiene o imposta lo stato di sfondo. Se vero, il timbro verrà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su falso.

```csharp
public bool IsBackground { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


