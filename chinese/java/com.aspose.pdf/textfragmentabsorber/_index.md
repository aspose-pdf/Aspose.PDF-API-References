---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示文本片段的吸收器对象。执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>."
type: docs
weight: 5120
url: /zh/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> 表示文本片段的吸收器对象。执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本及其字体。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> {@code TextFragmentAbsorber} 对象主要用于文本搜索场景。搜索完成后，出现的匹配项以 {@code TextFragment} 对象表示，这些对象存放在 {@code TextFragmentAbsorber.TextFragments} 集合中。{@code TextFragment} 对象提供对搜索到的文本、文本属性的访问，并允许编辑文本以及更改文本状态（字体、字号、颜色等）。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页上查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | 为所有已吸收的文本片段应用字体大小。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。 |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | 为所有已吸收的文本片段应用字体。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。 |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | 为所有已吸收的文本片段同时应用字体和大小。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。 |
| [getErrors](#getErrors--) | {@code TextExtractionError} 对象的列表。它包含在文本提取过程中发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| [getExtractionOptions](#getExtractionOptions--) | 获取文本提取选项。 |
| [getPhrase](#getPhrase--) | <p> 获取 {@code TextFragmentAbsorber} 在 PDF 文档或页面上搜索的短语。 </p> |
| [getRegexResults](#getRegexResults--) | <p> 获取搜索出现位置的字典，以 System.Text.RegularExpressions.Regex 类作为键，{@link TextFragment} 作为值。示例演示如何在第一个 PDF 文档页上使用正则表达式数组查找文本。 // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | 获取 {@code TextAbsorber} 在 PDF 文档或页面上提取的文本。 |
| [getTextEditOptions](#getTextEditOptions--) | 获取文本编辑选项。这些选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| [getTextFragments](#getTextFragments--) | <p> 获取以 {@code TextFragment} 对象呈现的搜索出现位置集合。 </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | 获取文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。 |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> 获取搜索选项。该选项支持使用正则表达式进行搜索。 </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | 该值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | 从文档中移除所有文本。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | 从指定页面中移除所有文本。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 从指定页面的指定矩形区域内移除文本。 |
| [reset](#reset--) | 清除此 {@code TextFragmentAbsorber} 对象的 TextFragments 集合。 |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | 设置文本提取选项。 |
| [setPhrase](#setPhrase-java.lang.String-) | <p> 设置 {@code TextFragmentAbsorber} 在 PDF 文档或页面上搜索的短语。 </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。该选项定义当请求的字符无法使用字体写入时的特殊行为。 |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> 设置以 {@code TextFragment} 对象呈现的搜索匹配集合。 </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | 设置文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。 |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> 设置搜索选项。该选项支持使用正则表达式进行搜索。 </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 对指定文档执行搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档中查找文本并替换所有搜索匹配的文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 对指定页面执行搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | 对指定的表单对象执行搜索。 |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> 初始化 {@code TextFragmentAbsorber} 的新实例，该实例执行对文档或页面所有文本段的搜索。 </p> <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并替换文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

为所有已吸收的文本片段应用字体大小。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSize |  | 文本的字体大小。 |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
为所有已吸收的文本片段应用字体。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
为所有已吸收的文本片段同时应用字体和大小。如果页面上的所有片段都已被吸收，则比遍历片段更快。否则效果与遍历相似。

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

{@code TextExtractionError} 对象的列表。它包含在文本提取过程中发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。

**Returns:**
TextExtractionError 对象的列表

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

获取文本提取选项。

**Returns:**
TextExtractionOptions 对象

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> 获取 {@code TextFragmentAbsorber} 在 PDF 文档或页面上搜索的短语。 </p>

**Returns:**
字符串值 <hr> <pre> 该示例演示如何多次执行文本搜索并进行文本替换。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

<p> 获取搜索出现位置的字典，以 System.Text.RegularExpressions.Regex 类作为键，{@link TextFragment} 作为值。示例演示如何在第一个 PDF 文档页上使用正则表达式数组查找文本。 // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary 实例

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

获取 {@code TextAbsorber} 在 PDF 文档或页面上提取的文本。

**Returns:**
字符串值 该示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

获取文本编辑选项。这些选项定义当请求的符号无法使用字体写入时的特殊行为。

**Returns:**
TextEditOptions 对象

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> 获取以 {@code TextFragment} 对象呈现的搜索出现位置集合。 </p>

**Returns:**
TextFragmentCollection 对象 <hr> <pre> 该示例演示如何在 PDF 文档的第一页查找文本并用新文本替换所有搜索匹配。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

获取文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。

**Returns:**
TextReplaceOptions 值

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> 获取搜索选项。该选项支持使用正则表达式进行搜索。 </p>

**Returns:**
TextSearchOptions 对象 <hr> <pre> 此示例演示如何使用正则表达式执行文本搜索。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // 使吸收器使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。 absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // 我们应该找到 "hello" 单词并将其替换为 "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

该值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。

**Returns:**
布尔值

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
从文档中移除所有文本。

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
从指定页面中移除所有文本。

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
从指定页面的指定矩形区域内移除文本。

### reset {#reset--}
```
public void reset()
```

清除此 {@code TextFragmentAbsorber} 对象的 TextFragments 集合。

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
设置文本提取选项。

### setPhrase {#setPhrase-java.lang.String-}
<p> 设置 {@code TextFragmentAbsorber} 在 PDF 文档或页面上搜索的短语。 </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
设置文本编辑选项。该选项定义当请求的字符无法使用字体写入时的特殊行为。

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> 设置以 {@code TextFragment} 对象呈现的搜索匹配集合。 </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
设置文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> 设置搜索选项。该选项支持使用正则表达式进行搜索。 </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 对指定文档执行搜索。 </p> <hr> <pre> 此示例演示如何在 PDF 文档中查找文本并替换所有搜索匹配项的文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 对指定页面执行搜索。 </p> <hr> <pre> 此示例演示如何在第一个 PDF 文档页面上查找文本并替换该文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
对指定的表单对象执行搜索。
