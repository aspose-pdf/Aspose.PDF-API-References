---
title: "validate"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يتحقق من مستند PDF للتوافق مع تنسيق PDF."
type: docs
url: /ar/rust-cpp/organize/validate/
---

_يتحقق من مستند PDF للتوافق مع تنسيق PDF._

```rust
    pub fn validate(
        &self,
        pdf_format: PdfFormat,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the validation log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // التحقق من توافق PDF-document مع تنسيق PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // طباعة نتيجة التحقق والسجل الكامل
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```