---
title: ImportIntoDataBase
second_title: Aspose.PDF لمرجع .NET API
description: استيراد البيانات من الجدول إلى قاعدة البيانات .
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase method

استيراد البيانات من الجدول إلى قاعدة البيانات .

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connectString | String | سلسلة اتصال من قاعدة البيانات. |
| dbType | DataType | نوع اتصال قاعدة البيانات: OLEDB أو ODBC. |

### أمثلة

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

### أنظر أيضا

* enum [DataType](../../datatype)
* class [FormDataConverter](../../formdataconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../formdataconverter)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->