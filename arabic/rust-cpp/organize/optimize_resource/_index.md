---
title: "optimize_resource"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحسين موارد PDF-document."
type: docs
url: /ar/rust-cpp/organize/optimize_resource/
---

_يقوم بتحسين موارد PDF-document._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // تحسين موارد PDF-document
    pdf.optimize_resource()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```