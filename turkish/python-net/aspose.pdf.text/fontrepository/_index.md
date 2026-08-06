---
title: "FontRepository"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Yazı tipi araması gerçekleştirir. Sistem yüklü yazı tiplerinde ve standart PDF yazı tiplerinde arama yapar.<br/>             Ayrıca özel yazı tiplerini açma işlevi sağlar."
type: docs
weight: 130
url: /tr/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Yazı tipi araması gerçekleştirir. Sistem yüklü yazı tiplerinde ve standart PDF yazı tiplerinde arama yapar.<br/>             Ayrıca özel yazı tiplerini açma işlevi sağlar.

FontRepository türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| FontRepository() | FontRepository sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| substitutions | Yazı tipi ikame stratejileri koleksiyonunu alır. |
| sources | Yazı tipi kaynakları koleksiyonunu alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| find_font(font_name) | Belirtilen yazı tipi adıyla fontu arar ve döndürür. |
| find_font(font_name, ignore_case) | Belirtilen yazı tipi adıyla fontu, büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak arar ve döndürür. |
| find_font(font_family_name, stl) | Belirtilen font adı ve font stiline sahip fontu arar ve döndürür. |
| find_font(font_family_name, stl, ignore_case) | Belirtilen font adı ve font stiline sahip fontu arar ve döndürür <br/>             büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak. |
| open_font(font_stream, font_type) | Belirtilen font akışıyla fontu açar. |
| open_font(font_file_path) | Belirtilen font dosyası yolu ile fontu açar. |
| open_font(font_file_path, metrics_file_path) | Belirtilen font dosyası yolu ile fontu açar. |
| load_fonts() | Sistemde yüklü fontları ve standart Pdf fontlarını yükler. Bu yöntem, font yükleme sürecini hızlandırmak için tasarlanmıştır.<br/>            Varsayılan olarak fontlar, herhangi bir font için ilk istek alındığında yüklenir. Bu yöntemin kullanılması, sistem ve standart Pdf fontlarını<br/>            herhangi bir Pdf belgesi açılmadan hemen önce yükler. |
| reload_fonts() | Özellik [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) tarafından belirtilen tüm fontları yeniden yükler. |

### Ayrıca Bakınız

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

