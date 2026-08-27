---
title: "page_to_bmp"
second_title: "Aspose.PDF for Rust via C++"
description: "将指定页面转换并保存为 BMP-image。"
type: docs
url: /zh/rust-cpp/convert/page_to_bmp/
---

_将指定页面转换并保存为 BMP-image._

```rust
pub fn page_to_bmp(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **resolution_dpi** - the resolution in DPI
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 转换并保存指定页面为 Bmp-image
    pdf.page_to_bmp(1, 100, "sample_page1.bmp")?;

    Ok(())
}

```