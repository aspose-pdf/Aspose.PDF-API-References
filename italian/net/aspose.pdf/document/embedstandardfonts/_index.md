---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del documento. Proprietà che dichiara che il documento deve incorporare tutti i font standard Type1 che hanno il flag IsEmbedded impostato su true. Tutti i font PDF possono essere incorporati nel documento semplicemente impostando il flag IsEmbedded su true, ma i font standard Type1 PDF sono un'eccezione a questa regola. L'incorporamento dei font standard Type1 richiede molto tempo, quindi per incorporare questi font è necessario non solo impostare il flag IsEmbedded su true per il font specificato, ma anche impostare un flag aggiuntivo a livello di documento - EmbedStandardFonts = true; Questa proprietà può essere impostata solo una volta per tutti i font. Per impostazione predefinita false.
type: docs
weight: 150
url: /it/net/aspose.pdf/document/embedstandardfonts/
---
## Proprietà Document.EmbedStandardFonts

Proprietà che dichiara che il documento deve incorporare tutti i font standard Type1 che hanno il flag IsEmbedded impostato su true. Tutti i font PDF possono essere incorporati nel documento semplicemente impostando il flag IsEmbedded su true, ma i font standard Type1 PDF sono un'eccezione a questa regola. L'incorporamento dei font standard Type1 richiede molto tempo, quindi per incorporare questi font è necessario non solo impostare il flag IsEmbedded su true per il font specificato, ma anche impostare un flag aggiuntivo a livello di documento - EmbedStandardFonts = true; Questa proprietà può essere impostata solo una volta per tutti i font. Per impostazione predefinita false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)