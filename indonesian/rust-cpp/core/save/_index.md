---
title: "save"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menyimpan dokumen PDF yang sebelumnya dibuka."
type: docs
url: /id/rust-cpp/core/save/
---

_Menyimpan dokumen PDF yang sebelumnya dibuka._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document bernama "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Simpan PDF-document yang sebelumnya dibuka
    pdf.save()?;

    Ok(())
}

```