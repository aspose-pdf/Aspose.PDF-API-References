---
title: "デリゲート HtmlSaveOptions.CssSavingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "このプロパティに、PDF から HTML への変換中に作成された 1 つの CSS 部分の処理または保存を実装するカスタム戦略を割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコード内で行う必要があります。"
type: docs
weight: 5720
url: /ja/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

このプロパティに、PDF から HTML への変換中に作成された 1 つの CSS の部分の処理または保存を実装するカスタム戦略を割り当てることができます。その場合、（ストリームやディスクへの保存などの）処理はカスタムコード内で行う必要があります。

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 提供された CSS 部分の保存に使用できるデータの集合を表します。 |

### 関連項目

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


