---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 완전한 필드 이름에 따라 기존 버튼 필드에 이미지를 붙여넣습니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

완전한 필드 이름에 따라 기존 버튼 필드에 이미지를 붙여넣습니다.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이미지 버튼 필드의 완전한 필드 이름입니다. |
| imageFileName | String | 이미지 파일의 경로, 상대 경로와 절대 경로 모두 가능합니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### 참조

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

FillImageField의 오버로드 함수입니다. 입력은 이미지 스트림입니다.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 완전한 필드 이름입니다. |
| imageStream | Stream | 이미지의 스트림입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### 참조

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)