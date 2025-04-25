---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Document property. Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time so to embed these fonts its necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on documents level  EmbedStandardFonts  true This property can be set only one time for all fonts. By default false
type: docs
weight: 160
url: /net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


