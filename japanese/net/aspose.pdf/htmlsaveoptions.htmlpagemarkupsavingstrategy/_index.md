---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 変換の結果は、外部ファイル（画像やフォントなど）を参照することもできる1つまたは複数のHTMLページを含むことがあります。このプロパティには、変換中に作成されたHTMLページ（HTML自体）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。この場合、ストリームやディスクへの保存などの処理は、そのカスタムコード内で行うことができます。この場合、HTMLページのマークアップを保存するために必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。この場合、何らかの理由で処理がコンバータのコード自体によって行われなければならない場合は、カスタムコード内で'htmlSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップがコンバータ自体で行われなければならないことをコンバータに通知します。まるで外部のカスタム保存コードが存在しないかのように。
type: docs
weight: 5680
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy デリゲート

変換の結果は、外部ファイル（画像やフォントなど）を参照することもできる1つまたは複数のHTMLページを含むことがあります。このプロパティには、変換中に作成されたHTMLページ（HTML自体）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。この場合、ストリームやディスクへの保存などの処理は、そのカスタムコード内で行うことができます。この場合、HTMLページのマークアップを保存するために必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。この場合、何らかの理由で処理がコンバータのコード自体によって行われなければならない場合は、カスタムコード内で'htmlSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップがコンバータ自体で行われなければならないことをコンバータに通知します。まるで外部のカスタム保存コードが存在しないかのように。

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 提供されたHTMLページの保存または処理に使用できるデータを表します |

### 参照

* クラス [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)