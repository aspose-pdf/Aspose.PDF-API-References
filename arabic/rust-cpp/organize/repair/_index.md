---
title: "repair"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بإصلاح PDF-document."
type: docs
url: /ar/rust-cpp/organize/repair/
---

_يُصلح مستند PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إصلاح مستند PDF-document
    pdf.repair()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```