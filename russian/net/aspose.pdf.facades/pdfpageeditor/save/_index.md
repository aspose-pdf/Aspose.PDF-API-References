---
title: "PdfPageEditor.Save"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfPageEditor. Сохраняет изменённый Document в файл"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Сохраняет изменённый Document в файл.

```csharp
public override void Save(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь к файлу, в котором будет сохранён документ. |

## Примеры

Следующий пример демонстрирует, как сохранить изменённый PDF‑документ

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Сохраняет изменённый Document в поток.

```csharp
public override void Save(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранён изменённый PDF‑документ. |

## Примеры

Следующий пример демонстрирует, как сохранить изменённый PDF‑документ в поток.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


