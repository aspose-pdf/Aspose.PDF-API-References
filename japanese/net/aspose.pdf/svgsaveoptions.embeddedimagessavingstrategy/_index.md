---
title: "デリゲート SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "この型のプロパティには、PDF から生成された SVG から抽出され、PDF から HTML への変換中に外部リソースとして保存される画像の外部保存処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの自己作成保存などの処理はカスタムコード内で行うことができ、カスタムコードは引用符なしのパスまたはその他の文字列を返す必要があります。その文字列は、生成された SVG に元の画像リソースのパスの代わりに組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行しなければなりません。コンバータのコードで結果を保存する処理は使用されません。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコードのフラグ CustomProcessingCancelled を imageSavingInfo パラメータの変数に設定してください。これにより、コンバータは外部カスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身で実行することを示します。これは、保存された画像に関する情報を表し、カスタムコードで使用できる文字列（画像の URL）を返す必要があります。その URL は SVG に挿入されます。"
type: docs
weight: 10420
url: /ja/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

この型のプロパティには、PDF から生成された SVG から抽出され、PDF から HTML への変換中に外部リソースとして保存される画像の外部保存処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの自己作成保存などの処理はカスタムコード内で行うことができ、カスタムコードは引用符なしのパス（またはその他の文字列）を返す必要があります。その文字列は、生成された SVG に元の画像リソースのパスの代わりに組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行しなければなりません。コンバータのコードで結果を保存する処理は使用されません。何らかの理由でこのファイルまたはそのファイルの処理をコンバータのコード自体で行う必要がある場合は、カスタムコードのフラグ 'CustomProcessingCancelled' を 'imageSavingInfo' パラメータの変数に設定してください。これにより、コンバータは外部カスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身で実行することを示します。これは、保存された画像に関する情報を表し、カスタムコードで使用できる文字列（画像の URL）を返す必要があります。その URL は SVG に挿入されます。

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### 関連項目

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


