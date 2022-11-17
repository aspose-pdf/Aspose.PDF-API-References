---
title: PdfFileInfo
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для доступа к метаинформации документа PDF.
type: docs
weight: 41
url: /ru/java/com.aspose.pdf.facades/pdffileinfo/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileInfo extends SaveableFacade
```

Представляет класс для доступа к метаинформации документа PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileInfo()](#PdfFileInfo--) | Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo со значениями по умолчанию. |
| [PdfFileInfo(InputStream inputStream)](#PdfFileInfo-java.io.InputStream-) | Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo. |
| [PdfFileInfo(InputStream inputStream, String password)](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo. |
| [PdfFileInfo(String inputFile)](#PdfFileInfo-java.lang.String-) | Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo. |
| [PdfFileInfo(String inputFile, String password)](#PdfFileInfo-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo. |
| [PdfFileInfo(IDocument document)](#PdfFileInfo-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfFileInfo на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [clearInfo()](#clearInfo--) | Очищает всю метаинформацию документа PDF. |
| [close()](#close--) | Закрывает все ресурсы, используемые этим документом. |
| [dispose()](#dispose--) | Закрывает все ресурсы, используемые этим экземпляром. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthor()](#getAuthor--) | Получает информацию об авторе документа PDF. |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | Получает информацию о дате создания документа PDF. |
| [getCreator()](#getCreator--) | Получает информацию о создателе документа PDF. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getDocumentPrivilege()](#getDocumentPrivilege--) | Получает настройки привилегий для документа PDF. |
| [getHeader()](#getHeader--) | Получает настроенную информацию о документе PDF. |
| [getInputFile()](#getInputFile--) | Получает входной файл. |
| [getInputStream()](#getInputStream--) | Получает входной поток. |
| [getKeywords()](#getKeywords--) | Получает информацию о ключевых словах документа PDF. |
| [getMetaInfo(String name)](#getMetaInfo-java.lang.String-) | Получает настроенную информацию о документе PDF с именем свойства. |
| [getModDate()](#getModDate--) | Получает информацию о дате ModDate документа PDF. |
| [getNumberOfPages()](#getNumberOfPages--) | Получает количество страниц документа. |
| [getPageHeight(int pageNum)](#getPageHeight-int-) | Получает высоту указанной страницы. |
| [getPageRotation(int pageNum)](#getPageRotation-int-) | Получает поворот указанной страницы. |
| [getPageWidth(int pageNum)](#getPageWidth-int-) | Получает ширину указанной страницы. |
| [getPageXOffset(int pageNum)](#getPageXOffset-int-) | Получает горизонтальное смещение указанной области отображения страницы. |
| [getPageYOffset(int pageNum)](#getPageYOffset-int-) | Получает вертикальное смещение указанной области отображения страницы. |
| [getPasswordType()](#getPasswordType--) | Возвращает тип пароля, который был передан для создания экземпляра PdfFileInfo. |
| [getPdfVersion()](#getPdfVersion--) | Получает информацию о версии документа PDF. |
| [getProducer()](#getProducer--) | Получает информацию о производителе документа PDF. |
| [getSubject()](#getSubject--) | Получает информацию о теме документа PDF. |
| [getTitle()](#getTitle--) | Получает информацию о заголовке документа PDF. |
| [getUseStrictValidation()](#getUseStrictValidation--) | Использует строгие правила проверки с помощью IsPdfFile (\#isPdfFile.isPdfFile). |
| [hasCollection()](#hasCollection--) | Возвращает true, если текущий входной файл является файлом «Портфолио», содержащим в себе коллекцию PDF-файлов. |
| [hasEditPassword()](#hasEditPassword--) | Возвращает true, если для изменения разрешений или свойств безопасности документа требуется пароль. |
| [hasOpenPassword()](#hasOpenPassword--) | Возвращает true, если для открытия защищенного паролем PDF-документа требуется пароль. |
| [hashCode()](#hashCode--) |  |
| [isEncrypted()](#isEncrypted--) | Проверяет, зашифрован ли документ PDF. |
| [isPdfFile()](#isPdfFile--) | Проверяет, является ли исходный ввод допустимым файлом PDF. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный файл. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [saveNewInfo(OutputStream outputStream)](#saveNewInfo-java.io.OutputStream-) | Сохраните обновленный документ PDF в указанный поток. |
| [saveNewInfo(String outputFile)](#saveNewInfo-java.lang.String-) | Сохраните обновленный PDF-документ в указанный файл. |
| [saveNewInfoWithXmp(String outputFileName)](#saveNewInfoWithXmp-java.lang.String-) | Изменяет свойства, указанные явно путем установки информации о файле, другие свойства остаются. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Устанавливает информацию об авторе документа PDF. |
| [setCreationDate(String value)](#setCreationDate-java.lang.String-) | Устанавливает информацию о дате создания документа PDF. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Устанавливает информацию о создателе документа PDF. |
| [setHeader(Map<String,String> value)](#setHeader-java.util.Map-java.lang.String-java.lang.String--) | Устанавливает пользовательскую информацию документа PDF. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Устанавливает входной файл. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Устанавливает входной поток. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Задает информацию о ключевых словах документа PDF. |
| [setMetaInfo(String name, String value)](#setMetaInfo-java.lang.String-java.lang.String-) | Устанавливает пользовательскую информацию PDF-документа. |
| [setModDate(String value)](#setModDate-java.lang.String-) | Устанавливает информацию о дате ModDate документа PDF. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Задает информацию о теме документа PDF. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Задает информацию о заголовке документа PDF. |
| [setUseStrictValidation(boolean value)](#setUseStrictValidation-boolean-) | Использует строгие правила проверки с помощью IsPdfFile (\#isPdfFile.isPdfFile). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileInfo() {#PdfFileInfo--}
```
public PdfFileInfo()
```


Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo со значениями по умолчанию.

### PdfFileInfo(InputStream inputStream) {#PdfFileInfo-java.io.InputStream-}
```
public PdfFileInfo(InputStream inputStream)
```


Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, в который помещается входной файл. |

### PdfFileInfo(InputStream inputStream, String password) {#PdfFileInfo-java.io.InputStream-java.lang.String-}
```
public PdfFileInfo(InputStream inputStream, String password)
```


Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, в который помещается входной файл. |
| password | java.lang.String | Пароль для доступа к файлу. |

### PdfFileInfo(String inputFile) {#PdfFileInfo-java.lang.String-}
```
public PdfFileInfo(String inputFile)
```


Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя файла, содержащего входной файл. |

### PdfFileInfo(String inputFile, String password) {#PdfFileInfo-java.lang.String-java.lang.String-}
```
public PdfFileInfo(String inputFile, String password)
```


Инициализирует новый экземпляр класса com.aspose.pdf.facades.PdfFileInfo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя файла, содержащего входной файл. |
| password | java.lang.String | Пароль для доступа к файлу. |

### PdfFileInfo(IDocument document) {#PdfFileInfo-com.aspose.pdf.IDocument-}
```
public PdfFileInfo(IDocument document)
```


Инициализирует новый объект PdfFileInfo на основе документа.

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
| srcFile | java.lang.String | PDF-файл. |
| password | java.lang.String | Пароль документа PDF. |

### clearInfo() {#clearInfo--}
```
public void clearInfo()
```


Очищает всю метаинформацию документа PDF.

### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим документом.

### dispose() {#dispose--}
```
public void dispose()
```


Закрывает все ресурсы, используемые этим экземпляром.

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
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает информацию об авторе документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCreationDate() {#getCreationDate--}
```
public String getCreationDate()
```


Получает информацию о дате создания документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getCreator() {#getCreator--}
```
public String getCreator()
```


Получает информацию о создателе документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getDocumentPrivilege() {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```


