---
title: "page_remove_tables"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus tabel di halaman."
type: docs
url: /id/rust-cpp/organize/page_remove_tables/
---

_Menghapus tabel di halaman._

```rust
pub fn page_remove_tables(&self, num: i32) -> Result<(), PdfError>
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

    // Hapus tabel di halaman
    pdf.page_remove_tables(1)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_remove_tables.pdf")?;

    Ok(())
}

```