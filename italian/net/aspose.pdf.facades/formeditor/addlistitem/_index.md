---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Aggiunge un nuovo elemento alla casella dell'elenco
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Aggiunge un nuovo elemento alla casella dell'elenco.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo a cui verrà aggiunto il nuovo elemento. |
| itemName | String | Nome del nuovo elemento. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Aggiunge un nuovo elemento con valore di esportazione al campo della casella dell'elenco esistente, solo per il campo della casella combinata AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo a cui verranno aggiunti gli elementi. |
| exportName | String[] | Un array di stringhe che denota un nuovo elemento dell'elenco con valore di esportazione, cioè (Etichetta dell'elemento, Valore di esportazione). |

## Esempi

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)