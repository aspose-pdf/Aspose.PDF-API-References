---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントプロパティ。ドキュメントが、フラグ IsEmbedded が true に設定されたすべての標準 Type1 フォントを埋め込む必要があることを宣言するプロパティ。すべての PDF フォントは、フラグ IsEmbedded を true に設定することでドキュメントに埋め込むことができますが、PDF 標準 Type1 フォントはこのルールの例外です。標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定されたフォントのフラグ IsEmbedded を true に設定するだけでなく、ドキュメントレベルで追加のフラグ EmbedStandardFonts = true を設定する必要があります。このプロパティは、すべてのフォントに対して一度だけ設定できます。デフォルトは false です。
type: docs
weight: 150
url: /ja/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts プロパティ

ドキュメントが、フラグ IsEmbedded が true に設定されたすべての標準 Type1 フォントを埋め込む必要があることを宣言するプロパティ。すべての PDF フォントは、フラグ IsEmbedded を true に設定することでドキュメントに埋め込むことができますが、PDF 標準 Type1 フォントはこのルールの例外です。標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定されたフォントのフラグ IsEmbedded を true に設定するだけでなく、ドキュメントレベルで追加のフラグ - EmbedStandardFonts = true; を設定する必要があります。このプロパティは、すべてのフォントに対して一度だけ設定できます。デフォルトは false です。

```csharp
public bool EmbedStandardFonts { get; set; }
```

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)