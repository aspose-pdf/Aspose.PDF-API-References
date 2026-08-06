---
title: "page_rotate"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF-document 中旋转页面."
type: docs
url: /zh/rust-cpp/organize/page_rotate/
---

_在 PDF-document 中旋转页面._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 旋转页面
    pdf.page_rotate(1, Rotation::On180)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```