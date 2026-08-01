---
title: "クラス PdfAnnotationEditor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor クラス。PDF ドキュメントの注釈コメントを操作するためのクラスを表します。"
type: docs
weight: 4530
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

PDF ドキュメントの注釈（コメント）を扱うクラスを表します。

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | `PdfAnnotationEditor` オブジェクトを新規に初期化します。 |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | `PdfAnnotationEditor` オブジェクトを *document* を基に新規に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | 指定された注釈名の注釈を削除します。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | ドキュメント内のすべての注釈を削除します。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | ドキュメント内の指定されたタイプのすべての注釈を削除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | 注釈をストリームにエクスポートします。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | 指定された注釈タイプの内容を XFDF にエクスポートします。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | 指定された注釈タイプの内容を XFDF にエクスポートします。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | 指定されたタイプの注釈一覧を取得します。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | 指定されたタイプの注釈一覧を取得します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | ドキュメント内のすべての注釈をフラット化します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | ドキュメント内のすべての注釈をフラット化します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | 指定されたタイプの注釈をフラット化します。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | XFDF データストリームから指定された注釈をインポートします。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | XFDF ファイルから指定された注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | 別の PDF ドキュメントストリームの配列からドキュメントに注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | 別の PDF ドキュメントの配列からドキュメントに注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | 別の PDF ドキュメントストリームの配列から指定された注釈をドキュメントにインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | 別の PDF ドキュメントの配列から指定された注釈をドキュメントにインポートします。 |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | FDF ファイルからすべての注釈をインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | XFDF データストリームからすべての注釈をインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF ファイルからすべての注釈をインポートします。 |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | 指定されたページ範囲の特定のタイプの注釈を変更します。次の注釈プロパティの変更をサポートしています：Modified、Title、Contents、Color、Subject、Open。 |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | 指定されたページ範囲の注釈の作成者を変更します。 |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | 指定されたページの領域を編集（マスク）します。すべてのコンテンツが削除されます。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


