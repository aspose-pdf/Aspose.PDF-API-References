---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 메서드. 스트림의 파일을 테이블로 변환
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable 메서드

스트림의 파일을 테이블로 변환합니다.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreams | Stream[] | 지정된 형식의 소스 스트림 배열입니다. |
| sourceType | DataType | 스트림의 데이터 형식입니다. 유효한 값은: PDF, FDF, XFDF, XML입니다. |

## 예제

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### 참조

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)