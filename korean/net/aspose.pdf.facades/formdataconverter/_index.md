---
title: "클래스 FormDataConverter"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.FormDataConverter 클래스. 데이터를 한 형식에서 다른 형식으로 변환하는 클래스를 나타냅니다. fdf/xml/pdf/xfdf 데이터를 OLEDB/OdbcDB 로 변환할 수 있습니다. 또한 OLEDB/OdbcDB 의 데이터를 fdf/xml/xfdf 로 변환할 수 있습니다. fdf를 하드네임드 태그가 있는 xml 로 변환할 수 있습니다."
type: docs
weight: 4440
url: /ko/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

데이터를 한 형식에서 다른 형식으로 변환하는 클래스를 나타냅니다. fdf/xml/pdf/xfdf 형식의 데이터를 OLEDB/OdbcDB로 변환할 수 있습니다. 또한 OLEDB/OdbcDB의 데이터를 fdf/xml/xfdf 형식으로 변환할 수 있습니다. fdf를 "hard-named" 태그가 있는 xml로 변환할 수 있습니다.

```csharp
public sealed class FormDataConverter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData는 데이터 내보내기 전에 테이블을 비웁니다. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable은 테이블에 존재하지 않을 경우 필요한 필드를 생성합니다. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase는 테이블이 존재하지 않을 경우 생성합니다. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase는 이 속성이 true로 설정된 경우 기존 테이블을 삭제하고 새 테이블을 생성합니다. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | 중간 데이터 컨테이너인 DataTable을 가져오거나 설정합니다. 한 형식에서 다른 형식으로 데이터를 변환하기 전에 정의되어야 합니다. DataTable의 Columns와 TableName을 정의해야 합니다. TableName은 데이터베이스의 테이블 이름입니다. 각 열의 ColumnName은 pdf의 정규화된 필드 이름이며, 각 열의 Caption은 데이터베이스 테이블의 열 이름입니다. 필드 이름이 테이블 열 이름과 동일한 경우 Caption을 지정할 필요가 없습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | 이 메서드는 사용되지 않습니다. 대신 ConvertToStreams()를 사용하십시오. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | 스트림 파일을 테이블로 변환합니다. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | 테이블의 데이터를 스트림으로 변환합니다. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | 데이터베이스에서 데이터를 테이블로 내보냅니다. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | 테이블에서 데이터를 데이터베이스로 가져옵니다. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | FDF 파일을 XML로 변환합니다. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | XML 가져오기/내보내기 양식 데이터 파일을 FDF 형식으로 변환합니다. |

### 또 보기

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


