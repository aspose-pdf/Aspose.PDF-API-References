---
title: "Document.EmbedStandardFonts"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document プロパティ。ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言するプロパティで、フラグ IsEmbedded が true に設定されます。すべての PDF フォントはフラグ IsEmbedded を true に設定するだけでドキュメントに埋め込むことができますが、PDF の標準 Type1 フォントはこの規則の例外です。標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定されたフォントの IsEmbedded フラグを true に設定するだけでなく、ドキュメントレベルで追加のフラグ EmbedStandardFonts を true に設定する必要があります。このプロパティはすべてのフォントに対して一度だけ設定できます。デフォルトは false です。"
type: docs
weight: 160
url: /ja/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

このプロパティは、フラグ IsEmbedded が true に設定されたすべての標準 Type1 フォントを Document に埋め込む必要があることを宣言します。すべての PDF フォントはフラグ IsEmbedded を true に設定するだけで Document に埋め込むことができますが、PDF の標準 Type1 フォントはこの規則の例外です。標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定したフォントのフラグ IsEmbedded を true に設定するだけでなく、Document レベルで追加のフラグ EmbedStandardFonts = true を設定する必要があります。このプロパティはすべてのフォントに対して一度だけ設定可能です。既定は false です。

```csharp
public bool EmbedStandardFonts { get; set; }
```

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


