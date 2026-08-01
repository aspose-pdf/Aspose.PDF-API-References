---
title: "インターフェイス IFontOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.IFontOptions インターフェイス。フォントの動作を調整するための便利なプロパティです。"
type: docs
weight: 10790
url: /ja/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

フォントの動作を調整するための便利なプロパティ

```csharp
public interface IFontOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 目的のフォントをドキュメントに埋め込むことができない場合があります。その理由は多数あり、例えばライセンス制限や、目的のフォントが対象コンピュータに見つからない場合などです。このような状況が発生すると、`Font.IsEmbedded = true` フラグによってフォントが埋め込まれるため、単純に検出することはできません。もちろん、このプロパティは設定直後に読み取ることは可能ですが、便利な方法とは言えません。フラグ `NotifyAboutFontEmbeddingError` は、フォント埋め込みが失敗した場合の例外メカニズムを強制します。このフラグが設定されていると、タイプ [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) の例外がスローされます。デフォルトは false です。 |

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


