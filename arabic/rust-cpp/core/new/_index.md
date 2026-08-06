---
title: "جديد"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "ينشئ PDF-document جديدًا."
type: docs
url: /ar/rust-cpp/core/new/
---

_ينشئ PDF-document جديدًا._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // إنشاء مستند PDF-document جديد
    let pdf = Document::new()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```