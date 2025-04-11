---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions プロパティ。ドキュメントに希望するフォントを埋め込むことができない場合があります。ライセンス制限や、希望するフォントが宛先コンピュータに見つからない場合など、さまざまな理由があります。この状況が発生した場合、希望するフォントはプロパティフラグ Font.IsEmbedded = true を介して埋め込まれているため、単純に検出することはできません。もちろん、このプロパティは設定された直後に読み取ることができますが、それは便利なアプローチではありません。フラグ NotifyAboutFontEmbeddingError は、フォントの埋め込みが失敗した場合の例外メカニズムを強制します。このフラグが設定されている場合、[`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 型の例外がスローされます。デフォルトは false です。
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError プロパティ

ドキュメントに希望するフォントを埋め込むことができない場合があります。ライセンス制限や、希望するフォントが宛先コンピュータに見つからない場合など、さまざまな理由があります。この状況が発生した場合、希望するフォントはプロパティフラグ Font.IsEmbedded = true; を介して埋め込まれているため、単純に検出することはできません。もちろん、このプロパティは設定された直後に読み取ることができますが、それは便利なアプローチではありません。フラグ NotifyAboutFontEmbeddingError は、フォントの埋め込みが失敗した場合の例外メカニズムを強制します。このフラグが設定されている場合、[`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 型の例外がスローされます。デフォルトは false です。

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 関連項目

* インターフェース [IFontOptions](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)