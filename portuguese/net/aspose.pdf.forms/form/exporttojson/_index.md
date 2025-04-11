---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Método do formulário. Exporta os campos do formulário PDF para o formato JSON e grava o resultado no fluxo fornecido
type: docs
weight: 240
url: /pt/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporta os campos do formulário PDF para o formato JSON e grava o resultado no fluxo fornecido.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | O fluxo para o qual escrever a saída JSON. |
| options | ExportFieldsToJsonOptions | Configurações opcionais para exportar os campos do formulário para JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de exportação para cada campo do formulário.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporta os campos do formulário PDF para o formato JSON e grava o resultado no arquivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileName | String | O nome do arquivo para o qual escrever a saída JSON. |
| options | ExportFieldsToJsonOptions | Configurações opcionais para exportar os campos do formulário para JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de exportação para cada campo do formulário.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)