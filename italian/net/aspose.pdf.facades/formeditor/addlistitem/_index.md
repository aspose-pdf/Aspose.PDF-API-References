---
title: AddListItem
second_title: Aspose.PDF per .NET API Reference
description: Aggiunge un nuovo elemento alla casella di riepilogo.
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Aggiunge un nuovo elemento alla casella di riepilogo.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo a cui verrà aggiunto il nuovo elemento. |
| itemName | String | Nome se nuovo elemento. |

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Aggiungi un nuovo elemento con il valore Esporta al campo della casella di riepilogo esistente, solo per il campo della casella combinata AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo a cui verranno aggiunti gli elementi. |
| exportName | String[] | Una matrice di stringhe che denota una nuova voce di elenco con Esporta valore, ad esempio (Etichetta elemento, Esporta valore). |

### Esempi

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->