---
title: Aspose::Pdf::Document::get_EmbedStandardFonts method
linktitle: get_EmbedStandardFonts
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::get_EmbedStandardFonts method. Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it''s necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document''s level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false in C++.'
type: docs
weight: 2700
url: /cpp/aspose.pdf/document/get_embedstandardfonts/
---
## Document::get_EmbedStandardFonts method


Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

```cpp
bool Aspose::Pdf::Document::get_EmbedStandardFonts() const
```

## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
