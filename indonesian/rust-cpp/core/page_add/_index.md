---
title: "page_add"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan halaman baru ke PDF-dokumen."
type: docs
url: /id/rust-cpp/core/page_add/
---

_Menambahkan halaman baru ke PDF-dokumen._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan halaman baru dalam PDF-dokumen
    pdf.page_add()?;

    // Simpan PDF-document yang sebelumnya dibuka
    pdf.save()?;

    Ok(())
}

```