---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "この型のプロパティには、PDF から作成された SVG から抽出された画像の外部保存処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。"
type: docs
weight: 4730
url: /ja/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

この種のプロパティには、PDF から生成された SVG から抽出され、PDF から HTML への変換時に外部リソースとして保存される画像の外部保存処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの独自保存などの処理はカスタムコードで行い、カスタムコードはパス（または引用符なしの任意の文字列）を返す必要があります。そのパスは、元の画像リソースへの想定パスの代わりに生成された SVG に組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行しなければなりません。なぜかコンバータのコード自体で処理する必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'imageSavingInfo' パラメータの変数に設定してください。これにより、外部カスタムコードがないかのように、リソースの処理に必要なすべての手順がコンバータ側で実行されることをコンバータに通知します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
