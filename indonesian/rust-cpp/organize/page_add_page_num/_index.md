---
title: "page_add_page_num"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan nomor halaman pada halaman."
type: docs
url: /id/rust-cpp/organize/page_add_page_num/
---

_Menambahkan nomor halaman pada halaman._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan nomor halaman pada halaman
    pdf.page_add_page_num(1)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```