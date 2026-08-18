---
title: "page_add_text_footer"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan teks di footer halaman."
type: docs
url: /id/rust-cpp/organize/page_add_text_footer/
---

_Menambahkan teks di footer halaman._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan teks di footer halaman
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```