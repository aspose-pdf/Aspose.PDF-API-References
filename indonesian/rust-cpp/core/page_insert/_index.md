---
title: "page_insert"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menyisipkan halaman baru pada posisi yang ditentukan dalam PDF-document."
type: docs
url: /id/rust-cpp/core/page_insert/
---

_Menyisipkan halaman baru pada posisi yang ditentukan dalam PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Sisipkan halaman baru pada posisi yang ditentukan dalam PDF-document
    pdf.page_insert(1)?;

    // Simpan PDF-document yang sebelumnya dibuka
    pdf.save()?;

    Ok(())
}

```