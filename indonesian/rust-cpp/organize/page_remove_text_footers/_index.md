---
title: "page_remove_text_footers"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus footer teks pada halaman."
type: docs
url: /id/rust-cpp/organize/page_remove_text_footers/
---

_Menghapus footer teks pada halaman._

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
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

    // Hapus footer teks pada halaman
    pdf.page_remove_text_footers(1)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```