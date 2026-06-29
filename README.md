i2i Academy - Connecting A Cloud Service - 1

Bu proje, i2i Academy eğitimi kapsamında bulut bilişim altyapılarına giriş yapmak, bir Sanal Makine (VM) ayağa kaldırmak ve temel ağ/bağlantı kontrollerini gerçekleştirmek amacıyla hazırlanmıştır.

## Proje Amacı ve Kapsamı
Projenin temel amacı, bir Bulut Hizmet Sağlayıcısı (Cloud Service Provider) üzerinde temel bir Linux sunucusu kurmak, yerel makineden bu sunucuya erişim sağlamak ve temel terminal komutlarını uygulamaktır.

## Yapılan İşlemler

### 1. Sanal Makine (VM) Kurulumu
* Seçilen bulut platformu (GCP / AWS) üzerinde temel konfigürasyonlara sahip bir Sanal Makine (VM) oluşturulmuştur.

### 2. Ağ Bağlantısı ve Ping Testi
* Yerel bilgisayarın terminali (Command Prompt / Terminal) kullanılarak, bulut üzerinde çalışan sanal makinenin genel (Public) IP adresine `ping` testi gerçekleştirilmiş ve ağ erişilebilirliği doğrulanmıştır.

### 3. SSH Bağlantısı ve Dosya İşlemleri
* Güvenli kabuk (SSH) protokolü aracılığıyla sanal makineye uzaktan bağlantı sağlanmıştır.
* VM içerisinde terminal kullanılarak `hello.txt` adında bir metin dosyası oluşturulmuştur.
* Dosya içerisine `"Hello i2i Academy!"` metni yazılmış ve terminal üzerinden dosya içeriği başarıyla okunmuştur.

## Ekran Görüntüleri
*(Not: Aldığınız ekran görüntülerini GitHub'a yükledikten sonra bu bölüme ekleyebilirsiniz)*

### Ping Testi Sonucu


### SSH Bağlantısı ve Dosya İçeriği
