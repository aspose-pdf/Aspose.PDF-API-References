---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "إزالة توافق PDF/A من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_pdfa_compliance/
---

_إزالة توافق PDF/A من PDF-document._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // إزالة الامتثال لـ PDF/A من PDF-document
    pdf.remove_pdfa_compliance()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```