---
title: "AppearanceDictionary"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "注释外观字典，指定注释在页面上如何以视觉方式呈现。"
type: docs
weight: 60
url: /zh/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

注释外观字典，指定注释在页面上如何以视觉方式呈现。

AppearanceDictionary 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_fixed_size | 获取一个值，指示字典是否具有固定大小。 |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state 值，<br/>            其中 N - 正常外观，R - 悬停外观，D - 按下外观，state - 状态的名称<br/>            （例如，复选框的 On、Off）。 |
| values | 获取字典值的列表。 <br/>            结果集合包含 XForm 对象的列表。 |
| is_synchronized | 获取一个值，指示对字典的访问是否已同步（线程安全）。 |
| sync_root | 获取一个可用于同步对字典访问的对象。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add(key, value) | 添加一个具有提供的键和值的元素。 |
| add(key, value) | 为指定键添加 X 表单。 |
| copy_to(array, index) | 将字典的元素复制到数组中，从特定的数组索引开始。 |
| contains_key(key) | 确定此字典是否包含指定的键。 |
| remove(key) | 从字典中删除键。 |
| try_get_value(key, value) | 尝试在字典中查找键，并在找到时检索其值。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

