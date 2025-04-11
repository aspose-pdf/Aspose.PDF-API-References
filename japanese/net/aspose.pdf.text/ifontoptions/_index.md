---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions インターフェース。フォントの動作を調整するための便利なプロパティ
type: docs
weight: 10610
url: /ja/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions インターフェース

フォントの動作を調整するための便利なプロパティ

```csharp
public interface IFontOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 時々、希望するフォントをドキュメントに埋め込むことができない場合があります。理由はいくつかあり、例えばライセンスの制限や、希望するフォントが宛先コンピュータに見つからない場合です。この状況が発生した場合、希望するフォントはプロパティフラグ Font.IsEmbedded = true; を介して埋め込まれるため、単純に検出することはできません。もちろん、設定された直後にこのプロパティを読み取ることは可能ですが、それは便利なアプローチではありません。フラグ NotifyAboutFontEmbeddingError は、フォントの埋め込みが失敗した場合の例外メカニズムを強制します。このフラグが設定されている場合、[`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) 型の例外がスローされます。デフォルトは false です。 |

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)