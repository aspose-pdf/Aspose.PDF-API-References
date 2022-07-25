---
title: FillField
second_title: Referencia de API de Aspose.PDF para .NET
description: Rellena el campo con el valor especificado.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Rellena el campo con el valor especificado.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |
| value | String | Nuevo valor del campo |
| fitFontSize | Boolean | Si es verdadero, se ajustará el tamaño de fuente en los cuadros de edición. |

### Valor_devuelto

verdadero si el campo se encontró y se llenó con éxito.

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Rellena el campo con un valor válido según un nombre de campo completo. Antes de rellenar los campos, se deben conocer los nombres de cada campo y sus correspondientes valores válidos. Tanto el nombre como los valores de los campos distinguen entre mayúsculas y minúsculas. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField", debe especificar el nombre completo y no "Campo de texto". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo a llenar. |
| fieldValue | String | El valor del campo que debe ser un valor válido para algunos campos. |

### Valor_devuelto

verdadero si el campo se encuentra y se completa con éxito.

### Ejemplos

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//cómo buscar un campo por su nombre parcial:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Rellena el campo de cuadro de radio con un valor de índice válido según un nombre de campo completo. Antes de rellenar los campos, solo se debe conocer el nombre del campo. Si bien el valor se puede especificar por su índice. Aviso: solo se aplica a los campos Radio Box, Combo Box y List Box. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField", debe especificar el nombre completo y no "ListBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo a llenar. |
| index | Int32 | Índice del artículo elegido. |

### Valor_devuelto

verdadero si el campo se encontró y se llenó con éxito.

### Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//cómo buscar un campo por su nombre parcial:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Rellena el campo de la casilla de verificación con un valor booleano. Aviso: solo se aplica a la casilla de verificación. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf .Kit; Por ejemplo, si el campo tiene el nombre completo "Formulario.Subformulario.CheckBoxField", debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo a llenar. |
| beChecked | Boolean | Una bandera booleana: verdadero significa marcar la casilla, mientras que falso para desmarcarla. |

### Valor_devuelto

verdadero si el campo se encontró y se llenó con éxito.

### Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//cómo buscar un campo por su nombre parcial:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Rellene un campo con varias selecciones. Nota: solo para el campo de cuadro de lista de AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completo. |
| fieldValues | String[] | Una matriz de cadenas que contiene varios elementos para seleccionar. |

### Ejemplos

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
