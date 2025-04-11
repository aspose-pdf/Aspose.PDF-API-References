---
title: Class GoToRemoteAction
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.GoToRemoteAction. Представляет собой удаленное действие перехода, которое похоже на обычное действие перехода, но переходит к месту назначения в другом PDF-файле вместо текущего файла
type: docs
weight: 1840
url: /ru/net/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class

Представляет собой удаленное действие перехода, которое похоже на обычное действие перехода, но переходит к месту назначения в другом PDF-файле вместо текущего файла.

```csharp
public sealed class GoToRemoteAction : GoToAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToRemoteAction](gotoremoteaction/#constructor)(string, ExplicitDestination) | Инициализирует объект GoToRemoteAction. |
| [GoToRemoteAction](gotoremoteaction/#constructor_1)(string, int) | Инициализирует объект GoToRemoteAction. |

## Properties

| Name | Description |
| --- | --- |
| override [Destination](../../aspose.pdf.annotations/gotoremoteaction/destination/) { get; set; } | Получает или задает место назначения для перехода. |
| [File](../../aspose.pdf.annotations/gotoremoteaction/file/) { get; set; } | Получает или задает спецификацию файла, в котором находится место назначения. |
| [NewWindow](../../aspose.pdf.annotations/gotoremoteaction/newwindow/) { get; set; } | Получает или задает флаг, указывающий, следует ли открывать документ назначения в новом окне. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Следующие действия в последовательности. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Получает строку для действия ECMAScript. |

### See Also

* class [GoToAction](../gotoaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)