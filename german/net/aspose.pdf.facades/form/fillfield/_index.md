---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen. Bevor die Felder gefüllt werden, müssen alle Feldnamen und die entsprechenden gültigen Werte bekannt sein. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert. Zum Beispiel, wenn das Feld den vollständigen Namen Form.Subform.TextField hat, sollten Sie den vollständigen Namen angeben und nicht TextField. Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen.
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Füllt das Feld mit dem angegebenen Wert.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes |
| value | String | Neuer Wert des Feldes |
| fitFontSize | Boolean | Wenn wahr, wird die Schriftgröße in den Eingabefeldern angepasst. |

### Rückgabewert

true, wenn das Feld gefunden und erfolgreich gefüllt wurde.

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen. Bevor die Felder gefüllt werden, müssen alle Feldnamen und die entsprechenden gültigen Werte bekannt sein. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Zum Beispiel, wenn das Feld den vollständigen Namen "Form.Subform.TextField" hat, sollten Sie den vollständigen Namen angeben und nicht "TextField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der Name des zu füllenden Feldes. |
| fieldValue | String | Der Wert des Feldes, der ein gültiger Wert für einige Felder sein muss. |

### Rückgabewert

true, wenn das Feld gefunden und erfolgreich gefüllt wurde.

## Beispiele

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

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Füllt das Auswahlfeld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. Bevor die Felder gefüllt werden, muss nur der Name des Feldes bekannt sein. Während der Wert durch seinen Index angegeben werden kann. Hinweis: Nur an Radio Box-, Combo Box- und List Box-Feldern anwendbar. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Zum Beispiel, wenn das Feld den vollständigen Namen "Form.Subform.ListBoxField" hat, sollten Sie den vollständigen Namen angeben und nicht "ListBoxField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des zu füllenden Feldes. |
| index | Int32 | Index des gewählten Elements. |

### Rückgabewert

true, wenn das Feld gefunden und erfolgreich gefüllt wurde.

## Beispiele

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

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Nur an Check Box anwendbar. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Zum Beispiel, wenn das Feld den vollständigen Namen "Form.Subform.CheckBoxField" hat, sollten Sie den vollständigen Namen angeben und nicht "CheckBoxField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der Name des zu füllenden Feldes. |
| beChecked | Boolean | Ein boolesches Flag: wahr bedeutet, das Kästchen zu aktivieren, während falsch bedeutet, es zu deaktivieren. |

### Rückgabewert

true, wenn das Feld gefunden und erfolgreich gefüllt wurde.

## Beispiele

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

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Füllt ein Feld mit mehreren Auswahlmöglichkeiten. Hinweis: nur für AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname. |
| fieldValues | String[] | Ein String-Array, das mehrere auszuwählende Elemente enthält. |

## Beispiele

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

Füllt das Feld mit dem angegebenen Wert.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes |
| value | String | Neuer Wert des Feldes |
| fitFontSize | Boolean | Wenn wahr, wird die Schriftgröße in den Eingabefeldern angepasst. |

### Rückgabewert

true, wenn das Feld gefunden und erfolgreich gefüllt wurde.

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)