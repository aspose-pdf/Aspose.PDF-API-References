---
title: PdfFileSignature
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для подписи PDF-файла сертификатом.
type: docs
weight: 45
url: /ru/java/com.aspose.pdf.facades/pdffilesignature/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileSignature extends SaveableFacade
```

Представляет класс для подписи PDF-файла сертификатом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileSignature()](#PdfFileSignature--) | Конструктор класса PdfFileSignature. |
| [PdfFileSignature(String inputFile)](#PdfFileSignature-java.lang.String-) | Конструктор класса PdfFileSignature. |
| [PdfFileSignature(String inputFile, String outputFile)](#PdfFileSignature-java.lang.String-java.lang.String-) | Конструктор класса PdfFileSignature. |
| [PdfFileSignature(IDocument document)](#PdfFileSignature-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfFileSignature на основе документа. |
| [PdfFileSignature(IDocument document, String outputFile)](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект PdfFileSignature на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Связывает поток Pdf для редактирования. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Связывает файл Pdf для редактирования. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature)](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Подтвердите документ подписью MDP. |
| [certify(String sigName, DocMDPSignature docMdpSignature)](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Подтвердите документ подписью MDP, которая размещена в уже представленном поле подписи. |
| [close()](#close--) | Закрывает фасад. |
| [containsSignature()](#containsSignature--) | Проверяет, есть ли у pdf цифровая подпись или нет. |
| [containsUsageRights()](#containsUsageRights--) | Проверяет, есть ли у pdf права на использование или нет. |
| [coversWholeDocument(String signName)](#coversWholeDocument-java.lang.String-) | Проверяет, охватывает ли подпись весь документ. |
| [dispose()](#dispose--) | Закрывает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractCertificate(String signName)](#extractCertificate-java.lang.String-) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [extractImage(String signName)](#extractImage-java.lang.String-) | Извлекает изображение подписи. |
| [getAccessPermissions()](#getAccessPermissions--) | Возвращает значение прав доступа сертифицированного документа по типу подписи MDP. |
| [getBlankSignNames()](#getBlankSignNames--) | Получает имена всех пустых полей подписи. |
| [getClass()](#getClass--) |  |
| [getContactInfo(String signName)](#getContactInfo-java.lang.String-) | Получает контактную информацию подписи. |
| [getDateTime(String signName)](#getDateTime-java.lang.String-) | Получает дату и время подписи. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getLocation(String signName)](#getLocation-java.lang.String-) | Получает расположение подписи. |
| [getReason(String signName)](#getReason-java.lang.String-) | Получает причину подписи. |
| [getRevision(String signName)](#getRevision-java.lang.String-) | Получает версию подписи. |
| [getSignNames()](#getSignNames--) | Получает имена всех непустых подписей. |
| [getSignNames(boolean onlyActive)](#getSignNames-boolean-) | Получает имена всех непустых подписей. |
| [getSignatureAppearance()](#getSignatureAppearance--) | Получает графический вид подписи. |
| [getSignatureAppearanceStream()](#getSignatureAppearanceStream--) | Получает графический вид подписи. |
| [getSignerName(String signName)](#getSignerName-java.lang.String-) | Получает имя человека или организации, подписавших PDF-документ. |
| [getTotalRevision()](#getTotalRevision--) | Получает общую ревизию. |
| [hashCode()](#hashCode--) |  |
| [isCertified()](#isCertified--) | Получает флаг, определяющий, сертифицирован документ или нет. |
| [isContainSignature()](#isContainSignature--) | Проверяет, есть ли у pdf цифровая подпись или нет. |
| [isCoversWholeDocument(String signName)](#isCoversWholeDocument-java.lang.String-) | Проверяет, охватывает ли подпись весь документ. |
| [isLtvEnabled()](#isLtvEnabled--) | Получает флаг включения LTV. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeSignature(String signName)](#removeSignature-java.lang.String-) | Удалите подпись в соответствии с названием подписи. |
| [removeSignature(String signName, boolean removeField)](#removeSignature-java.lang.String-boolean-) | Удаляет подпись по имени подписи. |
| [removeUsageRights()](#removeUsageRights--) | Удаляет запись прав использования. |
| [save()](#save--) | Сохраните подписанный pdf-файл. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет полученный PDF-файл в потоковом режиме. |
| [save(String outputFile)](#save-java.lang.String-) | Сохраняет результат PDF в файл. |
| [setCertificate(String pfx, String pass)](#setCertificate-java.lang.String-java.lang.String-) | Установите файл сертификата и пароль для процедуры подписи. |
| [setSignatureAppearance(String value)](#setSignatureAppearance-java.lang.String-) | Устанавливает графический вид подписи. |
| [setSignatureAppearanceStream(InputStream value)](#setSignatureAppearanceStream-java.io.InputStream-) | Устанавливает графический вид подписи. |
| [sign(int page, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Подпишите документ с заданным типом подписи. |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Сделайте подпись на pdf-документе. |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Подпишите документ с заданным типом подписи. |
| [sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. |
| [sign(String SigName, Signature sig)](#sign-java.lang.String-com.aspose.pdf.Signature-) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. |
| [sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. |
| [toString()](#toString--) |  |
| [verifySignature(String signName)](#verifySignature-java.lang.String-) | Проверяет действительность подписи. |
| [verifySigned(String signName)](#verifySigned-java.lang.String-) | Проверяет действительность подписи. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSignature() {#PdfFileSignature--}
```
public PdfFileSignature()
```


Конструктор класса PdfFileSignature.

### PdfFileSignature(String inputFile) {#PdfFileSignature-java.lang.String-}
```
public PdfFileSignature(String inputFile)
```


Конструктор класса PdfFileSignature.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл для подписи. |

### PdfFileSignature(String inputFile, String outputFile) {#PdfFileSignature-java.lang.String-java.lang.String-}
```
public PdfFileSignature(String inputFile, String outputFile)
```


Конструктор класса PdfFileSignature.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл для подписи. |
| outputFile | java.lang.String | Выходной файл. |

### PdfFileSignature(IDocument document) {#PdfFileSignature-com.aspose.pdf.IDocument-}
```
public PdfFileSignature(IDocument document)
```


Инициализирует новый объект PdfFileSignature на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### PdfFileSignature(IDocument document, String outputFile) {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSignature(IDocument document, String outputFile)
```


