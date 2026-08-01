---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormDataConverter メソッド。FDF ファイルを XML に変換します"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

FDF ファイルを XML に変換します。

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| sourceFdf | Stream | 変換する FDF を含むストリームです |
| destXml | Stream | 結果の XML が配置される場所です |

## 例

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 関連項目

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


