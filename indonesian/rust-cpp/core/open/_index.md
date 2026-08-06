---
title: "open"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membuka dokumen PDF dengan nama file."
type: docs
url: /id/rust-cpp/core/open/
---

_Membuka dokumen PDF dengan nama file._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document bernama "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```