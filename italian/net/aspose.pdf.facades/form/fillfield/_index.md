---
title: FillField
second_title: Aspose.PDF per .NET API Reference
description: Riempie il campo con il valore specificato.
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Riempie il campo con il valore specificato.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo |
| value | String | Nuovo valore del campo |
| fitFontSize | Boolean | Se true, la dimensione del carattere nelle caselle di modifica verrà adattata. |

### Valore di ritorno

true se il campo è stato trovato e compilato correttamente.

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Riempie il campo con un valore valido in base a un nome di campo completo. Prima di compilare i campi, è necessario conoscere i nomi di ogni campo e i relativi valori validi corrispondenti. Sia il nome che i valori dei campi fanno distinzione tra maiuscole e minuscole. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf.Kit; Ad esempio se il campo ha il nome completo "Form.Subform.TextField" è necessario specificare il nome completo e non "Campo di testo". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo da compilare. |
| fieldValue | String | Il valore del campo che deve essere un valore valido per alcuni campi. |

### Valore di ritorno

true se il campo viene trovato e compilato correttamente.

### Esempi

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
Way1: utilizzo diretto del privilegio predefinito.
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Riempie il campo della casella radio con un valore di indice valido in base a un nome di campo completo. Prima di compilare i campi, è necessario conoscere solo il nome del campo. Sebbene il valore possa essere specificato dal relativo indice. Avviso: applicabile solo ai campi Radio Box, Combo Box e List Box. Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf.Kit; Ad esempio se il campo ha il nome completo "Form.Subform.ListBoxField" è necessario specificare il nome completo e non "ListBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale.

```csharp
public bool FillField(string fieldName, int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo da compilare. |
| index | Int32 | Indice dell'elemento scelto. |

### Valore di ritorno

true se il campo è stato trovato e compilato correttamente.

### Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
Way2: Basato su un privilegio predefinito e modifica alcune autorizzazioni specifiche.
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Riempie il campo della casella di controllo con un valore booleano. Avviso: applicabile solo alla casella di controllo. Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf .Kit; Ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo da compilare. |
| beChecked | Boolean | Un flag booleano: true significa selezionare la casella, mentre false per deselezionarla. |

### Valore di ritorno

true se il campo è stato trovato e compilato correttamente.

### Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
Way3: basato su un privilegio predefinito e modifica alcune combinazioni di autorizzazioni Adobe Professional specifiche.
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Compila un campo con selezioni multiple. Nota: solo per il campo Casella di riepilogo AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completo. |
| fieldValues | String[] | Un array di stringhe che contiene diversi elementi da selezionare. |

### Esempi

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
