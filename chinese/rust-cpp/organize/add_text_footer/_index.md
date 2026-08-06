---
title: "add_text_footer"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF-document 的页脚添加文本。"
type: docs
url: /zh/rust-cpp/organize/add_text_footer/
---

_在 PDF-document 的页脚添加文本._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在 PDF-文档 的页脚中添加文本
    pdf.add_text_footer("FOOTER")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```