---
title: ContentsAppender
second_title: Aspose.PDF for Java API Reference
description: Performs contents modifications in APPEND mode only. this mode allows to avoid unneeded and heavy contents parsing before some change is made to the contents. It only appends new.
type: docs
weight: 800
url: /java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Performs contents modifications in APPEND mode only. this mode allows to avoid unneeded and heavy contents parsing before some change is made to the contents. It only appends new operators to the end or to the begin of the contents

## Constructors

| Constructor | Description |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Initializez new instance of the contents appender with page attached |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Initializes new instanse of the contets appender with Form XObject. |

## Methods

| Method | Description |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Appends operators to the end of the contents |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Appends operator to the end of the contents |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Appends operators to the end of the contents |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Appends operators to the begin of the contents |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Appends operator to the begin of the contents |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Appends operators to the begin of the contents |
| [getBeginCode](#getBeginCode--) | String containing operators to insert into start of page. |
| [getBeginOperators](#getBeginOperators--) | <p> returns begin operators </p> |
| [getEndCode](#getEndCode--) | Stirng containing operators to append to the end of page. |
| [getEndOperators](#getEndOperators--) | <p> returns end operators </p> |
| [resumeUpdate](#resumeUpdate--) | resumes document update |
| [setBeginCode](#setBeginCode-java.lang.String-) | String containing operators to insert into start of page. |
| [setEndCode](#setEndCode-java.lang.String-) | String containing operators to insert into start of page. |
| [suppressUpdate](#suppressUpdate--) | Suppresses update contents data The contents is not updated until ResumeUpdate is called |
| [updateData](#updateData--) | this is new version of UpdateData, which avoid decoding of the existing contents. |
| [updateDataOld](#updateDataOld--) | Must be called to apply the changes |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Initializez new instance of the contents appender with page attached

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Initializes new instanse of the contets appender with Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Appends operators to the end of the contents

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Appends operator to the end of the contents

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Appends operators to the end of the contents

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Appends operators to the begin of the contents

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Appends operator to the begin of the contents

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Appends operators to the begin of the contents

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

String containing operators to insert into start of page.

**Returns:**
String object

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> returns begin operators </p>

**Returns:**
{@code List<Operator>} object

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Stirng containing operators to append to the end of page.

**Returns:**
String object

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> returns end operators </p>

**Returns:**
{@code List<Operator>} object

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

resumes document update

### setBeginCode {#setBeginCode-java.lang.String-}
String containing operators to insert into start of page.

### setEndCode {#setEndCode-java.lang.String-}
String containing operators to insert into start of page.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suppresses update contents data The contents is not updated until ResumeUpdate is called

### updateData {#updateData--}
```
public void updateData()
```

this is new version of UpdateData, which avoid decoding of the existing contents.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Must be called to apply the changes
