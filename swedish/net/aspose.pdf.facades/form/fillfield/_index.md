---
title: "Form.FillField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Fyller fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls måste alla fältnamn och deras motsvarande giltiga värden vara kända. Både fältnamnen och värdena är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit. Till exempel, om fältet har det fullständiga namnet Form.Subform.TextField bör du ange hela namnet och inte TextField. Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det erforderliga fältet med dess partiella namn."
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

Fyller i fältet med ett giltigt värde enligt ett fullständigt fältnamn. Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända. Både fältnamnen och värdena är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.TextField" ska du ange det fullständiga namnet och inte "TextField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn som ska fyllas i. |
| fieldValue | String | Fältets värde som måste vara ett giltigt värde för vissa fält. |

### Returvärde

true om fältet hittas och fylls i framgångsrikt.

## Exempel

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//hur man söker fält efter dess partiella namn:
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan anges med dess index. Obs: Gäller endast för radioknappar, kombinationsrutor och listrutor. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.ListBoxField" ska du ange det fullständiga namnet och inte "ListBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet som ska fyllas i. |
| index | Int32 | Index för valt objekt. |

### Returvärde

true om fältet hittades och fyllts i framgångsrikt.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//hur man söker fält efter dess partiella namn:
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Fyller i kryssrutan med ett booleskt värde. Obs: Gäller endast för kryssruta. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.CheckBoxField" ska du ange det fullständiga namnet och inte "CheckBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn som ska fyllas i. |
| beChecked | Boolean | En boolesk flagga: true betyder att kryssa i rutan, medan false betyder att avmarkera den. |

### Returvärde

true om fältet hittades och fyllts i framgångsrikt.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//hur man söker fält efter dess partiella namn:
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Fyll ett fält med flera val. Obs: endast för AcroForm-listruta.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet. |
| fieldValues | String[] | En strängarray som innehåller flera objekt att välja. |

## Exempel

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Fyller fältet med angivet värde.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn |
| värde | String | Nytt värde för fältet |
| fitFontSize | Boolean | Om true kommer teckenstorleken i redigeringsrutorna att anpassas. |

### Returvärde

true om fältet hittades och fyllts i framgångsrikt.

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


