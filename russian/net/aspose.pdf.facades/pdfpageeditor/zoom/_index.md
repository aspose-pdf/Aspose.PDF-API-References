---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfPageEditor. Получает или устанавливает коэффициент масштабирования. Значение 1.0 соответствует 100%. Значение по умолчанию - 1.0. Следующий пример демонстрирует, как изменить масштаб страниц документа.
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## Свойство PdfPageEditor.Zoom

Получает или устанавливает коэффициент масштабирования. Значение 1.0 соответствует 100%. Значение по умолчанию - 1.0. Следующий пример демонстрирует, как изменить масштаб страниц документа.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)