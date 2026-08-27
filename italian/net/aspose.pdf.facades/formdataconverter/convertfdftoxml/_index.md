---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "FormDataConverter metodo. Converte il file FDF in XML"
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

Converti il file FDF in XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFdf | Stream | Stream che contiene il FDF da convertire. |
| destXml | Stream | Fonte dove verrà posizionato l'XML risultato. |

## Esempi

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Vedi anche

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


