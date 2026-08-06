---
title: "page_crop"
second_title: "Aspose.PDF for Rust via C++"
description: "裁剪页面。"
type: docs
url: /zh/rust-cpp/organize/page_crop/
---

_裁剪页面._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 裁剪页面
    pdf.page_crop(1, 1.0)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```