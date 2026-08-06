---
title: "page_add_text_header"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan teks di header halaman."
type: docs
url: /id/rust-cpp/organize/page_add_text_header/
---

_Menambahkan teks di header halaman._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan teks di header halaman
    pdf.page_add_text_header(1, "HEADER")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```