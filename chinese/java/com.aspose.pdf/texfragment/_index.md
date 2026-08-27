---
title: "TeXFragment"
linktitle: "TeXFragment"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 LaTeX 片段。"
type: docs
weight: 4860
url: /zh/java/com.aspose.pdf/texfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.TeXFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.TeXFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.TeXFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TeXFragment extends FormattedFragment
```

表示 LaTeX 片段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeXFragment](#TeXFragment-java.lang.String-) | 初始化 HtmlFragment 类的新实例。 |
| [TeXFragment](#TeXFragment-java.lang.String-boolean-) | 初始化 HtmlFragment 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆片段。 |
| [getLatexLoadOptionsOfInstance](#getLatexLoadOptionsOfInstance--) | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |
| [getTeXLoadOptionsOfInstance](#getTeXLoadOptionsOfInstance--) | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |
| [setLatexLoadOptionsOfInstance](#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |
| [setTeXLoadOptionsOfInstance](#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 LatexLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |

### TeXFragment {#TeXFragment-java.lang.String-}
初始化 HtmlFragment 类的新实例。

### TeXFragment {#TeXFragment-java.lang.String-boolean-}
初始化 HtmlFragment 类的新实例。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆片段。

**Returns:**
已克隆的片段。

### getLatexLoadOptionsOfInstance {#getLatexLoadOptionsOfInstance--}
```
@Deprecated public final TeXLoadOptions getLatexLoadOptionsOfInstance()
```

获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。

**Returns:**
TeXLoadOptions 实例 @deprecated 请使用 TeXLoadOptionsOfInstance 替代。

### getTeXLoadOptionsOfInstance {#getTeXLoadOptionsOfInstance--}
```
public TeXLoadOptions getTeXLoadOptionsOfInstance()
```

获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。

**Returns:**
TeXLoadOptions 实例

### setLatexLoadOptionsOfInstance {#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。

### setTeXLoadOptionsOfInstance {#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 LatexLoadOptions。当需要为此实例或其他实例的 LaTeX 导入使用特定设置时请使用它（例如，当此实例或其他实例应为导入的 LaTeX 使用特定的 BasePath，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 LaTeX 加载选项。
