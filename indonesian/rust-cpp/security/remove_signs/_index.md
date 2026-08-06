---
title: "remove_signs"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Hapus tanda dari dokumen PDF."
type: docs
url: /id/rust-cpp/security/remove_signs/
---

_Hapus tanda dari PDF-document._

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
    // Buka PDF-document bernama "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Hapus tanda dari PDF-document
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```