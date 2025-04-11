---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormDataConverter. Converti il file FDF in XML
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## Metodo FormDataConverter.ConvertFdfToXml

Converti il file FDF in XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFdf | Stream | Stream che contiene FDF da convertire. |
| destXml | Stream | Fonte in cui verrà posizionato il risultato XML. |

## Esempi

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Vedi Anche

* classe [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)