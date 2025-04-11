---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。XMLファイルからフィールドの内容をインポートし、新しいPDFに配置します。
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

XMLファイルからフィールドの内容をインポートし、新しいPDFに配置します。

```csharp
public void ImportXml(Stream inputXmlStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputXmlStream | Stream | インポート用のXMLが読み込まれるストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

XMLファイルからフィールドの内容をインポートし、新しいPDFに配置します。

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputXmlStream | Stream | 入力XMLストリーム。 |
| IgnoreFormTemplateChanges | Boolean | このパラメーターがtrueの場合、XFAフォームテンプレートのすべての変更は保存されません。 |

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)