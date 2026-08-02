---
title: "PdfPageEditor.Zoom"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfPageEditor. Получает или задаёт коэффициент масштабирования. Значение 1.0 соответствует 100. Значение по умолчанию — 1.0.  Следующий пример демонстрирует, как изменить масштаб страниц документа"
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom property

Получает или задает коэффициент масштабирования. Значение 1.0 соответствует 100 %. Значение по умолчанию — 1.0. Ниже приведён пример, демонстрирующий, как изменить масштаб страниц Document.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


