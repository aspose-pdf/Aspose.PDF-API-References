---
title: FormEditor.DecorateField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Изменяет визуальные атрибуты указанного поля
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
| fieldName | String | Полное имя поля. |

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

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

Изменяет визуальные атрибуты всех полей с указанным типом поля.

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
//decorate all text fields.
fe.DecorateField(FieldType.Text);
```

### См. также

* перечисление [FieldType](../../fieldtype/)
* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

Изменяет визуальные атрибуты всех полей в PDF документе.

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
//decorate all fields.
fe.DecorateField();
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)