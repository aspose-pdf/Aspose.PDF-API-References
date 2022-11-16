---
title: PdfAnnotationEditor
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для работы с комментариями аннотаций PDF-документа.
type: docs
weight: 34
url: /ru/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfAnnotationEditor extends SaveableFacade
```

Представляет собой класс для работы с аннотациями (комментариями) PDF-документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfAnnotationEditor()](#PdfAnnotationEditor--) | Инициализирует новый объект PdfAnnotationEditor. |
| [PdfAnnotationEditor(IDocument document)](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfAnnotationEditor на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Удаляет документ, связанный с фасадом. |
| [deleteAnnotation(String annotName)](#deleteAnnotation-java.lang.String-) | Удаляет аннотацию с указанным именем аннотации. |
| [deleteAnnotations()](#deleteAnnotations--) | Удаляет все аннотации в документе. |
| [deleteAnnotations(String annotType)](#deleteAnnotations-java.lang.String-) | Удаляет все аннотации указанного типа в документе. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportAnnotationsToXfdf(OutputStream xmlOutputStream)](#exportAnnotationsToXfdf-java.io.OutputStream-) | Экспорт аннотаций в поток. |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| [extractAnnotations(int start, int end, int[] annotTypes)](#extractAnnotations-int-int-int---) | Получает список аннотаций указанных типов. |
| [extractAnnotations(int start, int end, String[] annotTypes)](#extractAnnotations-int-int-java.lang.String---) | Получает список аннотаций указанных типов. |
| [flatteningAnnotations()](#flatteningAnnotations--) | Сглаживает все аннотации в документе. |
| [flatteningAnnotations(Form.FlattenSettings flattenSettings)](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | Сглаживает все аннотации в документе. |
| [flatteningAnnotations(int start, int end, int[] annotType)](#flatteningAnnotations-int-int-int---) | Сглаживает аннотации указанных типов. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [hashCode()](#hashCode--) |  |
| [importAnnotationFromXfdf(InputStream xfdfStream)](#importAnnotationFromXfdf-java.io.InputStream-) | Импортирует все аннотации из потока данных XFDF. |
| [importAnnotationFromXfdf(String xfdfFile)](#importAnnotationFromXfdf-java.lang.String-) | Импортирует все аннотации из файла XFDF. |
| [importAnnotations(InputStream[] annotFileInputStream)](#importAnnotations-java.io.InputStream---) | Импортирует аннотации в документ из массива других потоков документов PDF. |
| [importAnnotations(InputStream[] annotFileInputStream, int[] annotType)](#importAnnotations-java.io.InputStream---int---) | Импортирует указанные аннотации в документ из массива других потоков документов PDF. |
| [importAnnotations(String[] annotFile)](#importAnnotations-java.lang.String---) | Импортирует аннотации в документ из массива других документов PDF. |
| [importAnnotations(String[] annotFile, int[] annotType)](#importAnnotations-java.lang.String---int---) | Импортирует указанные аннотации в документ из массива других документов PDF. |
| [importAnnotationsFromXfdf(InputStream xfdfSteam)](#importAnnotationsFromXfdf-java.io.InputStream-) | Импортирует все аннотации из потока данных XFDF. |
| [importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)](#importAnnotationsFromXfdf-java.io.InputStream-int---) | Импортирует указанные аннотации из потока данных XFDF. |
| [importAnnotationsFromXfdf(String xfdfFile)](#importAnnotationsFromXfdf-java.lang.String-) | Импортирует все аннотации из файла XFDF. |
| [importAnnotationsFromXfdf(String xfdfFile, int[] annotType)](#importAnnotationsFromXfdf-java.lang.String-int---) | Импортирует указанные аннотации из файла XFDF. |
| [modifyAnnotations(int start, int end, Annotation annotation)](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | Изменяет аннотации указанного типа в указанном диапазоне страниц. |
| [modifyAnnotations(int start, int end, int annotType, Annotation annotation)](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | «Вместо этого используйте модификацию аннотаций (int start, int end, Annotation annotation)». |
| [modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | Изменяет автора аннотаций в указанном диапазоне страниц. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [redactArea(int pageIndex, Rectangle rect, Color color)](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Редактирует область на указанной странице. |
| [redactExactArea(int pageIndex, Rectangle rect, Color color)](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Редактирует область на указанной странице. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет полученный PDF-файл в потоковом режиме. |
| [save(String outputFile)](#save-java.lang.String-) | Сохраняет результат PDF в файл. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfAnnotationEditor() {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```


Инициализирует новый объект PdfAnnotationEditor.

### PdfAnnotationEditor(IDocument document) {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
```
public PdfAnnotationEditor(IDocument document)
```


Инициализирует новый объект PdfAnnotationEditor на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Удаляет документ, связанный с фасадом.

