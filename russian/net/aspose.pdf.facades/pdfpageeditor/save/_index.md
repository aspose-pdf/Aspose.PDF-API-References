---
title: Save
second_title: Aspose.PDF для справочника API .NET
description: Сохраняет измененный документ в файл.
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
| outputFile | String | Путь к файлу, в котором будет сохранен документ. |

### Примеры

В следующем примере показано, как сохранить измененный PDF-документ

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Смотрите также

* class [PdfPageEditor](../../pdfpageeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfpageeditor)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Сохраняет измененный документ в поток.

```csharp
public override void Save(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранен измененный PDF-документ. |

### Примеры

В следующем примере показано, как сохранить измененный PDF-документ в поток.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Смотрите также

* class [PdfPageEditor](../../pdfpageeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfpageeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->