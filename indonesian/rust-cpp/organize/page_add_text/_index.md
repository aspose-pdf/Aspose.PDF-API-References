---
title: "page_add_text"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan teks ke halaman."
type: docs
url: /id/rust-cpp/organize/page_add_text/
---

_Menambahkan teks ke halaman._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan teks pada halaman
    pdf.page_add_text(1, "added text")?;

    // Simpan PDF-document yang sebelumnya dibuka
    pdf.save()?;

    Ok(())
}

```