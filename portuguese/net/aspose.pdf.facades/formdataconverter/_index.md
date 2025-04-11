---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.FormDataConverter. Representa uma classe para converter dados de um formato para outro formato. Pode converter os dados em fdf/xml/pdf/xfdf para OLEDB/OdbcDB. Também pode converter os dados em OLEDB/OdbcDB para os dados em fdf/xml/xfdf. Pode converter o fdf para o xml com a tag "hard-named".
type: docs
weight: 4320
url: /pt/net/aspose.pdf.facades/formdataconverter/
---
## Classe FormDataConverter

Representa uma classe para converter dados de um formato para outro formato. Pode converter os dados em fdf/xml/pdf/xfdf para OLEDB/OdbcDB. Também pode converter os dados em OLEDB/OdbcDB para os dados em fdf/xml/xfdf. Pode converter o fdf para o xml com a tag "hard-named".

```csharp
public sealed class FormDataConverter
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData irá limpar a tabela antes da exportação de dados. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable irá criar o campo necessário se ele não existir na Tabela. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase irá criar a tabela se ela não existir. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase irá excluir a tabela existente e criar uma nova tabela se esta propriedade estiver definida como verdadeira. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Obtém ou define o contêiner de dados intermediário, uma DataTable. Deve ser definido antes de converter dados de um formato para outro formato. As Colunas e o TableName da DataTable devem ser definidos. O TableName é o nome da Tabela no banco de dados. O ColumnName de cada coluna é o nome qualificado do campo do pdf. O Caption de cada coluna é o nome da coluna da tabela no banco de dados. Se o nome do campo for o mesmo que o nome da coluna da tabela, o Caption não precisa ser especificado. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Este método está obsoleto. Por favor, use ConvertToStreams() em vez disso. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Converte arquivos de streams em tabela. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Converte dados na tabela em streams. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporta dados do banco de dados para a tabela. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importa dados da tabela para o banco de dados. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Converte arquivo FDF em XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Converte arquivo de dados de formulário de importação/exportação XML em formato FDF. |

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)