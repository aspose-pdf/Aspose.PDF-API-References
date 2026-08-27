---
title: "page_rotate"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يدور صفحة في مستند PDF."
type: docs
url: /ar/rust-cpp/organize/page_rotate/
---

_يدور صفحة في مستند PDF._

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
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // تدوير الصفحة
    pdf.page_rotate(1, Rotation::On180)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```