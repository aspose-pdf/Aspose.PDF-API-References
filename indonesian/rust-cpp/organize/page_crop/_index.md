---
title: "page_crop"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memotong sebuah halaman."
type: docs
url: /id/rust-cpp/organize/page_crop/
---

_Memotong sebuah halaman._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Potong sebuah halaman
    pdf.page_crop(1, 1.0)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```