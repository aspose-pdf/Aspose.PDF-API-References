---
title: "repair"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memperbaiki dokumen PDF."
type: docs
url: /id/rust-cpp/organize/repair/
---

_Memperbaiki dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Perbaiki dokumen PDF
    pdf.repair()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```