---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PdfViewer.getCustomPrintDelegate() イベントに対するデータを提供します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

PdfViewer.getCustomPrintDelegate() イベントに対するデータを提供します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [FileName](#FileName) | 印刷中のファイル名を取得します。 |
| [PageSettings](#PageSettings) | ドキュメントの各ページに適用すべき設定を取得します。 |
| [PrinterSettings](#PrinterSettings) | ドキュメントが印刷されるプリンターに関する情報を取得します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | 指定されたプリンターとページ設定で {@link CustomPrintEventArgs} を初期化します。 |

### FileName {#FileName}
```
public final String FileName
```

印刷中のファイル名を取得します。

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

ドキュメントの各ページに適用すべき設定を取得します。

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

ドキュメントが印刷されるプリンターに関する情報を取得します。

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
指定されたプリンターとページ設定で {@link CustomPrintEventArgs} を初期化します。
