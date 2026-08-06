---
title: "page_remove_text_footers"
second_title: "Aspose.PDF for Rust via C++"
description: "删除页面中的文本页脚。"
type: docs
url: /zh/rust-cpp/organize/page_remove_text_footers/
---

_删除页面中的文本页脚。_

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 删除页面中的文本页脚
    pdf.page_remove_text_footers(1)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```