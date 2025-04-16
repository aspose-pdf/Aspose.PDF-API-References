---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions フィールド。このフィールドには、URL または URL テンプレートを返すカスタムメソッドを含めることができます。マルチページ生成がオンの場合、生成された結果の HTML に配置されるべき CSS の詳細については、以下を参照してください。たとえば、コンバータが生成された CSS に標準の CSS ファイル名の代わりに特定の URL を配置したい場合は、望ましい URL を生成するメソッドを作成し、このプロパティに設定するだけです。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（ある場合）は、CSS の正確な URL ではなく、プレースホルダーをページ番号で置き換えた後に、コンバータ内の string.Format（） 関数を使用して解決できるテンプレート文字列を返す必要があります。この場合の期待される戻り値の文字列の例は、'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}' です。
type: docs
weight: 300
url: /ja/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation フィールド

このフィールドには、生成された結果の HTML に配置されるべき CSS の URL（またはマルチページ生成がオンの場合の URL テンプレート）を返すカスタムメソッドを含めることができます。たとえば、コンバータが生成された CSS に標準の CSS ファイル名の代わりに特定の URL を配置したい場合は、望ましい URL を生成するメソッドを作成し、このプロパティに設定するだけです。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（ある場合）は、CSS の正確な URL ではなく、プレースホルダーをページ番号で置き換えた後に、コンバータ内の string.Format() 関数を使用して解決できるテンプレート文字列を返す必要があります。この場合の期待される戻り値の文字列の例は、'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}' です。

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### 参照

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)