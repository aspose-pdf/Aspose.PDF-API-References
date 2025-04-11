---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: このプロパティには、PDFをHTMLに変換する際に作成されたCSSの一部の処理または保存を実装するカスタム戦略を割り当てることができます。この場合、ストリームまたはディスクへの保存などの処理は、そのカスタムコード内で行う必要があります。
type: docs
weight: 5590
url: /ja/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy デリゲート

このプロパティには、PDFをHTMLに変換する際に作成されたCSSの一部の処理または保存を実装するカスタム戦略を割り当てることができます。この場合、処理（ストリームまたはディスクへの保存など）は、そのカスタムコード内で行う必要があります。

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 提供されたCSS部分の保存に使用できるデータのセットを表します。 |

### 関連項目

* クラス [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)