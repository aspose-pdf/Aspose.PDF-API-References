---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "HtmlSaveOptions フィールド。変換結果は 1 つまたは複数の HTMLページ を含むことがあります。このプロパティには、変換中に作成された外部リンクファイルがない正確なマークアップHTML を生成するカスタムメソッドから作成されたデリゲートを割り当てることができます。そのような場合、HTMLページをストリームやディスクに保存する処理はカスタムコードで行うことができます。したがって、HTMLページの保存に必要なすべての操作は、提供されたメソッドのコード内で実行する必要があります。コンバータのコードで結果を保存する処理は使用されません。もし、何らかの理由でこの処理をコンバータ自身のコードで行う必要がある場合は、カスタムコード内で htmlSavingInfo パラメータの変数 CustomProcessingCancelled フラグを設定してください。これにより、外部のカスタムコードが存在しないかのように、リソースの処理はコンバータ自身で行われることをコンバータに通知します。"
type: docs
weight: 270
url: /ja/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

変換結果は 1 つまたは複数の HTML ページを含むことがあります。このプロパティには、変換中に作成された 1 つの HTML ページ（正確にはマークアップ HTML で、外部リンクファイルがある場合は除く）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ページの HTML をストリームやディスクに保存するなどの処理はカスタムコードで行われます。したがって、HTML ページの保存に必要なすべての操作は、提供されたメソッドのコード内で実行する必要があります。変換ツールのコードで処理すべきケースがあり、カスタムコードで行わない場合は、カスタムコード内で 'htmlSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これにより、外部カスタムコードが存在しないかのように、コンバータ自身がそのリソースの処理を行うことを示します。

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 関連項目

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


