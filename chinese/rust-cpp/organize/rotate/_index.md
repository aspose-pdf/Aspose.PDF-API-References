---
title: "rotate"
second_title: "Aspose.PDF for Rust via C++"
description: "旋转 PDF-document。"
type: docs
url: /zh/rust-cpp/organize/rotate/
---

_旋转 PDF-document._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 旋转 PDF-document
    pdf.rotate(Rotation::On270)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```