### deleteAnnotation(String annotName) {#deleteAnnotation-java.lang.String-}
```
public void deleteAnnotation(String annotName)
```


Удаляет аннотацию с указанным именем аннотации.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotName | java.lang.String | Имя аннотации |

### deleteAnnotations() {#deleteAnnotations--}
```
public void deleteAnnotations()
```


Удаляет все аннотации в документе.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations();
 editor.save("example_out.pdf");
```

### deleteAnnotations(String annotType) {#deleteAnnotations-java.lang.String-}
```
public void deleteAnnotations(String annotType)
```


Удаляет все аннотации указанного типа в документе.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations("Text");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotType | java.lang.String | Тип аннотации будет удален. |

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### exportAnnotationsToXfdf(OutputStream xmlOutputStream) {#exportAnnotationsToXfdf-java.io.OutputStream-}
```
public final void exportAnnotationsToXfdf(OutputStream xmlOutputStream)
```


Экспорт аннотаций в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | Экземпляр OutputStream (выходной поток) |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)
```


Экспортирует содержимое указанных типов аннотаций в XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 OutputStream stream = new FileOutputStream("example.xfdf");
     editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | Выходной поток XFDF. |
| start | int | Стартовая страница, с которой будут экспортироваться аннотации документа. |
| end | int | Конечная страница, на которую будут экспортированы аннотации документа. |
| annotTypes | int[] | Массив типов аннотаций необходимо экспортировать. |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)
```


Экспортирует содержимое указанных типов аннотаций в XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 OutputStream stream = new FileOutputStream("example.xfdf");
 editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | Выходной поток XFDF. |
| start | int | Стартовая страница, с которой будут экспортироваться аннотации документа. |
| end | int | Конечная страница, на которую будут экспортированы аннотации документа. |
| annotTypes | java.lang.String[] | Массив типов аннотаций необходимо экспортировать. |

### extractAnnotations(int start, int end, int[] annotTypes) {#extractAnnotations-int-int-int---}
```
public List<Annotation> extractAnnotations(int start, int end, int[] annotTypes)
```


Получает список аннотаций указанных типов.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Стартовая страница, с которой будут выбираться аннотации. |
| end | int | Конечная страница, к которой будут выбраны аннотации. |
| annotTypes | int[] | Массив необходимых типов аннотаций. |

**Возвращает:**
java.util.List<com.aspose.pdf.Annotation> — список аннотаций.
### extractAnnotations(int start, int end, String[] annotTypes) {#extractAnnotations-int-int-java.lang.String---}
```
public List<Annotation> extractAnnotations(int start, int end, String[] annotTypes)
```


Получает список аннотаций указанных типов.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Стартовая страница, с которой будут выбираться аннотации. |
| end | int | Конечная страница, к которой будут выбраны аннотации. |
| annotTypes | java.lang.String[] | Массив необходимых типов аннотаций. |

**Возвращает:**
java.util.List<com.aspose.pdf.Annotation> — список аннотаций.
### flatteningAnnotations() {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```


