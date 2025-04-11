---
title: FormEditor.DecorateField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Belirtilen alanın görsel özelliklerini değiştirir
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/formeditor/decoratefield/
---
## DecorateField(string) {#decoratefield_2}

Belirtilen alanın görsel özelliklerini değiştirir.

```csharp
public void DecorateField(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |

## Örnekler

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

Belirtilen alan türüne sahip tüm alanların görsel özelliklerini değiştirir.

```csharp
public void DecorateField(FieldType fieldType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldType | FieldType | Süslenilecek alanların türü. |

## Örnekler

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

### Ayrıca Bakınız

* enum [FieldType](../../fieldtype/)
* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

PDF belgesindeki tüm alanların görsel özelliklerini değiştirir.

```csharp
public void DecorateField()
```

## Örnekler

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

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)