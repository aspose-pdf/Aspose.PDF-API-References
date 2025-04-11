---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions フィールド。変換の結果は、1つまたは複数のHTMLページを含むことができます。このプロパティには、1つのHTMLページの処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます（正確には、変換中に作成された外部リンクファイルがない場合のマークアップHTML）。この場合、ページのHTMLをストリームまたはディスクに保存するなどの処理は、そのカスタムコード内で行うことができます。この場合、HTMLページを保存するために必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。この場合、何らかの理由でこのケースの処理をコンバータのコード自体で行う必要がある場合は、カスタムコード内で 'htmlSavingInfo' パラメータの変数の 'CustomProcessingCancelled' フラグを設定してください。これにより、リソースの処理に必要なすべてのステップがコンバータ自体で行われるべきであることがコンバータに通知されます。まるで外部のカスタムコードが処理のために存在しなかったかのように。
type: docs
weight: 270
url: /ja/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy フィールド

変換の結果は、1つまたは複数のHTMLページを含むことができます。このプロパティには、1つのHTMLページの処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます（正確には、変換中に作成された外部リンクファイルがない場合のマークアップHTML）。この場合、ページのHTMLをストリームまたはディスクに保存するなどの処理は、そのカスタムコード内で行うことができます。この場合、HTMLページを保存するために必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。この場合、何らかの理由でこのケースの処理をコンバータのコード自体で行う必要がある場合は、カスタムコード内で 'htmlSavingInfo' パラメータの変数の 'CustomProcessingCancelled' フラグを設定してください。これにより、リソースの処理に必要なすべてのステップがコンバータ自体で行われるべきであることがコンバータに通知されます。まるで外部のカスタムコードが処理のために存在しなかったかのように。

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 参照

* デリゲート [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* クラス [HtmlSaveOptions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)