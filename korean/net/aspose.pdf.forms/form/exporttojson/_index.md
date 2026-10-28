---
title: "Form.ExportToJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다."
type: docs
weight: 260
url: /ko/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | JSON 출력을 쓸 스트림. |
| 옵션 | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정. |

### 반환 값

각 양식 필드에 대한 내보내기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

PDF 양식 필드를 JSON 형식으로 내보내고 결과를 지정된 파일에 씁니다.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | JSON 출력을 쓸 파일 이름. |
| 옵션 | ExportFieldsToJsonOptions | 양식 필드를 JSON으로 내보내기 위한 선택적 설정. |

### 반환 값

각 양식 필드에 대한 내보내기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


