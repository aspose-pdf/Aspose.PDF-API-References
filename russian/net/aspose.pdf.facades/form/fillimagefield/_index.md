---
title: "Form.FillImageField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Вставляет изображение в существующее поле‑кнопку в качестве его внешнего вида в соответствии с полностью квалифицированным именем поля."
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Вставляет изображение в существующее поле кнопки в качестве его внешнего вида в соответствии с полностью квалифицированным именем поля.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля кнопки изображения. |
| imageFileName | String | Путь к файлу изображения, относительный и абсолютный оба подходят. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Перегружает функцию FillImageField. Входные данные — поток изображения.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля. |
| imageStream | Stream | Поток изображения. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


