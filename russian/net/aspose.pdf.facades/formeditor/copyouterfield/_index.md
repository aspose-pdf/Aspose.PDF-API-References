---
title: "FormEditor.CopyOuterField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Копирует существующее поле из одного PDF‑документа в другой документ с сохранением оригинального номера страницы и координат. Примечание: только для полей AcroForm, исключая переключатели."
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Копирует существующее поле из одного PDF‑документа в другой документ с оригинальным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Исходное полностью квалифицированное имя поля. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//копирует текстовое поле из source.pdf в PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и оригинальными координатами. Примечание: только для полей AcroForm (исключая переключатели).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Исходное полностью квалифицированное имя поля. |
| pageNum | Int32 | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | String | Исходное полностью квалифицированное имя поля. |
| pageNum | Int32 | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |
| абсцисса | Single | Абсцисса нового поля. Если -1, абсцисса будет равна исходной. |
| ордината | Single | Ордината нового поля. Если -1, ордината будет равна исходной. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


