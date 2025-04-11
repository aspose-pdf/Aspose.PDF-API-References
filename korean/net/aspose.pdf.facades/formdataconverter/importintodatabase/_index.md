---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 메서드. 테이블에서 데이터베이스로 데이터를 가져옵니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase 메서드

테이블에서 데이터베이스로 데이터를 가져옵니다.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| connectString | String | 데이터베이스의 연결 문자열. |
| dbType | DataType | 데이터베이스 연결 유형: OLEDB 또는 ODBC. |

## 예제

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

### 참조

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)