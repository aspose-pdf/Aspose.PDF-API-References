---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Fyller fältet med ett giltigt värde enligt ett fullt kvalificerat fältnamn. Innan fälten fylls måste varje fältnamn och dess motsvarande giltiga värden vara kända. Både fältnamn och värden är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med delvisa fältnamn i kontrast till Aspose.Pdf.Kit. Till exempel, om fältet har fullständigt namn Form.Subform.TextField bör du ange fullständigt namn och inte TextField. Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter erforderligt fält med dess delvisa namn.
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Fyller fältet med angivet värde.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fält |
| value | Sträng | Nytt värde för fältet |
| fitFontSize | Boolean | Om sant, kommer teckenstorleken i redigeringsrutorna att anpassas. |

### Returvärde

sant om fältet hittades och framgångsrikt fylldes.

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Fyller fältet med ett giltigt värde enligt ett fullt kvalificerat fältnamn. Innan fälten fylls måste varje fältnamn och dess motsvarande giltiga värden vara kända. Både fältnamn och värden är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.TextField" bör du ange fullständigt namn och inte "TextField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter erforderligt fält med dess delvisa namn.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namnet på fältet som ska fyllas. |
| fieldValue | Sträng | Värdet för fältet som måste vara ett giltigt värde för vissa fält. |

### Returvärde

sant om fältet hittas och fylls framgångsrikt.

## Exempel

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

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Fyller radioknappfältet med ett giltigt indexvärde enligt ett fullt kvalificerat fältnamn. Innan fälten fylls måste endast fältnamnet vara känt. Värdet kan anges med sitt index. Observera: Endast tillämpligt på Radioknapp, Kombinationsruta och Listboxfält. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.ListBoxField" bör du ange fullständigt namn och inte "ListBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter erforderligt fält med dess delvisa namn.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fältet som ska fyllas. |
| index | Int32 | Index för valt objekt. |

### Returvärde

sant om fältet hittades och framgångsrikt fylldes.

## Exempel

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

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Fyller kryssrutan med ett booleanvärde. Observera: Endast tillämpligt på Kryssruta. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.CheckBoxField" bör du ange fullständigt namn och inte "CheckBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter erforderligt fält med dess delvisa namn.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namnet på fältet som ska fyllas. |
| beChecked | Boolean | En booleanflagga: sant betyder att kryssrutan ska kryssas, medan falskt betyder att den ska avmarkeras. |

### Returvärde

sant om fältet hittades och framgångsrikt fylldes.

## Exempel

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

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Fyll ett fält med flera val. Observera: endast för AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullt kvalificerade fältnamnet. |
| fieldValues | Sträng[] | En strängarray som innehåller flera objekt som ska väljas. |

## Exempel

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

Fyller fältet med angivet värde.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fält |
| value | Sträng | Nytt värde för fältet |
| fitFontSize | Boolean | Om sant, kommer teckenstorleken i redigeringsrutorna att anpassas. |

### Returvärde

sant om fältet hittades och framgångsrikt fylldes.

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)