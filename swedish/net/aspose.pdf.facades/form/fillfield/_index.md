---
title: FillField
second_title: Aspose.PDF för .NET API Referens
description: Fyller fältet med angivet värde.
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Fyller fältet med angivet värde.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn |
| value | String | Nytt värde på fältet |
| fitFontSize | Boolean | Om det är sant kommer teckenstorleken i redigeringsrutorna att anpassas. |

### Returvärde

sant om fältet hittades och har fyllts i.

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Fyller fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan du fyller i fälten måste varje fälts namn och dess motsvarande giltiga värden vara kända. Både fältens namn och värden är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades stöder endast fullständiga fältnamn och fungerar inte med partiella fältnamn i motsats till Aspose.Pdf.Kit; Om t.ex. fältet har fullständigt namn "Form.Subform.TextField" ska du ange fullständigt namn och inte "Textfält". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn som ska fyllas i. |
| fieldValue | String | Fältets värde som måste vara ett giltigt värde för vissa fält. |

### Returvärde

sant om fältet hittas och fylls i.

### Exempel

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//hur man söker i fältet efter dess delnamn:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Fyller radioboxfältet med ett giltigt indexvärde enligt ett fullt kvalificerat fältnamn. Innan du fyller i fälten måste endast fältets namn vara känt. Medan värdet kan specificeras av dess index. Observera: Används endast för radiobox-, kombinationsbox- och listboxfält. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella -fältnamn i motsats till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.ListBoxField" ska du ange fullständigt namn och inte "ListBoxField". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fält som ska fyllas i. |
| index | Int32 | Index över valt objekt. |

### Returvärde

sant om fältet hittades och har fyllts i.

### Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//hur man söker i fältet efter dess delnamn:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Fyller kryssrutan med ett booleskt värde. Observera: Används endast för kryssrutan. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella -fältnamn i motsats till Aspose.Pdf .Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.CheckBoxField" bör du ange fullständigt namn och inte "CheckBoxField". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn som ska fyllas i. |
| beChecked | Boolean | En boolesk flagga: sant betyder att markera rutan, medan false att avmarkera den. |

### Returvärde

sant om fältet hittades och har fyllts i.

### Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//hur man söker i fältet efter dess delnamn:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Fyll ett fält med flera val. Notera: endast för AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullt kvalificerade fältnamnet. |
| fieldValues | String[] | En strängarray som innehåller flera objekt som ska väljas. |

### Exempel

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