Сглаживает все аннотации в документе.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.flatteningAnnotations();
 editor.save(example_out.pdf");
```

### flatteningAnnotations(Form.FlattenSettings flattenSettings) {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
```
public final void flatteningAnnotations(Form.FlattenSettings flattenSettings)
```


Сглаживает все аннотации в документе.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | Определяет режимы выравнивания. |

### flatteningAnnotations(int start, int end, int[] annotType) {#flatteningAnnotations-int-int-int---}
```
public void flatteningAnnotations(int start, int end, int[] annotType)
```


Сглаживает аннотации указанных типов.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
 editor.flatteningAnnotations(1, 2, annotTypes);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Стартовая страница. |
| end | int | Затем конечная страница. |
| annotType | int[] | Типы аннотаций должны быть сглажены. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### importAnnotationFromXfdf(InputStream xfdfStream) {#importAnnotationFromXfdf-java.io.InputStream-}
```
public final void importAnnotationFromXfdf(InputStream xfdfStream)
```


Импортирует все аннотации из потока данных XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | Входной поток данных XFDF. |

### importAnnotationFromXfdf(String xfdfFile) {#importAnnotationFromXfdf-java.lang.String-}
```
public final void importAnnotationFromXfdf(String xfdfFile)
```


Импортирует все аннотации из файла XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | java.lang.String | Входной файл XFDF. |

### importAnnotations(InputStream[] annotFileInputStream) {#importAnnotations-java.io.InputStream---}
```
public void importAnnotations(InputStream[] annotFileInputStream)
```


Импортирует аннотации в документ из массива других потоков документов PDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 editor.importAnnotations(streams);
 editor.save("example_out.pdf");
 streams[0].Close();
 streams[1].Close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | Массив потоков PDF-документов, содержащих исходные аннотации. |

### importAnnotations(InputStream[] annotFileInputStream, int[] annotType) {#importAnnotations-java.io.InputStream---int---}
```
public void importAnnotations(InputStream[] annotFileInputStream, int[] annotType)
```


Импортирует указанные аннотации в документ из массива других потоков документов PDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(streams, annotTypes);
 editor.save("example_out.pdf");
 streams[0].close();
 streams[1].close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | Массив потоков PDF-документов, содержащих исходные аннотации. |
| annotType | int[] | Типы аннотаций для импорта. |

### importAnnotations(String[] annotFile) {#importAnnotations-java.lang.String---}
```
public void importAnnotations(String[] annotFile)
```


Импортирует аннотации в документ из массива других документов PDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 editor.importAnnotations(paths);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | java.lang.String[] | Массив путей к документам PDF, содержащим исходные аннотации. |

### importAnnotations(String[] annotFile, int[] annotType) {#importAnnotations-java.lang.String---int---}
```
public void importAnnotations(String[] annotFile, int[] annotType)
```


Импортирует указанные аннотации в документ из массива других документов PDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(paths, annotTypes);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | java.lang.String[] | Массив путей к документам PDF, содержащим исходные аннотации. |
| annotType | int[] | Массив типов аннотаций для импорта. |

### importAnnotationsFromXfdf(InputStream xfdfSteam) {#importAnnotationsFromXfdf-java.io.InputStream-}
```
public void importAnnotationsFromXfdf(InputStream xfdfSteam)
```


Импортирует все аннотации из потока данных XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfSteam | java.io.InputStream | Входной поток данных XFDF. |

### importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType) {#importAnnotationsFromXfdf-java.io.InputStream-int---}
```
public void importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)
```


Импортирует указанные аннотации из потока данных XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | Входной поток данных XFDF. |
| annotType | int[] | Массив типов аннотаций для импорта. |

### importAnnotationsFromXfdf(String xfdfFile) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String xfdfFile)
```


Импортирует все аннотации из файла XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | java.lang.String | Входной файл XFDF. |

### importAnnotationsFromXfdf(String xfdfFile, int[] annotType) {#importAnnotationsFromXfdf-java.lang.String-int---}
```
public void importAnnotationsFromXfdf(String xfdfFile, int[] annotType)
```


Импортирует указанные аннотации из файла XFDF.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotationFromXfdf("annots.xfdf", annotTypes);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | java.lang.String | Входной файл XFDF. |
| annotType | int[] | Импортируемый массив аннотаций. |

### modifyAnnotations(int start, int end, Annotation annotation) {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, Annotation annotation)
```


Изменяет аннотации указанного типа в указанном диапазоне страниц. Он поддерживает изменение следующих свойств аннотации: «Изменено», «Заголовок», «Содержание», «Цвет», «Тема» и «Открыть».

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 TextAnnotation annot = new TextAnnotation();
 annot.setModified ( new Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor ( Color.RED);
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, annot);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Номер начальной страницы. |
| end | int | Конечный номер страницы. |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Объект аннотации содержит новые свойства. |

### modifyAnnotations(int start, int end, int annotType, Annotation annotation) {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, int annotType, Annotation annotation)
```


«Вместо этого используйте модификацию аннотаций (int start, int end, Annotation annotation)».

Изменяет аннотации указанного типа в указанном диапазоне страниц. Он поддерживает изменение следующих свойств аннотации: «Изменено», «Заголовок», «Содержание», «Цвет», «Тема» и «Открыть».

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation();
 annot.setModified ( new java.util.Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor (com.aspose.pdf.Color.getRed());
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Номер начальной страницы. |
| end | int | Конечный номер страницы. |
| annotType | int | Тип аннотации. |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Объект аннотации содержит новые свойства. |

### modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor) {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
```
public void modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)
```


Изменяет автора аннотаций в указанном диапазоне страниц.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Номер начальной страницы. |
| end | int | Конечный номер страницы. |
| srcAuthor | java.lang.String | Автор, который должен быть изменен. |
| desAuthor | java.lang.String | Новый автор. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### redactArea(int pageIndex, Rectangle rect, Color color) {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactArea(int pageIndex, Rectangle rect, Color color)
```


Редактирует область на указанной странице. Все содержимое удаляется.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Площадь прямоугольника. |
| color | java.awt.Color | Цвет заливки. |

### redactExactArea(int pageIndex, Rectangle rect, Color color) {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactExactArea(int pageIndex, Rectangle rect, Color color)
```


Редактирует область на указанной странице. Все содержимое удаляется.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Площадь прямоугольника. |
| color | java.awt.Color | Цвет заливки. |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет полученный PDF-файл в потоковом режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Выходной PDF-поток |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Сохраняет результат PDF в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Выходной PDF-файл |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
