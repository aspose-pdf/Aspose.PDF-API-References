---
title: DecorateField
second_title: Aspose.PDF per .NET API Reference
description: Modifica gli attributi visivi del campo specificato.
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/formeditor/decoratefield/
---
## DecorateField(string) {#decoratefield_2}

Modifica gli attributi visivi del campo specificato.

```csharp
public void DecorateField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completo. |

### Esempi

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato.

```csharp
public void DecorateField(FieldType fieldType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldType | FieldType | Tipo di campi che verranno decorati. |

### Esempi

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//come cercare il campo in base al suo nome parziale:
fe.DecorateField(FieldType.Text);
```

### Guarda anche

* enum [FieldType](../../fieldtype)
* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

Modifica gli attributi visivi di tutti i campi nel documento PDF.

```csharp
public void DecorateField()
```

### Esempi

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//Crea una copia del campo di testo nella pagina psecond.
fe.DecorateField();
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
