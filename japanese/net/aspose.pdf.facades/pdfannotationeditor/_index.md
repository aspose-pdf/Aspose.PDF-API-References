---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditorクラス。PDFドキュメントの注釈コメントを扱うためのクラスを表します。
type: docs
weight: 4410
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditorクラス

PDFドキュメントの注釈（コメント）を扱うためのクラスを表します。

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | 新しい `PdfAnnotationEditor` オブジェクトを初期化します。 |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | *document* に基づいて新しい `PdfAnnotationEditor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされたAspose.Pdf.Documentを破棄します。 |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | 指定された注釈名の注釈を削除します。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | ドキュメント内のすべての注釈を削除します。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | ドキュメント内の指定されたタイプのすべての注釈を削除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | 注釈をストリームにエクスポートします。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | 指定された注釈タイプの内容をXFDFにエクスポートします。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | 指定された注釈タイプの内容をXFDFにエクスポートします。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | 指定されたタイプの注釈のリストを取得します。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | 指定されたタイプの注釈のリストを取得します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | ドキュメント内のすべての注釈をフラット化します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | ドキュメント内のすべての注釈をフラット化します。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | 指定されたタイプの注釈をフラット化します。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | XFDFデータストリームから指定された注釈をインポートします。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | XFDFファイルから指定された注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | 他のPDFドキュメントストリームの配列からドキュメントに注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | 他のPDFドキュメントの配列からドキュメントに注釈をインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | 他のPDFドキュメントストリームの配列から指定された注釈をドキュメントにインポートします。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | 他のPDFドキュメントの配列から指定された注釈をドキュメントにインポートします。 |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | FDFファイルからすべての注釈をインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | XFDFデータストリームからすべての注釈をインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDFファイルからすべての注釈をインポートします。 |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | 指定されたページ範囲で指定されたタイプの注釈を修正します。次の注釈プロパティを修正することができます: Modified, Title, Contents, Color, Subject, および Open。 |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | 指定されたページ範囲で注釈の著者を修正します。 |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | 指定されたページの領域を修正します。すべての内容が削除されます。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDFドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDFドキュメントを指定されたファイルに保存します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)