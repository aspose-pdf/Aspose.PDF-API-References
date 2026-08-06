---
title: "تحويل"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحوّل مستند PDF إلى مستند PDF بالتنسيق المحدد للـ PDF."
type: docs
url: /ar/rust-cpp/organize/convert/
---

_يحوّل مستند PDF إلى مستند PDF بالتنسيق المحدد للـ PDF._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تحويل PDF-document إلى PDF-document بالتنسيق PDF المحدد
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // طباعة نتيجة التحويل والسجل الكامل
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```