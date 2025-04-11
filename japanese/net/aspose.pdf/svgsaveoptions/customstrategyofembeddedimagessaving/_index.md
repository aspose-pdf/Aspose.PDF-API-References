---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions フィールド。このフィールドには、保存戦略が含まれる場合があり、保存された SVG に埋め込まれた BMP または JPEG のような作成された参照外部画像ファイルのカスタマイズされた処理のために変換中に使用される必要があります。その戦略はリソースを処理し、生成された SVG に保存されたリソースの望ましい URI を表す文字列を返す必要があります。このファイルの処理が何らかの理由でカスタムコードではなくコンバーターのコード自体によって行われる必要がある場合は、カスタムコード内で 'imageSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これは、リソースの処理に必要なすべてのステップが外部のカスタムコードがないかのようにコンバーター自体で行われる必要があることをコンバーターに通知します。
type: docs
weight: 30
url: /ja/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving フィールド

このフィールドには、保存された SVG に埋め込まれた BMP または JPEG のような作成された参照外部画像ファイルのカスタマイズされた処理のために変換中に使用される必要がある保存戦略が含まれる場合があります。その戦略はリソースを処理し、生成された SVG に保存されたリソースの望ましい URI を表す文字列を返す必要があります。このファイルの処理が何らかの理由でカスタムコードではなくコンバーターのコード自体によって行われる必要がある場合は、カスタムコード内で 'imageSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これは、リソースの処理に必要なすべてのステップが外部のカスタムコードがないかのようにコンバーター自体で行われる必要があることをコンバーターに通知します。

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 関連項目

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)