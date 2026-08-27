---
title: "save_as"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحفظ مستند PDF-document المفتوح مسبقًا باسم ملف جديد."
type: docs
url: /ar/rust-cpp/core/save_as/
---

_يحفظ مستند PDF-document المفتوح مسبقًا باسم ملف جديد._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // إنشاء مستند PDF-document جديد
    let pdf = Document::new()?;

    // احفظ مستند PDF-document باسم ملف جديد
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```