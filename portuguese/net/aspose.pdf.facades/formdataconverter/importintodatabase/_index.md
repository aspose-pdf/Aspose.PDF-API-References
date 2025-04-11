---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Importa dados da tabela para o banco de dados
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## Método FormDataConverter.ImportIntoDataBase

Importa dados da tabela para o banco de dados.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| connectString | String | String de conexão do banco de dados. |
| dbType | DataType | Tipo de conexão com o banco de dados: OLEDB ou ODBC. |

## Exemplos

```csharp
FormDataConverter fc = new FormDataConverter();
DataTable table = new DataTable();
table.TableName = "test";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
DataRow row = table.NewRow();
row["TEXT_VALUE"] = "AAA";
row["INT_VALUE"] = "123";
table.Rows.Add(row);
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
fc.ImportIntoDataBase(connection, DataType.OLEDB);
```

### Veja Também

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)