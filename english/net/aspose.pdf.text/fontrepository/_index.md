---
title: "FontRepository Class"
linktitle: "FontRepository"
articleTitle: "FontRepository"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.FontRepository class. Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open cu..."
type: docs
weight: 150
url: "/net/aspose.pdf.text/fontrepository/"
keywords: "FontRepository, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FontRepository class

Performs font search. Searches in system installed fonts and standard Pdf fonts.
 Also provides functionality to open custom fonts.

```csharp
public sealed class FontRepository
```

## Constructors

| Name | Description |
| --- | --- |
| [FontRepository](./fontrepository/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Sources](./sources/) { get; } | Gets font sources collection. |
| [Substitutions](./substitutions/) { get; } | Gets font substitution strategies collection. |

## Methods

| Name | Description |
| --- | --- |
| [FindFont](./findfont/)(*string*) | Searches and returns font with specified font name. |
| [FindFont](./findfont/)(*string, bool*) | Searches and returns font with specified font name ignoring or honoring case sensitivity. |
| [FindFont](./findfont/)(*string, FontStyles*) | Searches and returns font with specified font name and font style. |
| [FindFont](./findfont/)(*string, FontStyles, bool*) | Searches and returns font with specified font name and font style. |
| [LoadFonts](./loadfonts/) | Loads system installed fonts and standard Pdf fonts. This method was designed to speed up font loading process. |
| [OpenFont](./openfont/)(*string*) | Opens font with specified font file path. |
| [OpenFont](./openfont/)(*Stream, FontTypes*) | Opens font with specified font stream. |
| [OpenFont](./openfont/)(*string, string*) | Opens font with specified font file path and metrics file path. |
| [ReloadFonts](./reloadfonts/) | Reloads all fonts specified by property `Sources`. |

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [Document](../document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

