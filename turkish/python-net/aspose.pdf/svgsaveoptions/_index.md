---
title: "SvgSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "SVG formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 1460
url: /tr/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

SVG formatına dışa aktarma için kaydetme seçenekleri

SvgSaveOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| SvgSaveOptions() | SvgSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Yok |
| try_merge_adjacent_same_background_images | Yok |
| treat_target_file_name_as_directory | Bu seçenek, hedef dizinin (henüz yoksa) istenen çıktı dosyasıyla aynı ada sahip bir dizin olarak oluşturulup oluşturulmayacağını tanımlar<br/>             (eğer henüz yoksa) istenen çıktı dosyasıyla aynı ada sahip bir dizin <br/>             istenen çıktı dosyasının kendisi yerine.<br/>             Böylece, dizin sayfaların tüm çıktı SVG görüntülerini (aşağıda açıklandığı gibi) içerecektir.<br/>               Hayır ise, ilk sayfa dışındaki sayfaların çıktı dosyaları tam olarak istenen dizinde<br/>            ana çıktı dosyası olarak oluşturulacak, ancak dosya adında _[2...n] eki bulunacak, bu<br/>             sayfa numarasına göre tanımlanır, ör. eğer çıktı dosyasını "C:\\AsposeTests\\output.svg" olarak tanımlarsanız<br/>             ve çıktı birkaç sayfanın svg dosyalarını içerecekse,<br/>             o zaman sayfa dosyaları da "C:\\AsposeTests\\" dizininde oluşturulacak ve 'output.svg', 'output_2.svg', 'output_3.svg' gibi adlara sahip olacaktır. |
| compress_output_to_zip_archive | Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir.<br/>             'TreatTargetFileNameAsDirectory' seçeneğine ilişkin yorumu inceleyerek çok sayfalı kaynak belge için sayfa svg dosyalarının adlandırma kurallarını görebilirsiniz; bu kurallar aynı zamanda sıkıştırılmış çıktı dosyalarına da uygulanır. |
| scale_to_pixels | Çıktı belgesinin tipografik puanlardan pikselere ölçeklenip ölçeklenmeyeceğini belirtir. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

