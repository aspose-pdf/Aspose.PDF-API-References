---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Вставляет изображение в существующее поле кнопки в качестве его внешнего вида в соответствии с его полным именем поля
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Вставляет изображение в существующее поле кнопки в качестве его внешнего вида в соответствии с его полным именем поля.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля кнопки изображения. |
| imageFileName | String | Путь к файлу изображения, относительный и абсолютный оба допустимы. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Перегружает функцию FillImageField. Входные данные - поток изображения.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| imageStream | Stream | Поток изображения. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)