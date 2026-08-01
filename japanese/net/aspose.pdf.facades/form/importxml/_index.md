---
title: "Form.ImportXml"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。xml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。"
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

xml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

```csharp
public void ImportXml(Stream inputXmlStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputXmlStream | Stream | インポート用 XML が読み取られるストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

xml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputXmlStream | Stream | 入力 xml ストリーム。 |
| IgnoreFormTemplateChanges | Boolean | このパラメータが true の場合、XFA フォームテンプレートのすべての変更は保存されません。 |

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


