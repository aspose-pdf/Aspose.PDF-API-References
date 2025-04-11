---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Método do formulário. Importa os campos do formulário PDF do formato JSON fornecido no stream
type: docs
weight: 290
url: /pt/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importa os campos do formulário PDF do formato JSON fornecido no stream.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | O stream para ler a entrada JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de importação para cada campo do formulário.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importa os campos do formulário PDF do formato JSON fornecido no arquivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileName | String | O nome do arquivo para ler a entrada JSON. |

### Valor de Retorno

Uma coleção de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicando o resultado da operação de importação para cada campo do formulário.

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Veja Também

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)