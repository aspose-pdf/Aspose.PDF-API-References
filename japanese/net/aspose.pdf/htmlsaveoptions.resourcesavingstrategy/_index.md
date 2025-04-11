---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: このプロパティには、PDFから抽出された外部リソース（フォントまたは画像）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。これらはPDFをHTMLに変換する際に外部リソースとして保存される必要があります。この場合、ストリームやディスクに保存するような処理はそのカスタムコードで行われ、そのカスタムコードは、生成されたHTMLに組み込まれる元の画像リソースのパスの代わりに、後で使用されるパス（または引用符なしの他の文字列）を返さなければなりません。この場合、画像の保存に必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。何らかの理由でこのファイルの処理がカスタムコードではなくコンバータのコード自体によって行われる必要がある場合は、カスタムコード内で'resourceSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップがコンバータ自体で行われるべきであることをコンバータに通知します。まるで外部のカスタムコードが存在しないかのように。
type: docs
weight: 5730
url: /ja/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy デリゲート

このプロパティには、PDFから抽出された外部リソース（フォントまたは画像）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。これらはPDFをHTMLに変換する際に外部リソースとして保存される必要があります。この場合、ストリームやディスクに保存するような処理はそのカスタムコードで行われ、そのカスタムコードは、生成されたHTMLに組み込まれる元の画像リソースのパスの代わりに、後で使用されるパス（または引用符なしの他の文字列）を返さなければなりません。この場合、画像の保存に必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。何らかの理由でこのファイルの処理がカスタムコードではなくコンバータのコード自体によって行われる必要がある場合は、カスタムコード内で'resourceSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップがコンバータ自体で行われるべきであることをコンバータに通知します。まるで外部のカスタムコードが存在しないかのように。

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | リソースの保存のためのデータセットを表します |

### 戻り値

保存されたリソースへのURLを返さなければなりません。これはHTMLの生成中に使用されます。

### 参照

* クラス [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)