---
title: "Metadata"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "提供对 XMP 元数据流的访问。"
type: docs
weight: 930
url: /zh/python-net/aspose.pdf/metadata/
---

## Metadata class

提供对 XMP 元数据流的访问。

Metadata 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_fixed_size | 检查集合是否具有固定大小。 |
| keys | 获取元数据键的集合。 |
| values | 获取元数据中的值。 |
| is_synchronized | 检查集合是否已同步。 |
| sync_root | 获取集合同步对象。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | 注册命名空间 URI。 |
| register_namespace_uri(prefix, namespace_uri, schema_description) | 注册命名空间 URI。 |
| add(key, value) | 向元数据添加值。 |
| add(key, value) | 向元数据添加值。 |
| add(prefix, value) | 向元数据添加 pdf 扩展。 |
| get_namespace_uri_by_prefix(prefix) | 通过前缀返回命名空间 URI。 |
| get_prefix_by_namespace_uri(namespace_uri) | 通过命名空间 URI 返回前缀。 |
| contains(key) | 检查键是否存在于元数据中。 |
| remove(key) | 从元数据中移除条目。 |
| contains_key(key) | 确定此字典是否包含指定的键。 |
| try_get_value(key, value) | 尝试在字典中查找键，并在找到时检索其值。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

