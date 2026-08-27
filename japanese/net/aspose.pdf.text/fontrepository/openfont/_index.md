---
title: "FontRepository.OpenFont"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FontRepository メソッド。指定されたフォントストリームでフォントを開きます"
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

指定されたフォント ストリームでフォントを開きます。

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontStream | Stream | フォントストリーム。 |
| fontType | FontTypes | フォントタイプの値。 |

### 戻り値

フォント オブジェクト。

## 例

この例では、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。

```csharp
// フォントを開く
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // 開く document
    Document doc = new Document(@"D:\Tests\input.pdf");

    // すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // 最初のページに対してアブソーバーを受け入れます
    doc.Pages[1].Accept(absorber);

    // 最初のテキスト出現箇所のフォントを変更
    absorber.TextFragments[1].TextState.Font = font;

    // 保存 document
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### 関連項目

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

指定されたフォント ファイル パスでフォントを開きます。

```csharp
public static Font OpenFont(string fontFilePath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontFilePath | String | フォントファイルのパス。 |

### 戻り値

フォント オブジェクト。

## 例

この例では、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。

```csharp
// フォントを開く
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

指定されたフォント ファイル パスとメトリクス ファイル パスでフォントを開きます。

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontFilePath | String | フォントファイルのパス。 |
| metricsFilePath | String | フォントメトリクスファイルのパス。 |

### 戻り値

フォント オブジェクト。

## 例

この例では、メトリック付きの Type1 フォントを開き、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを開く
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


