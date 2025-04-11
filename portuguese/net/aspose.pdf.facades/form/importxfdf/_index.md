---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Importa o conteúdo dos campos do arquivo xfdfxml e os coloca no novo pdf
type: docs
weight: 300
url: /pt/net/aspose.pdf.facades/form/importxfdf/
---
## Método Form.ImportXfdf

Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputXfdfStream | Stream | O fluxo xfdf(xml) de entrada. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)