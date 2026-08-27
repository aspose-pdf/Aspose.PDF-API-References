---
title: "remove_signs"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "إزالة التوقيعات من مستند PDF."
type: docs
url: /ar/rust-cpp/security/remove_signs/
---

_إزالة العلامات من مستند PDF._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF باسم "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // إزالة العلامات من مستند PDF
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```