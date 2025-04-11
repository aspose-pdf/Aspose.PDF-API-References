---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter メソッド。FDF ファイルを XML に変換
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml メソッド

FDF ファイルを XML に変換します。

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceFdf | Stream | 変換する FDF を含むストリーム。 |
| destXml | Stream | 結果の XML が配置されるソース。 |

## 例

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 関連項目

* クラス [FormDataConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)