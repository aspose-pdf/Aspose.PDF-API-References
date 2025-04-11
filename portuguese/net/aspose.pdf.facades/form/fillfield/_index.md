---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, todos os nomes dos campos e seus valores válidos correspondentes devem ser conhecidos. Tanto o nome dos campos quanto os valores são sensíveis a maiúsculas e minúsculas. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, em contraste com Aspose.Pdf.Kit. Por exemplo, se o campo tiver o nome completo Form.Subform.TextField, você deve especificar o nome completo e não TextField. Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial.
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Preenche o campo com o valor especificado.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo |
| value | String | Novo valor do campo |
| fitFontSize | Boolean | Se verdadeiro, o tamanho da fonte nas caixas de edição será ajustado. |

### Valor de Retorno

verdadeiro se o campo foi encontrado e preenchido com sucesso.

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, todos os nomes dos campos e seus valores válidos correspondentes devem ser conhecidos. Tanto o nome dos campos quanto os valores são sensíveis a maiúsculas e minúsculas. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, em contraste com Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.TextField", você deve especificar o nome completo e não "TextField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo a ser preenchido. |
| fieldValue | String | O valor do campo que deve ser um valor válido para alguns campos. |

### Valor de Retorno

verdadeiro se o campo for encontrado e preenchido com sucesso.

## Exemplos

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

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Preenche o campo da caixa de seleção com um valor de índice válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, apenas o nome do campo deve ser conhecido. Enquanto o valor pode ser especificado pelo seu índice. Aviso: Apenas aplicável a campos de Caixa de Seleção, Caixa de Combinação e Caixa de Lista. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, em contraste com Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.ListBoxField", você deve especificar o nome completo e não "ListBoxField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial.

```csharp
public bool FillField(string fieldName, int index)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo a ser preenchido. |
| index | Int32 | Índice do item escolhido. |

### Valor de Retorno

verdadeiro se o campo foi encontrado e preenchido com sucesso.

## Exemplos

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

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Preenche o campo da caixa de seleção com um valor booleano. Aviso: Apenas aplicável a Caixa de Seleção. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, em contraste com Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.CheckBoxField", você deve especificar o nome completo e não "CheckBoxField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo a ser preenchido. |
| beChecked | Boolean | Uma flag booleano: verdadeiro significa marcar a caixa, enquanto falso significa desmarcá-la. |

### Valor de Retorno

verdadeiro se o campo foi encontrado e preenchido com sucesso.

## Exemplos

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

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Preenche um campo com múltiplas seleções. Nota: apenas para o campo de Caixa de Lista do AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo totalmente qualificado. |
| fieldValues | String[] | Um array de strings que contém vários itens a serem selecionados. |

## Exemplos

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Preenche o campo com o valor especificado.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo |
| value | String | Novo valor do campo |
| fitFontSize | Boolean | Se verdadeiro, o tamanho da fonte nas caixas de edição será ajustado. |

### Valor de Retorno

verdadeiro se o campo foi encontrado e preenchido com sucesso.

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)