---
title: "Page.AddImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 메서드. 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다."
type: docs
weight: 350
url: /ko/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지 스트림. |
| imageRect | Rectangle | 이미지의 위치. |
| bbox | Rectangle | 이미지의 Bbox. |
| autoAdjustRectangle | Boolean | 입력 사각형의 중앙에 이미지를 조정합니다. |

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

검색 가능한 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hocr | String | 이미지의 hocr. |
| imageStream | Stream | 이미지 스트림. |
| imageRect | Rectangle | 이미지의 위치. |
| bbox | Rectangle | 이미지의 bbox. |

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

페이지에 이미지를 추가하고 이미지 사각형 위치에 따라 배치합니다.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지 스트림. |
| imageRect | Rectangle | 페이지에서 이미지의 기본 위치. |
| imageWidth | Int32 | 이미지의 너비. |
| imageHeight | Int32 | 이미지의 높이. |
| saveImageProportions | Boolean | 플래그가 true로 설정된 경우 이미지가 사각형 위치에 배치되고; 그렇지 않으면 사각형 크기가 이미지 크기와 동일해집니다. |
| bbox | Rectangle | 이미지의 bbox. |

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imagePath | String | 이미지 경로. |
| rectangle | Rectangle | 이미지의 위치. |

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


