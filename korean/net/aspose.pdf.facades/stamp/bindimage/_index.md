---
title: "Stamp.BindImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Stamp 메서드. 이미지를 스탬프로 설정합니다."
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
| imageFile | String | 이미지 파일 이름 및 경로입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

스탬프로 사용할 이미지를 설정합니다.

```csharp
public void BindImage(Stream image)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Stream | 이미지 데이터를 포함하는 스트림입니다. |

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


