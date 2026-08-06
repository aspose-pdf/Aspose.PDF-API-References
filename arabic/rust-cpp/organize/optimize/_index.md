---
title: "optimize"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحسين محتوى PDF-document."
type: docs
url: /ar/rust-cpp/organize/optimize/
---

_يقوم بتحسين محتوى PDF-document._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // تحسين محتوى PDF-document
    pdf.optimize()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```