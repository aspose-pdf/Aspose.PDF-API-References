---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于操作 XMP 元数据的类。"
type: docs
weight: 380
url: /zh/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

用于操作 XMP 元数据的类。

PdfXmpMetadata 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfXmpMetadata() | PdfXmpMetadata 的构造函数。 |
| PdfXmpMetadata(document) | 初始化 PdfXmpMetadata 类的新实例。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| keys | 从字典获取键。 |
| values | 获取字典中值的集合。 |
| is_fixed_size | 如果集合具有固定大小，则返回 true。 |
| is_synchronized | 如果集合已同步，则返回 true。 |
| sync_root | 获取集合的同步对象。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| add(key, value) | 向 XMP 元数据添加值。 |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | 向元数据中添加扩展字段。 |
| add(key, value) | 向字典对象添加新元素。 |
| add(key, value) | 向元数据中添加扩展字段。 |
| remove(key) | 删除具有指定键的元素。 |
| remove(key) | 从字典中删除键。 |
| contains(key) | 检查字典是否包含指定的键。 |
| contains(property) | 检查字典是否包含指定的属性。 |
| get_xmp_metadata() | 以 XML 格式获取输入 PDF 的 XmpMetadata。 |
| get_xmp_metadata(name) | 根据元数据名称获取输入 PDF 的 XmpMetadata 的一部分。 |
| close() | 释放与当前外观关联的所有资源。 |
| register_namespace_uri(prefix, namespace_uri) | 注册命名空间 URI。 |
| get_namespace_uri_by_prefix(prefix) | 根据前缀获取命名空间 URI。 |
| get_prefix_by_namespace_uri(namespace_uri) | 根据命名空间 URI 获取前缀。 |
| contains_key(key) | 确定此字典是否包含指定的键。 |
| try_get_value(key, value) | 尝试在字典中查找键，并在找到时检索其值。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

