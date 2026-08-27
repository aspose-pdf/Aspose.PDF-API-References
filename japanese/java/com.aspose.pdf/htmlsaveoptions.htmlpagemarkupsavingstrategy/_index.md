---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "変換の結果は、1つまたは複数の HTML ページを含むことがあります（画像やフォントなどの外部ファイルを参照することもできます）。このプロパティには、作成されたデリゲートを割り当てることができます。"
type: docs
weight: 2110
url: /ja/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

変換結果には1つまたは複数のHTMLページ（画像やフォントなどの外部ファイルを参照できる場合もあります）が含まれる可能性があります。このプロパティには、変換中に作成されたHTMLページ（HTML自体）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができます。この場合、HTMLページのマークアップの保存に必要なすべての操作は提供されたメソッドのコード内で実行する必要があります。なぜかコンバータのコード自体で処理を行う必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'htmlSavingInfo' パラメータの変数に設定してください。このフラグは、外部のカスタム保存コードがないかのように、コンバータ自身でそのリソースの処理に必要なすべての手順を実行するようコンバータに指示します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | 内部 beginInvoke メソッド |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | 内部 endInvoke メソッド |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | 呼び出されたメソッド |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
内部 beginInvoke メソッド

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
内部 endInvoke メソッド

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
呼び出されたメソッド
