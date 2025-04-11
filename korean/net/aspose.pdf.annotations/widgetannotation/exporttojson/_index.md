---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation 메서드. 지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 기록합니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 기록합니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | JSON 출력을 기록할 스트림입니다. |
| options | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정입니다. |

### 반환 값

지정된 양식 필드 및 해당 자식 요소(있는 경우)에 대한 내보내기 작업의 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### 참조

* 클래스 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 클래스 [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* 클래스 [WidgetAnnotation](../)
* 네임스페이스 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 지정된 파일에 기록합니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | JSON 출력을 기록할 파일의 이름입니다. |
| options | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정입니다. |

### 반환 값

지정된 양식 필드 및 해당 자식 요소(있는 경우)에 대한 내보내기 작업의 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### 참조

* 클래스 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 클래스 [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* 클래스 [WidgetAnnotation](../)
* 네임스페이스 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../../)