---
title: Aspose::Pdf::Text::FontRepository class
linktitle: FontRepository
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontRepository class. Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.text/fontrepository/
---
## FontRepository class


Performs font search. Searches in system installed fonts and standard [Pdf](../../aspose.pdf/) fonts. Also provides functionality to open custom fonts.

```cpp
class FontRepository : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [FindFont](./findfont/)(System::String) | Searches and returns font with specified font name. |
| static [FindFont](./findfont/)(System::String, bool) | Searches and returns font with specified font name ignoring or honoring case sensitivity. |
| static [FindFont](./findfont/)(System::String, FontStyles) | Searches and returns font with specified font name and font style. |
| static [FindFont](./findfont/)(System::String, FontStyles, bool) | Searches and returns font with specified font name and font style ignoring or honoring case sensitivity. |
| static [get_Sources](./get_sources/)() | Gets font sources collection. |
| static [get_Substitutions](./get_substitutions/)() | Gets font substitution strategies collection. |
| static [LoadFonts](./loadfonts/)() | Loads system installed fonts and standard [Pdf](../../aspose.pdf/) fonts. This method was designed to speed up font loading process. By default fonts are loaded on first request for any font. Use of this method loads system and standard [Pdf](../../aspose.pdf/) fonts immediately before any [Pdf](../../aspose.pdf/) document was open. |
| static [OpenFont](./openfont/)(System::SharedPtr\<System::IO::Stream\>, FontTypes) | Opens font with specified font stream. |
| static [OpenFont](./openfont/)(System::String) | Opens font with specified font file path. |
| static [OpenFont](./openfont/)(System::String, System::String) | Opens font with specified font file path and metrics file path. |
| static [ReloadFonts](./reloadfonts/)() | Reloads all fonts specified by property [Sources](../) |


## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
