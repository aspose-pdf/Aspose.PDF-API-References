---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Справочник API Aspose.PDF для Java"
description: "Предоставляет данные для события PdfViewer.getCustomPrintDelegate()."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

Предоставляет данные для события PdfViewer.getCustomPrintDelegate().

## Поля

| Поле | Описание |
| --- | --- |
| [FileName](#FileName) | Получает имя файла, который печатается. |
| [PageSettings](#PageSettings) | Получает настройки, которые должны применяться к каждой странице документа. |
| [PrinterSettings](#PrinterSettings) | Получает информацию о принтере, на котором должен быть распечатан документ. |

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Инициализирует {@link CustomPrintEventArgs} с указанным принтером и настройками страницы. |

### FileName {#FileName}
```
public final String FileName
```

Получает имя файла, который печатается.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

Получает настройки, которые должны применяться к каждой странице документа.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

Получает информацию о принтере, на котором должен быть распечатан документ.

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
Инициализирует {@link CustomPrintEventArgs} с указанным принтером и настройками страницы.
