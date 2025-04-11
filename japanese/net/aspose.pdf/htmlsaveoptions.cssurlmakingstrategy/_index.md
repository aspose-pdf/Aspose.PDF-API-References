---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: このプロパティには、生成された HTML ドキュメントで参照される CSS の URL を作成するカスタム メソッドから作成されたデリゲートを割り当てることができます。たとえば、HTML で "otherPage.ASPXCssIDzjjkklj" として参照される CSS を作成したい場合、そのカスタム戦略は "otherPage.ASPXCssIDzjjkklj" を返す必要があります。
type: docs
weight: 5600
url: /ja/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy デリゲート

このプロパティには、生成された HTML ドキュメントで参照される CSS の URL を作成するカスタム メソッドから作成されたデリゲートを割り当てることができます。たとえば、HTML で "otherPage.ASPX?CssID=zjjkklj" として参照される CSS を作成したい場合、そのカスタム戦略は "otherPage.ASPX?CssID=zjjkklj" を返す必要があります。

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | CSS の URL を生成するために使用できるデータのセットを表します。 |

### 戻り値

CSS の URL または URL のテンプレートを表す文字列を返す必要があります。

### 参照

* クラス [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)