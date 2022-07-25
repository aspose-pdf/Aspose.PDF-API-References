---
title: FillField
second_title: Aspose.PDF für .NET-API-Referenz
description: Füllt das Feld mit dem angegebenen Wert.
type: docs
weight: 160
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
| fitFontSize | Boolean | Wenn wahr, wird die Schriftgröße in den Bearbeitungsfeldern angepasst. |

### Rückgabewert

wahr, wenn das Feld gefunden und erfolgreich ausgefüllt wurde.

### Siehe auch

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Füllt das Feld mit einem gültigen Wert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder müssen die Namen aller Felder und die entsprechenden gültigen Werte bekannt sein. Bei Feldnamen und -werten wird zwischen Groß- und Kleinschreibung unterschieden. Bitte beachten Sie dies Aspose.Pdf.Facades unterstützt nur vollständige Feldnamen und arbeitet nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit; Wenn das Feld beispielsweise den vollständigen Namen "Form.Subform.TextField" hat, sollten Sie den vollständigen Namen angeben und nicht "Textfeld". Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu durchsuchen.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der auszufüllende Feldname. |
| fieldValue | String | Der Wert des Felds, der für einige Felder ein gültiger Wert sein muss. |

### Rückgabewert

wahr, wenn das Feld erfolgreich gefunden und gefüllt wird.

### Beispiele

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//Wie man das Feld nach seinem Teilnamen sucht:
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

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Füllt das Radiobox-Feld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. Vor dem Füllen der Felder muss nur der Feldname bekannt sein. Während der Wert durch seinen Index angegeben werden kann. Hinweis: Nur auf Radio Box-, Combo Box- und List Box-Felder anwenden. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit unvollständigen -Feldnamen arbeitet im Gegensatz zu Aspose.Pdf.Kit; Wenn das Feld beispielsweise den vollständigen Namen "Form.Subform.ListBoxField" hat, sollten Sie den vollständigen Namen und nicht "ListBoxField" angeben. Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu durchsuchen.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des auszufüllenden Feldes. |
| index | Int32 | Index des ausgewählten Artikels. |

### Rückgabewert

wahr, wenn das Feld gefunden und erfolgreich ausgefüllt wurde.

### Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//Wie man das Feld nach seinem Teilnamen sucht:
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

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Nur auf Kontrollkästchen anwenden. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf nicht mit teilweisen Feldnamen arbeitet .Kit; Wenn das Feld beispielsweise den vollständigen Namen „Form.Subform.CheckBoxField“ hat, sollten Sie den vollständigen Namen und nicht „CheckBoxField“ angeben. Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu suchen.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der auszufüllende Feldname. |
| beChecked | Boolean | Ein boolesches Flag: „true“ bedeutet, dass das Kontrollkästchen aktiviert wird, „false“, um es zu deaktivieren. |

### Rückgabewert

wahr, wenn das Feld gefunden und erfolgreich ausgefüllt wurde.

### Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//Wie man das Feld nach seinem Teilnamen sucht:
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

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Füllen Sie ein Feld mit Mehrfachauswahl.Hinweis: nur für AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollständig qualifizierte Feldname. |
| fieldValues | String[] | Ein String-Array, das mehrere auszuwählende Elemente enthält. |

### Beispiele

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Siehe auch

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
