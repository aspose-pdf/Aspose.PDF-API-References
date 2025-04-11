---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 스트림에서 제공된 JSON 형식의 PDF 양식 필드를 가져옵니다.
type: docs
weight: 290
url: /ko/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

스트림에서 제공된 JSON 형식의 PDF 양식 필드를 가져옵니다.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | JSON 입력을 읽기 위한 스트림입니다. |

### 반환 값

각 양식 필드에 대한 가져오기 작업의 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### 참조

* 클래스 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

지정된 파일에서 제공된 JSON 형식의 PDF 양식 필드를 가져옵니다.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | JSON 입력을 읽기 위한 파일의 이름입니다. |

### 반환 값

각 양식 필드에 대한 가져오기 작업의 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### 참조

* 클래스 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)