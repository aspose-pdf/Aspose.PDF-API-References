---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Método de campo. Importa dados para os campos especificados a partir de um fluxo JSON com base em uma correspondência exata dos nomes completos dos campos
type: docs
weight: 210
url: /pt/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importa dados para os campos especificados a partir de um fluxo JSON, com base em uma correspondência exata dos nomes completos dos campos.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputJsonStream | Stream | O fluxo JSON de entrada contendo os dados do campo a serem importados para o campo. |

### Valor de Retorno

Verdadeiro se o campo foi encontrado no fluxo JSON; caso contrário - falso

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Veja Também

* classe [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importa dados para o campo especificado a partir de um fluxo JSON, usando o nome completo especificado na variável 'fieldFullNameInJSON' para correspondência.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputJsonStream | Stream | O fluxo JSON de entrada contendo os dados do campo a serem importados para o campo. |
| fieldFullNameInJSON | String | O nome dos dados dentro do fluxo JSON para correspondência. Se os dados dentro do fluxo JSON tiverem uma estrutura aninhada, o nome completo deve ser especificado com todos os itens pai e filho separados por '.' |

### Valor de Retorno

Verdadeiro se o campo foi encontrado no arquivo JSON; caso contrário - falso

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Veja Também

* classe [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)