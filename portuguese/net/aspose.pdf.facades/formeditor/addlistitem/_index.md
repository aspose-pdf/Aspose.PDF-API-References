---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Adiciona novo item à caixa de lista
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AdicionarItemLista(string, string) {#addlistitem}

Adiciona novo item à caixa de lista.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo ao qual o novo item será adicionado. |
| itemName | String | Nome do novo item. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarItemLista(string, string[]) {#addlistitem_1}

Adiciona um novo item com valor de Exportação ao campo de caixa de lista existente, apenas para campo de caixa de combinação AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo ao qual os itens serão adicionados. |
| exportName | String[] | Um array de strings denotando um novo item da lista com Valor de Exportação, ou seja, (Rótulo do Item, Valor de Exportação). |

## Exemplos

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)