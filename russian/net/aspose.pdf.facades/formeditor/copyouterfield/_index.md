---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Копирует существующее поле из одного PDF-документа в другой документ с оригинальным номером страницы и координатами. Обратите внимание: только для полей AcroForm.
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Копирует существующее поле из одного PDF-документа в другой документ с оригинальным номером страницы и координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF-документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Оригинальное полное имя поля. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Копирует существующее поле из одного PDF-документа в другой документ с указанным номером страницы и оригинальными координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF-документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Оригинальное полное имя поля. |
| pageNum | Int32 | Номер страницы, на которой будет находиться новое поле. Если -1, новое поле будет скопировано на ту же страницу, на которой находилось старое. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Копирует существующее поле из одного PDF-документа в другой документ с указанным номером страницы и координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF-документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Оригинальное полное имя поля. |
| pageNum | Int32 | Номер страницы, на которой будет находиться новое поле. Если -1, новое поле будет скопировано на ту же страницу, на которой находилось старое. |
| abscissa | Single | Абсцисса нового поля. Если -1, абсцисса будет равна оригинальной. |
| ordinate | Single | Ордината нового поля. Если -1, ордината будет равна оригинальной. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)