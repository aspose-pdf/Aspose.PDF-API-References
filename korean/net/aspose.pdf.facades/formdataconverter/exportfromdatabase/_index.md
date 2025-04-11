---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 메서드. 데이터베이스에서 테이블로 데이터를 내보냅니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase 메서드

데이터베이스에서 테이블로 데이터를 내보냅니다.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| connectString | String | 데이터베이스의 연결 문자열. |
| dbType | DataType | 연결 유형: OLEDB 또는 ODBC. |

## 예제

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

### 참조

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)