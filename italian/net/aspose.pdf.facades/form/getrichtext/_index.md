---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Ottieni il valore di un campo Rich Text inclusa l'informazione di formattazione di ogni carattere
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/form/getrichtext/
---
## Metodo Form.GetRichText

Ottieni il valore di un campo Rich Text, inclusa l'informazione di formattazione di ogni carattere.

```csharp
public string GetRichText(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo Rich Text completamente qualificato. |

### Valore di Ritorno

Restituisce una stringa contenente informazioni di formattazione del campo Rich Text.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)