---
title: FillImageField
second_title: Aspose.PDF для справочника API .NET
description: Вставляет изображение в существующее поле кнопки в качестве внешнего вида в соответствии с его полным именем поля.
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Вставляет изображение в существующее поле кнопки в качестве внешнего вида в соответствии с его полным именем поля.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля кнопки изображения. |
| imageFileName | String | Путь к файлу изображения, относительный и абсолютный, в порядке. |

### Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Перегружает функцию FillImageField. Ввод представляет собой поток изображений.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| imageStream | Stream | Поток изображения. |

### Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
