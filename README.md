# ToprakNemSistemiAraRapor

# 1. Proje Konusu
   
Toprağın nemini ölçen ve ölçüm sonuçlarını internet üzerinden kullanıcılara bildiren bir sistem geliştirilmesi.
________________________________________
# 2. Özet 
Bu proje kapsamında, Arduino platformu kullanılarak toprak nem sensörü ile veri toplama işlemi gerçekleştirilmiştir. İnternet üzerinden veri iletimi sağlamak amacıyla çalışmalar yapılmaktadır. İlk aşamada ESP8266 modülü ile Telegram üzerinden bildirim gönderilmesi hedeflenmiş, bağlantı problemleri nedeniyle ESP32 modülü kullanılmasına karar verilmiştir. Sistem, belirli aralıklarla toprak nem bilgisini kullanıcılara ulaştıracaktır.
________________________________________
# 3. Kullanılan Yöntemler

•	Arduino Uno: Başlangıçta sensör verileri toplandı.

•	Toprak Nem Sensörü (YL-69): Nem ölçümü için kullanıldı.

•	ESP32 Geliştirme Kartı (Planlanan): Arduino'ya doğrudan Wi-Fi özelliği kazandıracak.

•	Telegram Bot API (Planlanan): Kullanıcılara nem bilgisi göndermek için kullanılacak.

•	C/C++ (Arduino IDE): Arduino ve ESP32 programlamasında kullanılıyor.

________________________________________
# 4. Yapılan Çalışmalar ve Görselleri

•	Toprak nem sensörü Arduino ile bağlandı ve veri okunması başarıyla sağlandı.

•	Telegram botu oluşturuldu ve bot token'ı elde edildi.

•	ESP8266 modülüyle Telegram'a bağlanma denemeleri yapıldı, bağlantı problemleri yaşandı.

•	Bağlantı sorunlarını çözmek için ESP32 modülü ile devam etme kararı alındı.

•	ESP32 kurulumu ve kod uyarlamaları için hazırlıklara başlandı.

Görseller:

•	Kullanılan nem Sensörü

<img src="https://github.com/21360859018/ToprakNemSistemiAraRapor/raw/main/Figure/nemsensörü.jpg" width="300" />


________________________________________
# 5. Elde Edilen Sonuçlar

•	Toprak nem sensöründen alınan veriler Arduino üzerinde başarılı bir şekilde okunabildi.

•	Telegram botu kurulumu tamamlandı.

•	ESP8266 ile yaşanan bağlantı problemleri tespit edildi.

•	ESP32 kullanımı ile bağlantı ve veri aktarım problemlerinin çözülmesi hedefleniyor.

________________________________________
# 6. Karşılaşılan Sorunlar ve Çözümler

| **Sorun**                                  | **Çözüm**                                                                |
|--------------------------------------------|---------------------------------------------------------------------------|
| ESP8266 ile Wi-Fi bağlantı problemleri yaşandı. | ESP32 geliştirme kartı kullanılarak doğrudan Wi-Fi bağlantısı sağlanacak. |
| Telegram API'ye veri gönderilemedi.        | ESP32 ile yeni bir bağlantı testi yapılacak ve kod güncellenecek.       |
| Güç kaynağı stabilitesi problemi.           | ESP32'nin stabil çalışması için harici güç kaynağı opsiyonu değerlendirilecek. |

________________________________________
# 7. Projenin Devamında Yapılacaklar

•	ESP32 modülü ile sensör verilerinin okunması ve Wi-Fi üzerinden Telegram Bot API'ye veri gönderilmesi.

•	4 saatte bir otomatik bildirim sisteminin oluşturulması.

•	Sensör verilerinin doğruluğunun test edilmesi.

•	Sistemin dış mekânda test edilmesi.

________________________________________

