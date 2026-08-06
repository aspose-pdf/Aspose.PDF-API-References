---
title: "page_grayscale"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi halaman menjadi hitam putih."
type: docs
url: /id/rust-cpp/organize/page_grayscale/
---

_Mengonversi halaman menjadi hitam putih._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
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

    // Konversi halaman menjadi hitam putih
    pdf.page_grayscale(1)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```