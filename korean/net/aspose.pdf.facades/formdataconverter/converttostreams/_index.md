---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 메서드. 테이블의 데이터를 스트림으로 변환
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams 메서드

테이블의 데이터를 스트림으로 변환합니다.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| destStream | Stream[] | 데이터가 저장될 스트림. |
| destType | DataType | 저장된 데이터의 유형. 유효한 값은: XML, FDF, XFDF. |

## 예제

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
DataRow newrow = table.NewRow();
newrow["textField"] = "NEW DATA";
newrow["listboxField"] = "Item1";
newrow["comboboxField"] = "Item1";
newrow["checkboxField"] = "true";
newrow["radiobuttonField"] = "true";
table.Rows.Add(newrow);
fc.Table = table;
fc.ConvertToStreams(new Stream[] { stream }, DataType.XML);
```

### 참조

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)