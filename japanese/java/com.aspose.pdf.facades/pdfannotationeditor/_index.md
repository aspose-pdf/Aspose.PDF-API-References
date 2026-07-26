---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントの注釈（コメント）を扱うクラスを表します。"
type: docs
weight: 360
url: /ja/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

PDF ドキュメントの注釈（コメント）を扱うクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | 新しい {@code PdfAnnotationEditor} オブジェクトを初期化します。 |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | 新しい {@code PdfAnnotationEditor} オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> 指定されたアノテーション名のアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotation(\"4cfa69cd-9bff-49e0-9005-e22a77cebf38\"); editor.save(\"example_out.pdf\"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> ドキュメント内のすべてのアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> ドキュメント内のすべてのアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | アノテーションをストリームにエクスポートします。 |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> 指定されたアノテーションタイプの内容を XFDF にエクスポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> 指定されたアノテーションタイプの内容を XFDF にエクスポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> 指定されたタイプのアノテーションのリストを取得します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> 指定されたタイプのアノテーションのリストを取得します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> XFDF データストリームからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> XFDF データストリームから指定されたアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\"), annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> XFDF ファイルから指定されたアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf(\"annots.xfdf\", annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> 別の PDF ドキュメントストリームの配列からドキュメントにアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); editor.importAnnotations(streams); editor.save(\"example_out.pdf\"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> 別の PDF ドキュメントストリームの配列から指定されたアノテーションをドキュメントにインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save(\"example_out.pdf\"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> 別の PDF ドキュメントの配列からドキュメントにアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; editor.importAnnotations(paths); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> 別の PDF ドキュメントの配列から指定されたアノテーションをドキュメントにインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | FDF ファイルからすべてのアノテーションをインポートします。 PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromFdf(\"annots.fdf\"); editor.save(\"example_out.pdf\"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> XFDF データストリームからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> XFDF ファイルからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromXfdf(\"annots.xfdf\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> 指定されたページ範囲の指定されたタイプの注釈を変更します。次の注釈プロパティの変更をサポートします: Modified、Title、Contents、Color、Subject、Open。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "modifyAnnotations(int start, int end, Annotation annotation) を使用してください。" <p> 指定されたページ範囲の指定されたタイプの注釈を変更します。次の注釈プロパティの変更をサポートします: Modified、Title、Contents、Color、Subject、Open。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> 指定されたページ範囲の注釈の作成者を変更します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | 指定されたページの領域を削除します。 |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | 指定されたページの領域を削除します。 |
| [save](#save-java.io.OutputStream-) | 結果の PDF をストリームに保存します。 |
| [save](#save-java.lang.String-) | 結果の PDF をファイルに保存します。 |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

新しい {@code PdfAnnotationEditor} オブジェクトを初期化します。

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
新しい {@code PdfAnnotationEditor} オブジェクトを初期化します。

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> 指定されたアノテーション名のアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotation(\"4cfa69cd-9bff-49e0-9005-e22a77cebf38\"); editor.save(\"example_out.pdf\"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> ドキュメント内のすべてのアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> ドキュメント内のすべてのアノテーションを削除します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
アノテーションをストリームにエクスポートします。

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> 指定されたアノテーションタイプの内容を XFDF にエクスポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> 指定されたアノテーションタイプの内容を XFDF にエクスポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> 指定されたタイプのアノテーションのリストを取得します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> 指定されたタイプのアノテーションのリストを取得します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> ドキュメント内のすべてのアノテーションをフラット化します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> XFDF データストリームからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> XFDF データストリームから指定されたアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\"), annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> XFDF ファイルから指定されたアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf(\"annots.xfdf\", annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> 別の PDF ドキュメントストリームの配列からドキュメントにアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); editor.importAnnotations(streams); editor.save(\"example_out.pdf\"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> 別の PDF ドキュメントストリームの配列から指定されたアノテーションをドキュメントにインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save(\"example_out.pdf\"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> 別の PDF ドキュメントの配列からドキュメントにアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; editor.importAnnotations(paths); editor.save(\"example_out.pdf\"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> 別の PDF ドキュメントの配列から指定されたアノテーションをドキュメントにインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
FDF ファイルからすべてのアノテーションをインポートします。 PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromFdf(\"annots.fdf\"); editor.save(\"example_out.pdf\");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> XFDF データストリームからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> XFDF ファイルからすべてのアノテーションをインポートします。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromXfdf(\"annots.xfdf\"); editor.save(\"example_out.pdf\"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> 指定されたページ範囲の指定されたタイプの注釈を変更します。次の注釈プロパティの変更をサポートします: Modified、Title、Contents、Color、Subject、Open。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"modifyAnnotations(int start, int end, Annotation annotation) を使用してください。" <p> 指定されたページ範囲の指定されたタイプの注釈を変更します。次の注釈プロパティの変更をサポートします: Modified、Title、Contents、Color、Subject、Open。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> 指定されたページ範囲の注釈の作成者を変更します。 </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
指定されたページの領域を削除します。

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
指定されたページの領域を削除します。

### save {#save-java.io.OutputStream-}
結果の PDF をストリームに保存します。

### save {#save-java.lang.String-}
結果の PDF をファイルに保存します。