Инициализирует новый объект PdfFileSignature на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputFile | java.lang.String | Выходной файл. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Связывает поток Pdf для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF для редактирования. |

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

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Связывает файл Pdf для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | PDF-файл для редактирования. |

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

### certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature) {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
```
public void certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```


Подтвердите документ подписью MDP. Такие данные, как причина подписи, контакт и местонахождение, должны быть предоставлены соответствующими свойствами объекта Signature sig.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Страница, на которой делается подпись. |
| SigReason | java.lang.String | Причина подписи. |
| SigContact | java.lang.String | Контакт подписи. |
| SigLocation | java.lang.String | Место подписи. |
| visible | boolean | Видимость подписи. |
| annotRect | java.awt.Rectangle | Право подписи. |
| docMdpSignature | [DocMDPSignature](../../com.aspose.pdf/docmdpsignature) | Тип подписи документа MDP. |

### certify(String sigName, DocMDPSignature docMdpSignature) {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
```
public final void certify(String sigName, DocMDPSignature docMdpSignature)
```


Подтвердите документ подписью MDP, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf-документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр sigName).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| sigName | java.lang.String | Имя поля подписи. |
| docMdpSignature | [DocMDPSignature](../../com.aspose.pdf/docmdpsignature) | Тип подписи может быть и    |

### close() {#close--}
```
public void close()
```


Закрывает фасад.

### containsSignature() {#containsSignature--}
```
public boolean containsSignature()
```


Проверяет, есть ли у pdf цифровая подпись или нет.

**Возвращает:**
boolean - Возвращает результат логического типа.
### containsUsageRights() {#containsUsageRights--}
```
public boolean containsUsageRights()
```


