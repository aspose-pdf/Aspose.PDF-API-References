---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "HtmlSaveOptions フィールド。このフィールドには、マルチページ生成が有効な場合に URL または URL テンプレートを返すカスタムメソッドを含めることができます。以下の CSS に関する詳細は、生成された結果 HTML に配置されるべきものです。たとえば、変換時に標準の CSS ファイル名の代わりに特定の URL を生成したい場合は、このプロパティに望ましい URL を生成するメソッドを作成して設定します。SplitCssIntoPages フラグが設定されている場合、このカスタム戦略は CSS の正確な URL ではなく、プレースホルダーをページ番号に置換し、コンバータ内の string.Format 関数で解決できるテンプレート文字列を返す必要があります。このようなケースで期待される戻り文字列の例は、SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0 です。"
type: docs
weight: 300
url: /ja/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

このフィールドには、生成された結果 HTML に配置すべき対象 CSS の URL（マルチページ生成が有効な場合は URL テンプレート）を返すカスタムメソッドを指定できます。たとえば、標準の CSS ファイル名の代わりに特定の URL を使用したい場合は、望ましい URL を生成するメソッドを作成し、このプロパティに設定してください。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（存在する場合）は CSS の正確な URL ではなく、プレースホルダーをページ番号で置換する（converter 内の string.Format() 関数を使用）ことで各ページの CSS URL に解決できるテンプレート文字列を返す必要があります。そのような場合に期待される返却文字列の例は、'SomeTargetLocation-page_{0}.css'、'../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}' です。

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### 関連項目

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


