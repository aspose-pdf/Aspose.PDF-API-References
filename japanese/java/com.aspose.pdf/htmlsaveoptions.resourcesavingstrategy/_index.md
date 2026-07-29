---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このプロパティには、PDF から抽出され保存が必要な外部リソース（フォントまたは画像）の処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。"
type: docs
weight: 2150
url: /ja/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

このプロパティには、PDFからHTMLへの変換中に抽出され外部リソース（フォントまたは画像）として保存する必要があるリソースの処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができ、カスタムコードはパス（引用符なしの任意の文字列）を返す必要があります。そのパスは、生成されたHTMLに元の画像リソースのパスの代わりに組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行する必要があります。なぜかコンバータのコード自体で処理を行う必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'resourceSavingInfo' パラメータの変数に設定してください。このフラグは、外部のカスタムコードがないかのように、コンバータ自身でそのリソースの処理に必要なすべての手順を実行するようコンバータに指示します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | 呼び出されたメソッド |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
呼び出されたメソッド
