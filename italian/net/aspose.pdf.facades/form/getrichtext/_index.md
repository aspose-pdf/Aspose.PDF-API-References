---
title: "Form.GetRichText"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Ottiene il valore di un campo Rich Text includendo le informazioni di formattazione di ogni carattere"
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Ottieni il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere.

```csharp
public string GetRichText(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo Rich Text. |

### Valore di ritorno

Restituisce una stringa contenente le informazioni di formattazione del campo Rich Text.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


