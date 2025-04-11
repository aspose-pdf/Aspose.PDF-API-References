---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Rellena el campo con un valor válido de acuerdo con un nombre de campo completamente calificado. Antes de llenar los campos, deben conocerse todos los nombres de los campos y sus correspondientes valores válidos. Tanto el nombre de los campos como los valores son sensibles a mayúsculas y minúsculas. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit. Por ejemplo, si el campo tiene el nombre completo Form.Subform.TextField, debe especificar el nombre completo y no TextField. Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Rellena el campo con el valor especificado.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |
| value | String | Nuevo valor del campo |
| fitFontSize | Boolean | Si es verdadero, el tamaño de fuente en los cuadros de edición se ajustará. |

### Valor de Retorno

verdadero si se encontró el campo y se llenó con éxito.

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Rellena el campo con un valor válido de acuerdo con un nombre de campo completamente calificado. Antes de llenar los campos, deben conocerse todos los nombres de los campos y sus correspondientes valores válidos. Tanto el nombre de los campos como los valores son sensibles a mayúsculas y minúsculas. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField", debe especificar el nombre completo y no "TextField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo que se va a llenar. |
| fieldValue | String | El valor del campo que debe ser un valor válido para algunos campos. |

### Valor de Retorno

verdadero si se encuentra el campo y se llena con éxito.

## Ejemplos

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Rellena el campo de la casilla de radio con un valor de índice válido de acuerdo con un nombre de campo completamente calificado. Antes de llenar los campos, solo debe conocerse el nombre del campo. Mientras que el valor puede especificarse por su índice. Nota: Solo se aplica a campos de Casilla de Radio, Cuadro Combinado y Cuadro de Lista. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField", debe especificar el nombre completo y no "ListBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo que se va a llenar. |
| index | Int32 | Índice del elemento elegido. |

### Valor de Retorno

verdadero si se encontró el campo y se llenó con éxito.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Rellena el campo de la casilla de verificación con un valor booleano. Nota: Solo se aplica a la Casilla de Verificación. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField", debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo que se va a llenar. |
| beChecked | Boolean | Una bandera boolean: verdadero significa marcar la casilla, mientras que falso significa desmarcarla. |

### Valor de Retorno

verdadero si se encontró el campo y se llenó con éxito.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Rellena un campo con múltiples selecciones. Nota: solo para el campo de lista de AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado. |
| fieldValues | String[] | Un arreglo de cadenas que contiene varios elementos a seleccionar. |

## Ejemplos

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Rellena el campo con el valor especificado.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |
| value | String | Nuevo valor del campo |
| fitFontSize | Boolean | Si es verdadero, el tamaño de fuente en los cuadros de edición se ajustará. |

### Valor de Retorno

verdadero si se encontró el campo y se llenó con éxito.

### Véase También

* clase [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)