Проверяет, есть ли у pdf права на использование или нет.

**Возвращает:**
boolean - Возвращает результат логического типа.
### coversWholeDocument(String signName) {#coversWholeDocument-java.lang.String-}
```
public boolean coversWholeDocument(String signName)
```


Проверяет, охватывает ли подпись весь документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
boolean - Возвращает результат логического типа.
### dispose() {#dispose--}
```
public void dispose()
```


Закрывает фасад. Этот метод устарел, вместо него используйте close().

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
### extractCertificate(String signName) {#extractCertificate-java.lang.String-}
```
public InputStream extractCertificate(String signName)
```


Извлекает единственный сертификат X.509 подписи в виде потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.io.InputStream — если сертификат найден, возвращает один сертификат X.509; в противном случае ноль.
### extractImage(String signName) {#extractImage-java.lang.String-}
```
public InputStream extractImage(String signName)
```


Извлекает изображение подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.io.InputStream — если изображение было успешно найдено, возвращает объект потока; в противном случае ноль.
### getAccessPermissions() {#getAccessPermissions--}
```
public int getAccessPermissions()
```


Возвращает значение прав доступа сертифицированного документа по типу подписи MDP.

**Возвращает:**
int - Если документ заверяется, то возвращает значение прав доступа; в противном случае выбрасывается.
### getBlankSignNames() {#getBlankSignNames--}
```
public List<String> getBlankSignNames()
```


Получает имена всех пустых полей подписи.

