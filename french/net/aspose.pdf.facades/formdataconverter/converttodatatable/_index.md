---
title: ConvertToDataTable
second_title: Référence de l'API Aspose.PDF pour .NET
description: Convertir les fichiers de strems en table.
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable method

Convertir les fichiers de strems en table.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceStreams | Stream[] | Tableau de flux source au format spécifié. |
| sourceType | DataType | Format des données dans les flux. Les valeurs valides sont : PDF, FDF, XFDF, XML. |

### Exemples

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### Voir également

* enum [DataType](../../datatype)
* class [FormDataConverter](../../formdataconverter)
* espace de noms [Aspose.Pdf.Facades](../../formdataconverter)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->