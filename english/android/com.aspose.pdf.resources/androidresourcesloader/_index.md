---
title: AndroidResourcesLoader
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.pdf.resources/androidresourcesloader/
---
**Inheritance:**
java.lang.Object
```
public class AndroidResourcesLoader
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AndroidResourcesLoader()](#AndroidResourcesLoader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [initContext(Activity activity)](#initContext-android.app.Activity-) |  |
| [getActivity()](#getActivity--) |  |
| [getContext()](#getContext--) |  |
| [loadResource(String fileName)](#loadResource-java.lang.String-) |  |
| [open(String fileName)](#open-java.lang.String-) |  |
| [isInit()](#isInit--) |  |
| [dispose()](#dispose--) |  |
### AndroidResourcesLoader() {#AndroidResourcesLoader--}
```
public AndroidResourcesLoader()
```


### initContext(Activity activity) {#initContext-android.app.Activity-}
```
public static void initContext(Activity activity)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| activity | android.app.Activity |  |

### getActivity() {#getActivity--}
```
public static Activity getActivity()
```




**Returns:**
android.app.Activity
### getContext() {#getContext--}
```
public static Context getContext()
```




**Returns:**
[Context](../../android.content/context)
### loadResource(String fileName) {#loadResource-java.lang.String-}
```
public static System.IO.Stream loadResource(String fileName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
com.aspose.ms.System.IO.Stream
### open(String fileName) {#open-java.lang.String-}
```
public static InputStream open(String fileName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
java.io.InputStream
### isInit() {#isInit--}
```
public static boolean isInit()
```




**Returns:**
boolean
### dispose() {#dispose--}
```
public static void dispose()
```