**Возвращает:**
java.util.List<java.lang.String> — возвращает список массивов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContactInfo(String signName) {#getContactInfo-java.lang.String-}
```
public String getContactInfo(String signName)
```


Получает контактную информацию подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.lang.String — возвращает результат типа String.
### getDateTime(String signName) {#getDateTime-java.lang.String-}
```
public Date getDateTime(String signName)
```


Получает дату и время подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
[Date](../../java.util/date) - Вернуть результат типа DateTime.
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getLocation(String signName) {#getLocation-java.lang.String-}
```
public String getLocation(String signName)
```


Получает расположение подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.lang.String — возвращает результат типа String.
### getReason(String signName) {#getReason-java.lang.String-}
```
public String getReason(String signName)
```


Получает причину подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.lang.String — возвращает результат типа String.
### getRevision(String signName) {#getRevision-java.lang.String-}
```
public int getRevision(String signName)
```


Получает версию подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
int - Возвращает номер версии подписи.
### getSignNames() {#getSignNames--}
```
public final List<String> getSignNames()
```


Получает имена всех непустых подписей.

--------------------

**Возвращает:**
java.util.List<java.lang.String> — возвращает список массивов.
### getSignNames(boolean onlyActive) {#getSignNames-boolean-}
```
public List<String> getSignNames(boolean onlyActive)
```


Получает имена всех непустых подписей.

--------------------

```
String inFile=TestPath + "example1.pdf";
  PdfFileSignature pdfSign=new PdfFileSignature();
  pdfSign.bindPdf(inFile);
  ArrayList names=pdfSign.getSignNames(true);
 for(int i=0;i<names.Count;i++)
 {
   System.out.println("signature name:"+(String)names[i]);
   System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i]));
   System.out.println("revision:"+pdfSign.GetRevision((String)names[i]));
   System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i]));
   System.out.println("reason:"+pdfSign.GetReason((String)names[i]));
   System.out.println("location:"+pdfSign.GetLocation((String)names[i]));
   System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i]));
  }
  System.out.println("totalvision:"+pdfSign.GetTotalRevision());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| onlyActive | boolean | логическое значение, если оно истинно, возвращать только активные подписи; в противном случае вернуть все подписи. |

**Возвращает:**
java.util.List<java.lang.String> — возвращает список массивов.
### getSignatureAppearance() {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```


Получает графический вид подписи. Значение свойства представляет имя файла изображения.

**Возвращает:**
java.lang.String — строковое значение
### getSignatureAppearanceStream() {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```


Получает графический вид подписи. Значение свойства представляет поток изображения.

**Возвращает:**
java.io.InputStream — элемент InputStream
### getSignerName(String signName) {#getSignerName-java.lang.String-}
```
public String getSignerName(String signName)
```


Получает имя человека или организации, подписавших PDF-документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
java.lang.String — возвращает результат имени подписавшего.
### getTotalRevision() {#getTotalRevision--}
```
public int getTotalRevision()
```


Получает общую ревизию.

**Возвращает:**
int — возвращает общее количество ревизий подписи.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCertified() {#isCertified--}
```
public boolean isCertified()
```


Получает флаг, определяющий, сертифицирован документ или нет.

**Возвращает:**
boolean - логическое значение
### isContainSignature() {#isContainSignature--}
```
public boolean isContainSignature()
```


Проверяет, есть ли у pdf цифровая подпись или нет.

**Возвращает:**
boolean - Возвращает результат логического типа.
### isCoversWholeDocument(String signName) {#isCoversWholeDocument-java.lang.String-}
```
public boolean isCoversWholeDocument(String signName)
```


Проверяет, охватывает ли подпись весь документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
boolean - Возвращает результат логического типа.
### isLtvEnabled() {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```


Получает флаг включения LTV.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeSignature(String signName) {#removeSignature-java.lang.String-}
```
public void removeSignature(String signName)
```


Удалите подпись в соответствии с названием подписи.

--------------------

```
String inFile = TestPath + "example1.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.bindPdf(inFile);
 List names = pdfSign.getSignNames();
 for(int i = 0; i < names.size(); i++)
 {
    pdfSign.removeSignature((String)names.get(i));
 }
 pdfSign.save(TestPath + "signed_removed.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

### removeSignature(String signName, boolean removeField) {#removeSignature-java.lang.String-boolean-}
```
public void removeSignature(String signName, boolean removeField)
```


Удаляет подпись по имени подписи.

--------------------

```
String inFile = TestPath + "example1.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.BindPdf(inFile);
 List names = pdfSign.getSignNames();
 for(int i = 0; i < names.size(); i++)
 {
    pdfSign.removeSignature((String)names.get(i), false);
 }
 pdfSign.save(TestPath + "signed_removed.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |
| removeField | boolean | Если установлено значение true, то из документа удаляются и подпись, и поле; в противном случае только подпись. |

### removeUsageRights() {#removeUsageRights--}
```
public void removeUsageRights()
```


Удаляет запись прав использования.

### save() {#save--}
```
public void save()
```


Сохраните подписанный pdf-файл. Имя выходного файла должно быть предоставлено заранее с помощью соответствующего конструктора PdfFileSignature.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет полученный PDF-файл в потоковом режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | выходной pdf-поток |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Сохраняет результат PDF в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | выходной pdf-файл |

### setCertificate(String pfx, String pass) {#setCertificate-java.lang.String-java.lang.String-}
```
public void setCertificate(String pfx, String pass)
```


Установите файл сертификата и пароль для процедуры подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | java.lang.String |  ПККС\Файл сертификата №12. |
| pass | java.lang.String | Пароль для доступа к закрытому ключу сертификата. |

### setSignatureAppearance(String value) {#setSignatureAppearance-java.lang.String-}
```
public void setSignatureAppearance(String value)
```


Устанавливает графический вид подписи. Значение свойства представляет имя файла изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setSignatureAppearanceStream(InputStream value) {#setSignatureAppearanceStream-java.io.InputStream-}
```
public void setSignatureAppearanceStream(InputStream value)
```


Устанавливает графический вид подписи. Значение свойства представляет поток изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Элемент InputStream |

### sign(int page, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, boolean visible, Rectangle annotRect, Signature sig)
```


Подпишите документ с заданным типом подписи.

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 sig.setReason ( "Some reason");
 sig.setContact ( "Smith");
 sig.setLocation ( "New York");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 Rectangle rect = new Rectangle(100, 100, 200, 100);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign(2, true, rect, sig);
 pdfSign.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер страницы, на которой ставится подпись. |
| visible | boolean | Видимость подписи. |
| annotRect | java.awt.Rectangle | Право подписи. |
| sig | [Signature](../../com.aspose.pdf/signature) | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. Такие данные, как причина подписи, контакт и местонахождение, должны уже присутствовать в этом объекте (см. соответствующие свойства). |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)
```


Сделайте подпись на pdf-документе.

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.bindPdf(inFile);
 Rectangle rect = new Rectangle(100, 100, 200, 200);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.setCertificate("certificate.pfx", "password");
 pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect);
 pdfSign.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер страницы, на которой ставится подпись. |
| SigReason | java.lang.String | Причина подписи. |
| SigContact | java.lang.String | Контакт подписи. |
| SigLocation | java.lang.String | Место подписи. |
| visible | boolean | Видимость подписи. |
| annotRect | java.awt.Rectangle | Право подписи. |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


Подпишите документ с заданным типом подписи.

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 Rectangle rect = new Rectangle(100, 100, 200, 100);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect, new PKCS1("certificate.pfx", "password"));
 pdfSign.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер страницы, на которой ставится подпись. |
| SigReason | java.lang.String | Причина подписи. |
| SigContact | java.lang.String | Контакт подписи. |
| SigLocation | java.lang.String | Место подписи. |
| visible | boolean | Видимость подписи. |
| annotRect | java.awt.Rectangle | Право подписи. |
| sig | [Signature](../../com.aspose.pdf/signature) | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

### sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. Перед подписанием в pdf-документе уже должно быть поле для подписи, соответствующая страница и прямоугольник берутся из поля для подписи, которое находится по имени подписи (см. параметр SigName).

--------------------

```
String inFile = TestPath + "blankWithSignature.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS7 sig = new PKCS7("certificate.pfx", "password");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile);
 Rectangle rect = new Rectangle(100, 100, 100, 100);
 pdfSign.setSignatureAppearance( TestPath + "butterfly.jpg");
 pdfSign.sign(1, "Signature1", "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig);
 pdfSign.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер страницы, на которой ставится подпись. |
| SigName | java.lang.String | Имя поля подписи. |
| SigReason | java.lang.String | Причина подписи. |
| SigContact | java.lang.String | Контакт подписи. |
| SigLocation | java.lang.String | Место подписи. |
| visible | boolean | Видимость подписи. |
| annotRect | java.awt.Rectangle | Право подписи. |
| sig | [Signature](../../com.aspose.pdf/signature) | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

### sign(String SigName, Signature sig) {#sign-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, Signature sig)
```


Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf-документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и местонахождение, должны быть предоставлены соответствующими свойствами объекта Signature sig.

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 sig.setReason ( "Some reason");
 sig.setContact ( "Smith");
 sig.setLocation ( "New York");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign("Signature1", sig);
 pdfSign.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | java.lang.String | Имя поля подписи. |
| sig | [Signature](../../com.aspose.pdf/signature) | Тип подписи может быть PKCS1 (объект Pkcs1Signature), PKCS7 и PKCS7 detached (объект Pkcs7Signature). |

### sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig) {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)
```


Подпишите документ подписью данного типа, которая размещена в уже представленном поле для подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf-документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName).

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig);
 pdfSign.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | java.lang.String | Имя поля подписи. |
| SigReason | java.lang.String | Причина подписи. |
| SigContact | java.lang.String | Контакт подписи. |
| SigLocation | java.lang.String | Место подписи. |
| sig | [Signature](../../com.aspose.pdf/signature) | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### verifySignature(String signName) {#verifySignature-java.lang.String-}
```
public boolean verifySignature(String signName)
```


Проверяет действительность подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
boolean - Возвращает результат логического типа.
### verifySigned(String signName) {#verifySigned-java.lang.String-}
```
public boolean verifySigned(String signName)
```


Проверяет действительность подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | java.lang.String | Название подписи. |

**Возвращает:**
boolean - Возвращает результат логического типа.
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
