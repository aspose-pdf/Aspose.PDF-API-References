---
title: "デリゲート HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "このプロパティには、PDF から抽出され HTML へ変換する際に外部リソースresourceFontまたはImageとして保存する必要がある外部リソースの処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存といった処理はカスタムコード内で行い、カスタムコードは引用符なしのパスまたはその他の文字列を返す必要があります。その文字列は生成された HTML に組み込まれ、元の画像リソースの想定パスの代わりに使用されます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行されなければなりません。コンバータのコード内で結果を保存する処理は使用されません。もし、何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコード内で resourceSavingInfo パラメータの変数のフラグ CustomProcessingCancelled を設定してください。これにより、コンバータは外部のカスタムコードがないかのように、そのリソースの処理に必要なすべての手順をコンバータ自身で実行することを示します。"
type: docs
weight: 5860
url: /ja/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

このプロパティには、PDF から抽出され HTML へ変換する際に外部リソース（フォントまたは画像）として保存する必要がある外部リソースの処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコード内で行い、カスタムコードは引用符なしのパス（またはその他の文字列）を返す必要があります。その文字列は生成された HTML に組み込まれ、元の画像リソースの想定パスの代わりに使用されます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行されなければなりません。コンバータのコード内で結果を保存する処理は使用されません。もし、何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコード内で 'resourceSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これにより、コンバータは外部のカスタムコードがないかのように、そのリソースの処理に必要なすべての手順をコンバータ自身で実行することを示します。

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | リソースの保存に必要なデータの集合を表します |

### 戻り値

HTML の生成時に使用される、保存されたリソースへの URL を返す必要があります

### 関連項目

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


