---
title: "デリゲート HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "変換結果には、画像やフォントなどの外部ファイルを参照できる 1 つまたは複数の HTML ページが含まれる場合があります。このプロパティには、変換中に作成された HTML ページ自体の処理を実装したカスタム メソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができます。この場合、HTML ページのマークアップ保存に必要なすべての操作は、提供されたメソッドのコード内で実行しなければなりません。なぜかコンバータのコード自体で処理を行う必要がある場合は、カスタムコードで CustomProcessingCancelled フラグを htmlSavingInfo パラメータの変数に設定してください。これにより、リソースの処理に必要なすべての手順がコンバータ自身で実行されることをコンバータに通知します。"
type: docs
weight: 5810
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

変換結果には、画像やフォントなどの外部ファイルを参照できる 1 つまたは複数の HTML ページが含まれる場合があります。このプロパティには、変換中に作成された HTML ページ（HTML 自体）の処理を実装したカスタム メソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができます。この場合、HTML ページのマークアップ保存に必要なすべての操作は、提供されたメソッドのコード内で実行しなければなりません。なぜかカスタムコードではなくコンバータのコード自体で処理を行う必要がある場合は、カスタムコードで 'CustomProcessingCancelled' フラグを 'htmlSavingInfo' パラメータの変数に設定してください。これにより、外部のカスタム保存コードがないかのように、リソースの処理に必要なすべての手順がコンバータ自身で実行されることをコンバータに通知します。

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 提供された HTML ページの保存または処理に使用できるデータを表します。 |

### 関連項目

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


