---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Aspose.PDF for Java API 参考"
description: "为 PdfViewer.getCustomPrintDelegate() 事件提供数据。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

为 PdfViewer.getCustomPrintDelegate() 事件提供数据。

## 字段

| 字段 | 描述 |
| --- | --- |
| [FileName](#FileName) | 获取正在打印的文件的名称。 |
| [PageSettings](#PageSettings) | 获取应应用于文档每页的设置。 |
| [PrinterSettings](#PrinterSettings) | 获取有关文档应打印到的打印机的信息。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | 使用给定的打印机和页面设置初始化 {@link CustomPrintEventArgs}。 |

### FileName {#FileName}
```
public final String FileName
```

获取正在打印的文件的名称。

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

获取应应用于文档每页的设置。

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

获取有关文档应打印到的打印机的信息。

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
使用给定的打印机和页面设置初始化 {@link CustomPrintEventArgs}。
