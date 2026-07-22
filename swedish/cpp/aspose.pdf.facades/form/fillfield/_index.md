---
title: "Aspose::Pdf::Facades::Form::FillField‑metod"
linktitle: "FillField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::Form::FillField‑metod. Fyller kryssrutan med ett booleskt värde. Obs: Kan endast tillämpas på kryssruta. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet \\\"Form.Subform.CheckBoxField\\\" ska du ange det fullständiga namnet och inte \\\"CheckBoxField\\\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet via dess partiella namn i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/form/fillfield/
---
## Form::FillField(const System::String\&, bool) method


Fyller kryssrutan med ett booleskt värde. Obs: Kan endast tillämpas på kryssruta. Observera att [Aspose.Pdf.Facades](../../) endast stöder fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet \"Form.Subform.CheckBoxField\" ska du ange det fullständiga namnet och inte \"CheckBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet via dess partiella namn.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, bool beChecked)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Fältets namn som ska fyllas i. |
| beChecked | bool | En boolesk flagga: true betyder att kryssrutan ska markeras, medan false betyder att den ska avmarkeras. |

### ReturnValue

true om fältet hittades och fylldes framgångsrikt.

## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::ArrayPtr\<System::String\>\&) method


Fyll i ett fält med flera val. Obs: endast för AcroForm List Box-fält.

```cpp
void Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::ArrayPtr<System::String> &fieldValues)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Det fullständigt kvalificerade fältnamnet. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | En strängarray som innehåller flera objekt att välja. |

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&) method


Fyller fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste alla fältnamnen och deras motsvarande giltiga värden vara kända. Både fältnamnen och värdena är skiftlägeskänsliga. Observera att [Aspose.Pdf.Facades](../../) endast stöder fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet \"Form.Subform.TextField\" ska du ange det fullständiga namnet och inte \"TextField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet via dess partiella namn.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &fieldValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Fältets namn som ska fyllas i. |
| fieldValue | const System::String\& | Fältets värde som måste vara ett giltigt värde för vissa fält. |

### ReturnValue

true om fältet hittas och fylls i framgångsrikt.

## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&, bool) method


Fyller fältet med angivet värde.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &value, bool fitFontSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Fältets namn |
| värde | const System::String\& | Nytt värde för fältet |
| fitFontSize | bool | Om true kommer teckenstorleken i redigeringsrutorna att anpassas. |

### ReturnValue

true om fältet hittades och fylldes framgångsrikt.

## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, int32_t) method


Fyller radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan specificeras med sitt index. Obs: Kan endast tillämpas på radioknappar, kombinationsrutor och listboxar. Observera att [Aspose.Pdf.Facades](../../) endast stöder fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet \"Form.Subform.ListBoxField\" ska du ange det fullständiga namnet och inte \"ListBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet via dess partiella namn.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, int32_t index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Namn på fältet som ska fyllas i. |
| index | int32_t | Index för valt objekt. |

### ReturnValue

true om fältet hittades och fylldes framgångsrikt.
## Anmärkningar




```cpp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```cpp
//hur man söker fältet via dess partiella namn:
Form form = new Form("input.pdf", "output.pdf");
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
