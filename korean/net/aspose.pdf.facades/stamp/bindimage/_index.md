---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Stamp 메서드. 이미지를 스탬프로 설정합니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

이미지를 스탬프로 설정합니다.

```csharp
public void BindImage(string imageFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | 문자열 | 이미지 파일 이름 및 경로. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

스탬프로 사용될 이미지를 설정합니다.

```csharp
public void BindImage(Stream image)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | 스트림 | 이미지 데이터가 포함된 스트림. |

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)