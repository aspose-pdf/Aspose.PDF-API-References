---
title: "FormEditor.DecorateField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод FormEditor. Изменяет визуальные атрибуты указанного поля"
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/formeditor/decoratefield/
---
## DecorateField(string) {#decoratefield_2}

Изменяет визуальные атрибуты указанного поля.

```csharp
public void DecorateField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля. |

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

Изменяет визуальные атрибуты всех полей указанного типа.

```csharp
public void DecorateField(FieldType fieldType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | FieldType | Тип полей, которые будут оформлены. |

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//оформить все текстовые поля.
fe.DecorateField(FieldType.Text);
```

### См. также

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

Изменяет визуальные атрибуты всех полей в PDF‑документе.

```csharp
public void DecorateField()
```

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//оформить все поля.
fe.DecorateField();
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


