---
title: "rotate"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يدور مستند PDF-document."
type: docs
url: /ar/rust-cpp/organize/rotate/
---

_يدور مستند PDF-document._

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
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تدوير مستند PDF-document
    pdf.rotate(Rotation::On270)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```