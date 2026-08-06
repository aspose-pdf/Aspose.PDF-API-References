---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحصل على ما إذا كان PDF-document متوافقًا مع PDF/A."
type: docs
url: /ar/rust-cpp/organize/is_pdfa_compliant/
---

_يحصل على ما إذا كان PDF-document متوافقًا مع PDF/A._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // احصل على حالة توافق PDF/A لمستند PDF-document
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```