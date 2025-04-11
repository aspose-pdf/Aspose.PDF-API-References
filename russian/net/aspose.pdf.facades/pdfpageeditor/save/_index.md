---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Сохраняет измененный документ в файл
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Сохраняет измененный документ в файл.

```csharp
public override void Save(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь к файлу, в который будет сохранен документ. |

## Примеры

Следующий пример демонстрирует, как сохранить измененный PDF документ

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Сохраняет измененный документ в поток.

```csharp
public override void Save(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будет сохранен измененный PDF документ. |

## Примеры

Следующий пример демонстрирует, как сохранить измененный PDF документ в поток.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)