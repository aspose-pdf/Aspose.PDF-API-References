---
title: "デリゲート HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "このプロパティには、生成されたHTMLドキュメントで参照されるCSSのURL作成を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。例えば、HTMLで参照されるCSSを otherPage.ASPXCssIDzjjkklj としたい場合、そのようなカスタム戦略は otherPage.ASPXCssIDzjjkklj を返す必要があります。"
type: docs
weight: 5730
url: /ja/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

このプロパティには、生成されたHTMLドキュメントで参照されるCSSのURL作成を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。例えば、HTMLで参照されるCSSを "otherPage.ASPX?CssID=zjjkklj" としたい場合、そのようなカスタム戦略は "otherPage.ASPX?CssID=zjjkklj" を返す必要があります。

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | CSSのURL生成に使用できるデータの集合を表します |

### 戻り値

CSSのURLまたはURLテンプレートを表す文字列を返す必要があります

### 関連項目

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


