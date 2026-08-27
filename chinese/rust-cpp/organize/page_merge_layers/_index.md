---
title: "page_merge_layers"
second_title: "Aspose.PDF for Rust via C++"
description: "将页面上的所有图层合并为单个图层，使用指定的新图层名称。"
type: docs
url: /zh/rust-cpp/organize/page_merge_layers/
---

_将页面上的所有图层合并为单个图层，使用指定的新图层名称。_

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 将页面上的所有图层合并为单个图层，使用指定的新图层名称
    pdf.page_merge_layers(1, "New Layer Name")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```