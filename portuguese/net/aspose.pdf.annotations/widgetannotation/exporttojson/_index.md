---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Método WidgetAnnotation. Exporta o campo de formulário PDF especificado para o formato JSON e grava o resultado no fluxo fornecido
type: docs
weight: 120
url: /pt/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporta o campo de formulário PDF especificado para o formato JSON e grava o resultado no fluxo fornecido.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | O fluxo para o qual a saída JSON será gravada. |
| options | ExportFieldsToJsonOptions | Configurações opcionais para exportar o campo de formulário para JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de exportação para o campo de formulário especificado e seus elementos filhos, se presentes.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporta o campo de formulário PDF especificado para o formato JSON e grava o resultado no arquivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileName | String | O nome do arquivo para o qual a saída JSON será gravada. |
| options | ExportFieldsToJsonOptions | Configurações opcionais para exportar o campo de formulário para JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de exportação para o campo de formulário especificado e seus elementos filhos, se presentes.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)