---
title: "Form.ImportFromJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 스트림에 제공된 JSON 형식에서 PDF 양식 필드를 가져옵니다."
type: docs
weight: 310
url: /ko/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

스트림에 제공된 JSON 형식에서 PDF 양식 필드를 가져옵니다.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | JSON 입력을 읽을 스트림. |

### 반환 값

각 양식 필드에 대한 가져오기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

지정된 파일에 제공된 JSON 형식에서 PDF 양식 필드를 가져옵니다.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | JSON 입력을 읽을 파일 이름. |

### 반환 값

각 양식 필드에 대한 가져오기 작업 결과를 나타내는 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 컬렉션.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### 또 보기

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


