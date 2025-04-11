---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: このタイプのプロパティには、PDFから作成されたSVGから抽出された画像の外部保存処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。PDFからHTMLへの変換中に外部リソースとして保存する必要があります。この場合、ストリームやディスクへの独自の保存のような処理は、そのカスタムコード内で行うことができ、そのカスタムコードは、生成されたSVGに組み込まれる元の画像リソースへのパスの代わりに、後で組み込まれるパス（または引用符なしの他の任意の文字列）を返す必要があります。この場合、画像の保存に必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。このファイルの処理が何らかの理由でカスタムコードではなくコンバータのコード自体によって行われなければならない場合は、カスタムコード内で'imageSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップが、外部のカスタムコードが存在しないかのようにコンバータ自体で行われるべきであることをコンバータに通知します。保存された画像に関する情報を表し、カスタムコードで使用できる必要があり、SVGに挿入される画像のURLを表す文字列を返さなければなりません。
type: docs
weight: 10240
url: /ja/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy デリゲート

このタイプのプロパティには、PDFから作成されたSVGから抽出された画像の外部保存処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。PDFからHTMLへの変換中に外部リソースとして保存する必要があります。この場合、ストリームやディスクへの独自の保存のような処理は、そのカスタムコード内で行うことができ、そのカスタムコードは、生成されたSVGに組み込まれる元の画像リソースへのパスの代わりに、後で組み込まれるパス（または引用符なしの他の任意の文字列）を返す必要があります。この場合、画像の保存に必要なすべてのアクションは、提供されたメソッドのコード内で実行されなければなりません。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。このファイルの処理が何らかの理由でカスタムコードではなくコンバータのコード自体によって行われなければならない場合は、カスタムコード内で'imageSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これは、リソースの処理に必要なすべてのステップが、外部のカスタムコードが存在しないかのようにコンバータ自体で行われるべきであることをコンバータに通知します。保存された画像に関する情報を表し、カスタムコードで使用できる必要があり、SVGに挿入される画像のURLを表す文字列を返さなければなりません。

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### 関連項目

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)