---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: 페이지 메서드. 페이지에 이미지를 추가하고 지정된 사각형의 중앙에 위치시키며 이미지 비율을 유지합니다.
type: docs
weight: 350
url: /ko/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

페이지에 이미지를 추가하고 지정된 사각형의 중앙에 위치시키며 이미지 비율을 유지합니다.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지의 스트림. |
| imageRect | Rectangle | 이미지의 위치. |
| bbox | Rectangle | 이미지의 bbox. |
| autoAdjustRectangle | Boolean | 입력 사각형의 중앙에 이미지를 조정합니다. |

### 참조

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

검색 가능한 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 위치시키며 이미지 비율을 유지합니다.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hocr | String | 이미지의 hocr. |
| imageStream | Stream | 이미지의 스트림. |
| imageRect | Rectangle | 이미지의 위치. |
| bbox | Rectangle | 이미지의 bbox. |

### 참조

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
| imageStream | Stream | 이미지의 스트림. |
| imageRect | Rectangle | 페이지에서 이미지의 기본 위치. |
| imageWidth | Int32 | 이미지의 너비. |
| imageHeight | Int32 | 이미지의 높이. |
| saveImageProportions | Boolean | 플래그가 true로 설정되면 이미지가 사각형 위치에 배치됩니다. 그렇지 않으면 사각형의 크기가 이미지 크기와 같아집니다. |
| bbox | Rectangle | 이미지의 bbox. |

### 참조

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

페이지에 이미지를 추가하고 지정된 사각형의 중앙에 위치시키며 이미지 비율을 유지합니다.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imagePath | String | 이미지의 경로. |
| rectangle | Rectangle | 이미지의 위치. |

### 참조

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)