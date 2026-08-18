---
title: "page_remove_watermarks"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus watermark di halaman."
type: docs
url: /id/rust-cpp/organize/page_remove_watermarks/
---

_Menghapus watermark di halaman._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
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

    // Hapus watermark di halaman
    pdf.page_remove_watermarks(1)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```