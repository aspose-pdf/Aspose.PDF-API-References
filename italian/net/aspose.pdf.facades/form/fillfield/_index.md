---
title: "Form.FillField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Compila il campo con un valore valido in base a un nome di campo completamente qualificato. Prima di compilare i campi, è necessario conoscere tutti i nomi dei campi e i relativi valori validi. Sia il nome del campo che i valori sono sensibili al maiuscolo/minuscolo. Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit. Ad esempio, se un campo ha il nome completo Form.Subform.TextField, è necessario specificare il nome completo e non solo TextField. È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale."
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

Compila il campo con un valore valido in base a un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere tutti i nomi dei campi e i relativi valori validi. Sia il nome del campo che i valori sono sensibili al maiuscolo/minuscolo. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; ad esempio, se il campo ha il nome completo "Form.Subform.TextField" è necessario specificare il nome completo e non "TextField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo da compilare. |
| fieldValue | String | Il valore del campo, che deve essere un valore valido per alcuni campi. |

### Valore di ritorno

true se il campo è stato trovato e compilato con successo.

## Esempi

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//come cercare un campo per nome parziale:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Compila il campo radio box con un valore indice valido in base a un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere solo il nome del campo. Il valore può essere specificato tramite il suo indice. Nota: si applica solo ai campi Radio Box, Combo Box e List Box. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; ad esempio, se il campo ha il nome completo "Form.Subform.ListBoxField" è necessario specificare il nome completo e non "ListBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale.

```csharp
public bool FillField(string fieldName, int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo da compilare. |
| index | Int32 | Indice dell'elemento scelto. |

### Valore di ritorno

true se il campo è stato trovato e compilato con successo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//come cercare un campo per nome parziale:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Compila il campo casella di controllo con un valore booleano. Nota: si applica solo a Casella di Controllo. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo da compilare. |
| beChecked | Boolean | Un flag booleano: true indica di spuntare la casella, mentre false di deselezionarla. |

### Valore di ritorno

true se il campo è stato trovato e compilato con successo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//come cercare un campo per nome parziale:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Compila un campo con selezioni multiple. Nota: solo per il campo AcroForm List Box.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo. |
| fieldValues | String[] | Un array di stringhe che contiene diversi elementi da selezionare. |

## Esempi

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Compila il campo con il valore specificato.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo |
| valore | String | Nuovo valore del campo |
| fitFontSize | Boolean | Se true, la dimensione del carattere nelle caselle di modifica verrà adattata. |

### Valore di ritorno

true se il campo è stato trovato e compilato con successo.

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


