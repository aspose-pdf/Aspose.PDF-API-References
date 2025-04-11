---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Exporta dados do banco de dados para a tabela
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## Método FormDataConverter.ExportFromDataBase

Exporta dados do banco de dados para a tabela.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| connectString | String | String de conexão para o banco de dados. |
| dbType | DataType | Tipo de conexão: OLEDB ou ODBC. |

## Exemplos

```csharp
FormDataConverter fc = new FormDataConverter();
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
DataTable table = new DataTable();
table.TableName = "TestSource";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
fc.ExportFromDataBase(connection, DataType.OLEDB);
```

### Veja Também

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)