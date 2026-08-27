---
title: "FormDataConverter.ExportFromDataBase"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormDataConverter. تصدر البيانات من قاعدة البيانات إلى الجدول"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase method

تصدير البيانات من قاعدة البيانات إلى جدول.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| connectString | String | سلسلة الاتصال لقاعدة البيانات. |
| dbType | DataType | نوع الاتصال: OLEDB أو ODBC. |

## أمثلة

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

### انظر أيضًا

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


