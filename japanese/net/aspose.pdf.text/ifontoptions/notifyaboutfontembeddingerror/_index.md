---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IFontOptions プロパティ。目的のフォントをドキュメントに埋め込めないことがあります。たとえばライセンス制限や、目的のフォントが対象コンピュータに見つからない場合など、さまざまな理由があります。このような状況が発生すると、目的のフォントはプロパティ フラグ Font.IsEmbedded が true に設定されて埋め込まれているため、検出が容易ではありません。もちろん、このプロパティは設定直後に読み取ることは可能ですが、便利な方法とは言えません。Flag NotifyAboutFontEmbeddingError は、フォント埋め込みが失敗した場合に例外メカニズムを強制します。このフラグが設定されていると、FontEmbeddingException 型の例外がスローされます。既定は false。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

目的のフォントをドキュメントに埋め込めないことがあります。たとえばライセンス制限や、目的のフォントが対象コンピュータに見つからない場合など、さまざまな理由があります。このような状況が発生すると、目的のフォントはプロパティ フラグ Font.IsEmbedded = true によって埋め込まれているため、検出が容易ではありません。もちろん、このプロパティは設定直後に読み取ることは可能ですが、便利な方法とは言えません。Flag NotifyAboutFontEmbeddingError は、フォント埋め込みが失敗した場合に例外メカニズムを強制します。このフラグが設定されていると、[`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 型の例外がスローされます。既定は false。

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 関連項目

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


