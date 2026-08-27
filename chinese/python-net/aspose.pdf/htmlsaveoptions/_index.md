---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 HTML 格式的保存选项"
type: docs
weight: 490
url: /zh/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

导出为 HTML 格式的保存选项

HtmlSaveOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| HtmlSaveOptions() | 初始化 [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/) 类的新实例。 |
| HtmlSaveOptions(document_type) | 初始化 HtmlSaveOptions 类的新实例 |
| HtmlSaveOptions(fixed_layout) | 初始化 HtmlSaveOptions 类的新实例 |
| HtmlSaveOptions(document_type, fixed_layout) | 初始化 HtmlSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调用于处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。 <br/>            Continue 是默认操作，保存操作将继续，但用户也可以返回 Abort，此时保存操作应停止。 |
| save_format | 数据保存的格式。 |
| close_response | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| document_type | 获取或设置 [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/)。 |
| compress_svg_graphics_if_any | 获取或设置指示是否<br/>            在保存期间将找到的 SVG 图形（如果有）压缩（打包）<br/>            为 SVGZ 格式的标志 |
| split_css_into_pages | 当选择多页模式（即 'SplitIntoPages' 为 'true'）时，<br/>            此属性定义是否应为每个生成的 HTML 页面创建单独的 CSS 文件。<br/>            默认情况下此属性为 false，因而会为所有生成的页面创建<br/>            一个大的公共 CSS。以此模式生成的所有 CSS（每页一个 CSS）的总大小通常<br/>            远大于一个大 CSS 文件的大小，因为在前一种情况下<br/>            CSS 类会在每个页面的多个 CSS 文件中重复。<br/>            因此，仅当您希望<br/>            独立处理每个 HTML 页面时才使用此设置，且每个页面的 CSS 大小<br/>            成为最关键的问题。 |
| split_into_pages | 获取或设置指示是否每个源 <br/>            文档的页面将被转换为其自己的目标 HTML 文档的标志，<br/>            即结果 HTML 是否会被拆分为多个 HTML 页面。 |
| explicit_list_of_saved_pages | 使用此属性，您可以明确指定 <br/>            应转换的文档页码。<br/>            列表中的页码必须为从 1 开始的编号。例如，<br/>            有效的页码必须取自范围 (1...[NumberOfPagesInConvertedDocument])。<br/>            列表中页码的出现顺序不会影响它们在结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。<br/>            如果此列表为 null（默认情况），则会转换所有页。<br/>            如果列表中的任何页码超出现有页的范围 (1-[amountOfPagesInDocument])，<br/>            将抛出异常。 |
| fixed_layout | 获取或设置指示该 HTML 是否以固定布局创建的值。 |
| image_resolution | 获取或设置图像渲染的分辨率。 |
| default_font_name | 指定用于替代<br/>            未嵌入且系统中未安装的文档字体的已安装字体名称。<br/>            如果为 null，则使用默认的替代字体。 |
| batch_size | 定义批处理大小，如果批量转换适用于源和目标格式对。<br/>             |
| font_sources | 预保存字体的字体来源。 |
| additional_margin_width_in_points | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页的整体 HTML 不会<br/>            被拆分为不同的 HTML 页面，而是放入一个大的结果 HTML 文件中。<br/>            但每个源 PDF 页面将在 HTML 中以其自己的<br/>            矩形区域表示（如有必要，这些区域可以加边框以显示页面纸张边缘，使用特殊属性 'PageBorderIfAny'）。<br/>            此参数定义在输出 HTML 区域周围强制保留的边距宽度，<br/>            这些区域代表源 PDF 文档的页面。本质上它定义了 PDF “纸张”页面的 HTML 表示之间的保证间隔，以此转换模式。 |
| use_z_order | 如果属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。<br/>            如果此属性为 false，所有图形将放置为单层，这可能会导致重叠对象出现一些不必要的效果。 |
| convert_marked_content_to_layers | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）中的所有元素将放入带有 "data-pdflayer" 属性并指定图层名称的 HTML div 中。<br/>            该图层名称将从 PDF 标记内容的可选属性中提取。<br/>            如果此属性为 false（默认），则不会从 PDF 标记内容创建任何图层。 |
| minimal_line_width | 此属性设置图形路径线的最小宽度。<br/>如果线的粗细小于 1px，Adobe Acrobat 会将其四舍五入为此值。因此可以使用此属性在 HTML 浏览器中模拟此行为。 |
| prevent_glyphs_grouping | 此属性开启一种模式，在该模式下文本字形不会被分组为单词和字符串。<br/>该模式允许在页面上定位字形时保持最高精度，并可用于转换包含音乐符号或需要相互独立放置的字形的文档。<br/>仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| simple_textbox_mode_grouping | 此属性指定将字形和单词顺序分组为字符串。<br/>例如，在转换后的 HTML 中，标签和单词的顺序不同，而您希望它们保持一致。<br/>仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| flow_layout_paragraph_full_width | 此属性指定 Flow 模式下的全宽段落文本，FixedLayout = false |
| render_text_as_image | 如果将属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。<br/>这对于使文本不可选择可能有用<br/>或 HTML 文本未正确渲染时也可使用。 |
| save_full_font | 指示将保存完整字体，仅支持 True Type Fonts。<br/>默认情况下 SaveFullFont = false，转换器仅保存初始字体的子集，以满足文档文本的显示需求。 |
| antialiasing_processing | 此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施 |
| save_transparent_texts | PDF 可能包含可复制到剪贴板的透明文本（通常在文档包含图像且提取了 OCR 文本时出现）。<br/>此设置告知转换器是否需要将此类文本保存为透明的、可选择的文本在结果 HTML 中。 |
| save_shadowed_texts_as_transparent_texts | PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常在文档包含图像且提取了 OCR 文本时出现）。<br/>此设置告知转换器是否需要将此类文本保存为透明的、可选择的文本在结果 HTML 中，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制到剪贴板）。 |
| font_saving_mode | 定义在将 PDF 保存为所需格式时使用的字体保存模式 |
| page_border_if_any | 此属性表示用于在结果 HTML 文档中绘制（如果有）边框的一组设置，围绕表示源 PDF 页面的区域。<br/>本质上它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。 |
| page_margin_if_any | 此属性表示在结果 HTML 文档中围绕表示源 PDF 页面区域的额外页面边距（如果有）的一组设置。 |
| letters_positioning_method | 设置结果 HTML 中单词中字母的定位模式 |
| exclude_font_name_list | PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。 |
| special_folder_for_svg_images | 获取或设置目录路径，仅在将文档保存为 HTML 时遇到 SVG 图像时将其保存到该目录。<br/>            如果参数为空或 null，<br/>            则 SVG 文件（如果有）将与其他图像文件一起保存（靠近输出文件）<br/>            或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。<br/>            如果已成功使用 CustomImageSavingStrategy<br/>            属性处理相关图像文件，则此设置不产生任何影响。 |
| special_folder_for_all_images | 获取或设置目录路径，在将文档保存为 HTML 时遇到任何图像时将其保存到该目录。<br/>            如果参数为空或 null，<br/>            则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。<br/>            如果已成功使用 CustomImageSavingStrategy<br/>            属性处理相关图像文件，则此设置不产生任何影响。 |
| css_class_names_prefix | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名<br/>            （例如 \".stl_01 {}\" ... \".stl_NN {}\"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。<br/>            例如，如果您希望所有类名都以 'my_prefix_' 开头<br/>            （即类似 'my_prefix_1' ... 'my_prefix_NNN'），<br/>            只需在转换前将 'my_prefix_' 赋给此属性。<br/>            如果此属性保持未设置（即值为 null），则<br/>            转换器将自行生成类名<br/>            （例如 \".stl_01 {}\" ... \".stl_NN {}\"）。 |
| parts_embedding_mode | 它定义了引用的文件（HTML、字体、图像、CSS）<br/>            是嵌入到主 HTML 文件中，还是生成独立的二进制实体。 |
| html_markup_generation_mode | 有时会出现对 HTML 标记生成的特定需求。<br/>            此参数定义了在 PDF 转换为 HTML 过程中可使用的 HTML 准备模式，以满足这些特定需求。 |
| raster_images_saving_mode | 转换后的 PDF 可能包含栅格图像<br/>            此参数定义了在 PDF 转换为 HTML 过程中如何处理这些图像。 |
| remove_empty_areas_on_top_and_bottom | 定义在生成的 HTML 中是否移除顶部和底部没有任何内容的空白区域（如果存在）。 |
| font_encoding_strategy | 定义用于调优当前文档 PDF 解码的编码特殊规则 |
| pages_flow_type_depends_on_viewers_screen_size | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面对应的完整 HTML 将<br/>            放入一个大的结果 HTML 文件中。<br/>            此标志定义了结果 HTML 是否以一种方式生成，即在结果 HTML 中表示 PDF 页面的区域流动会依据查看器的屏幕分辨率而定。<br/>            假设查看器侧的屏幕宽度足以在水平方向并排放置两页或更多页面。若将此标志设为 true，则会利用此机会（尽可能在水平方向并排显示多页，随后下一组水平页面显示在第一组下方）。<br/>            否则页面将以如下方式流动：下一页始终显示在前一页的下方。 |
| try_save_text_underlining_and_strikeouting_in_css | PDF 本身不包含文本下划线标记，而是通过位于文本下方的线条来模拟。<br/>            此选项允许转换器尝试判断某条线是否为文本的下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

