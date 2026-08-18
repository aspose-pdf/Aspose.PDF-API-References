---
title: "append_pages"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan halaman terpilih dari PDF-document lain."
type: docs
url: /id/rust-cpp/core/append_pages/
---

_Menambahkan halaman terpilih dari PDF-document lain._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document utama
    let pdf = Document::open("sample1page.pdf")?;

    // Buka dokumen PDF lain untuk ditambahkan
    let another_pdf = Document::open("sample.pdf")?;

    // Tambahkan halaman tertentu (1 dan 3) dari PDF-document lain
    pdf.append_pages(&another_pdf, "1,3")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```