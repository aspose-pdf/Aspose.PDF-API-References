---
title: "Document.EmbedStandardFonts"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà del Document. Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true. Tutti i font PDF possono essere incorporati nel documento semplicemente impostando il flag IsEmbedded su true, ma i font PDF Type1 standard sono un'eccezione a questa regola. L'incorporamento dei font Type1 standard richiede molto tempo, quindi per incorporare questi font è necessario non solo impostare il flag IsEmbedded su true per il font specificato, ma anche impostare un flag aggiuntivo a livello del documento EmbedStandardFonts true. Questa proprietà può essere impostata una sola volta per tutti i font. Per impostazione predefinita false."
type: docs
weight: 160
url: /it/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

Proprietà che dichiara che il documento deve incorporare tutti i caratteri Type1 standard per i quali la flag IsEmbedded è impostata su true. Tutti i caratteri PDF possono essere incorporati nel documento semplicemente impostando la flag IsEmbedded su true, ma i caratteri PDF standard Type1 sono un'eccezione a questa regola. L'incorporamento dei caratteri Type1 standard richiede molto tempo, quindi per incorporare questi caratteri è necessario non solo impostare la flag IsEmbedded su true per il carattere specificato, ma anche impostare una flag aggiuntiva a livello di documento - EmbedStandardFonts = true; Questa proprietà può essere impostata una sola volta per tutti i caratteri. Per impostazione predefinita false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


