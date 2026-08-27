---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SvgSaveOptions フィールド。このフィールドは、変換中に存在する場合に使用される保存戦略を含めることができ、作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理します。その戦略はリソースを処理し、生成された SVG で保存されたリソースの望ましい URI を表す文字列を返す必要があります。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータのコード自体で行う必要がある場合は、カスタムコードフラグ CustomProcessingCancelled を imageSavingInfo パラメータ変数に設定してください。これは、外部カスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身で実行することをコンバータに通知します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。その戦略はリソースを処理し、生成された SVG 内で保存されたリソースの望ましい URI を表す文字列を返す必要があります。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコードで 'imageSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これは、外部のカスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身が実行することをコンバータに通知します。

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 関連項目

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


