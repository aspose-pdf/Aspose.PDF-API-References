---
title: "WidgetAnnotation.ExportToJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "WidgetAnnotation 메서드. 지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | JSON 출력을 쓸 스트림. |
| 옵션 | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정. |

### 반환 값

지정된 양식 필드 및 해당 자식 요소(있는 경우)의 내보내기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 지정된 파일에 씁니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | JSON 출력을 쓸 파일 이름. |
| 옵션 | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정. |

### 반환 값

지정된 양식 필드 및 해당 자식 요소(있는 경우)의 내보내기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