Получает настройки привилегий для документа PDF.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Настройки привилегий для PDF-документов.
### getHeader() {#getHeader--}
```
public Map<String,String> getHeader()
```


Получает настроенную информацию о документе PDF.

**Возвращает:**
java.util.Map<java.lang.String,java.lang.String> — объект карты
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Получает входной файл.

**Возвращает:**
java.lang.String — строковое значение
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


Получает входной поток.

**Возвращает:**
java.io.InputStream — объект InputStream
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Получает информацию о ключевых словах документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getMetaInfo(String name) {#getMetaInfo-java.lang.String-}
```
public String getMetaInfo(String name)
```


Получает настроенную информацию о документе PDF с именем свойства. Если нет свойства, соответствующего имени, будет возвращена пустая строка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ пользовательского мета-свойства. |

**Возвращает:**
java.lang.String — значение пользовательского мета-свойства.
### getModDate() {#getModDate--}
```
public String getModDate()
```


Получает информацию о дате ModDate документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getNumberOfPages() {#getNumberOfPages--}
```
public int getNumberOfPages()
```


Получает количество страниц документа.

**Возвращает:**
интервал - целочисленное значение
### getPageHeight(int pageNum) {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```


Получает высоту указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNum | int | Номер страницы. |

**Возвращает:**
float — высота страницы.
### getPageRotation(int pageNum) {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```


Получает поворот указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNum | int | Номер страницы. |

**Возвращает:**
int - Поворот страницы. Значение может быть 0,90,180,270.
### getPageWidth(int pageNum) {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```


Получает ширину указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNum | int | Номер страницы. |

**Возвращает:**
float — ширина страницы.
### getPageXOffset(int pageNum) {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```


Получает горизонтальное смещение указанной области отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNum | int | Номер страницы. |

**Возвращает:**
float — смещение по горизонтали от левого края страницы.
### getPageYOffset(int pageNum) {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```


Получает вертикальное смещение указанной области отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNum | int | Номер страницы. |

**Возвращает:**
float - Вертикальное смещение области отображения страницы.
### getPasswordType() {#getPasswordType--}
```
public int getPasswordType()
```


Возвращает тип пароля, который был передан для создания экземпляра PdfFileInfo. См. возможные значения в PasswordType . Обратите внимание, что pdf-документ можно открыть как с использованием пароля пользователя (или открытия), так и пароля владельца (или прав доступа, редактирования).

**Возвращает:**
int — элемент типа пароля
### getPdfVersion() {#getPdfVersion--}
```
public String getPdfVersion()
```


Получает информацию о версии документа PDF.

**Возвращает:**
java.lang.String — строка версии.
### getProducer() {#getProducer--}
```
public String getProducer()
```


Получает информацию о производителе документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getSubject() {#getSubject--}
```
public String getSubject()
```


Получает информацию о теме документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает информацию о заголовке документа PDF.

**Возвращает:**
java.lang.String — строковое значение
### getUseStrictValidation() {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```


Использует строгие правила проверки с помощью IsPdfFile (\#isPdfFile.isPdfFile).

**Возвращает:**
boolean - логическое значение
### hasCollection() {#hasCollection--}
```
public boolean hasCollection()
```


Возвращает true, если текущий входной файл является файлом «Портфолио», содержащим в себе коллекцию PDF-файлов.

**Возвращает:**
boolean - логическое значение
### hasEditPassword() {#hasEditPassword--}
```
public boolean hasEditPassword()
```


Возвращает true, если для изменения разрешений или свойств безопасности документа требуется пароль. Обратите внимание, что это свойство может быть прочитано только в том случае, если в конструкторе PdfFileInfo был указан действительный пароль. Если PasswordType имеет значение Inaccessible (означает, что был предоставлен неверный пароль), чтение этого свойства завершится ошибкой с InvalidPasswordException .

**Возвращает:**
boolean - логическое значение
### hasOpenPassword() {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```


Возвращает true, если для открытия защищенного паролем PDF-документа требуется пароль.

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Проверяет, зашифрован ли документ PDF.

**Возвращает:**
boolean - логическое значение
### isPdfFile() {#isPdfFile--}
```
public boolean isPdfFile()
```


Проверяет, является ли исходный ввод допустимым файлом PDF.

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




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Целевой поток. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл назначения. |

### saveNewInfo(OutputStream outputStream) {#saveNewInfo-java.io.OutputStream-}
```
public boolean saveNewInfo(OutputStream outputStream)
```


Сохраните обновленный документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Выходной поток. |

**Возвращает:**
boolean - True, если в противном случае успех равен false.
### saveNewInfo(String outputFile) {#saveNewInfo-java.lang.String-}
```
public boolean saveNewInfo(String outputFile)
```


Сохраните обновленный PDF-документ в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Выходной файл. |

**Возвращает:**
boolean - True, если в противном случае успех равен false.
### saveNewInfoWithXmp(String outputFileName) {#saveNewInfoWithXmp-java.lang.String-}
```
public boolean saveNewInfoWithXmp(String outputFileName)
```


Изменяет свойства, указанные явно путем установки информации о файле, другие свойства остаются.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | java.lang.String | Выходной файл. |

**Возвращает:**
boolean - True для успеха или false.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Устанавливает информацию об авторе документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCreationDate(String value) {#setCreationDate-java.lang.String-}
```
public void setCreationDate(String value)
```


Устанавливает информацию о дате создания документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Устанавливает информацию о создателе документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setHeader(Map<String,String> value) {#setHeader-java.util.Map-java.lang.String-java.lang.String--}
```
public void setHeader(Map<String,String> value)
```


Устанавливает пользовательскую информацию документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Map<java.lang.String,java.lang.String> |  Объект карты |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


Устанавливает входной файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Устанавливает входной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Задает информацию о ключевых словах документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setMetaInfo(String name, String value) {#setMetaInfo-java.lang.String-java.lang.String-}
```
public void setMetaInfo(String name, String value)
```


Устанавливает пользовательскую информацию PDF-документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ пользовательского мета-свойства. |
| value | java.lang.String | Пользовательское значение мета-свойства. |

### setModDate(String value) {#setModDate-java.lang.String-}
```
public void setModDate(String value)
```


Устанавливает информацию о дате ModDate документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Задает информацию о теме документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Задает информацию о заголовке документа PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setUseStrictValidation(boolean value) {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```


Использует строгие правила проверки с помощью IsPdfFile (\#isPdfFile.isPdfFile).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
