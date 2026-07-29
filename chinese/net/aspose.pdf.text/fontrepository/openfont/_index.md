---
title: "FontRepository.OpenFont"
second_title: "Aspose.PDF for .NET API 参考"
description: "FontRepository 方法。使用指定的字体流打开字体。"
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

使用指定的字体流打开字体。

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontStream | Stream | 字体流。 |
| fontType | FontTypes | 字体类型值。 |

### 返回值

字体对象。

## 示例

该示例演示了如何打开字体并替换第一页文本的字体。

```csharp
// 打开字体
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // 打开文档
    Document doc = new Document(@"D:\Tests\input.pdf");

    // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // 接受第一页的吸收器
    doc.Pages[1].Accept(absorber);

    // 更改首次出现的文本的字体
    absorber.TextFragments[1].TextState.Font = font;

    // 保存文档
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### 另请参见

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

使用指定的字体文件路径打开字体。

```csharp
public static Font OpenFont(string fontFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | String | 字体文件路径。 |

### 返回值

字体对象。

## 示例

该示例演示了如何打开字体并替换第一页文本的字体。

```csharp
// 打开字体
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

使用指定的字体文件路径和度量文件路径打开字体。

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | String | 字体文件路径。 |
| metricsFilePath | String | 字体度量文件路径。 |

### 返回值

字体对象。

## 示例

示例演示了如何打开带度量的 Type1 字体并替换第一页文本的字体。

```csharp
// 打开字体
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


