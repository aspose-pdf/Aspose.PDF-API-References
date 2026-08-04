---
title: "FileSpecification"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示嵌入文件的类。"
type: docs
weight: 360
url: /zh/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

表示嵌入文件的类。

FileSpecification 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FileSpecification(file) | 初始化 FileSpecification 类的新实例 |
| FileSpecification(stream, name) | 初始化 FileSpecification 类的新实例 |
| FileSpecification(file, description) | 初始化 FileSpecification 类的新实例 |
| FileSpecification(stream, name, description) | 初始化 FileSpecification 类的新实例 |
| FileSpecification(file_name, annot) | 初始化 FileSpecification 类的新实例 |
| FileSpecification() | 创建新的空文件规范。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| 编码 | 获取或设置编码格式。<br/>            可能的值：Zip - 文件使用 ZIP 压缩，<br/>            None - 文件未压缩。 |
| include_contents | 如果为 true，文件的内容将包含在文件规范中。 |
| encrypted_payload | 获取已加密的负载。 |
| description | 获取或设置与文件规范关联的文本。 |
| af_relationship | 关联的文件关系。 |
| stream_contents | 以流的形式获取文件内容。 <br/>            内容不会加载到内存中，从而降低内存使用。<br/>            但此流不支持定位和 Length 属性。如果需要这些功能，请改用 Contents 属性。 |
| 内容 | 获取或设置文件内容。 <br/>            此属性返回加载到内存中的数据，对于大数据可能导致内存不足异常。<br/>            为了降低内存使用，请使用 StreamContents。 |
| params | 获取文件参数。 |
| mime_type | 获取嵌入文件的子类型。 |
| 名称 | 获取或设置文件规范名称。 |
| unicode_name | 获取或设置文件规范的 Unicode 名称。 |
| file_system | 获取或设置文件系统的名称。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_value(key) | 获取特定于应用程序的参数。 |
| set_value(key, value) | 设置特定于应用程序的参数。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

