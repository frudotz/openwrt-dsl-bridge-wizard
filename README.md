# [BETA] OpenWRT Köprü Modu Hızlı Kurulum Sihirbazı
OpenWRT kurulu DSL modem ve routerınız için hızlı başlangıç sağlayabileceğiniz otomatik köprü kurulum sihirbazı.  
*DİKKAT! Henüz deneysel aşamadaki bu sihirbazı kullanırken oluşabilecek komplikasyonlar sizin sorumluluğunuzdadır.*  
Sihirbazı kullanırken herhangi bir hata ile karşılaşırsanız veya takıldığınız bir yer olursa; [**@frudotz**](http://frudotz.com/)  
Varsa `/tmp/setup-frudotz.log` dosyanızla birlikte Discord/Telegram üzerinden bana ulaşarak iletebilirsiniz.  
*Rehberimizi kaynak göstererek paylaşmanız önemle rica olunur.* 🙏  

## 💭 Geliştirilme Amacı
> Her gün gelişen ve genişleyen OpenWRT Türkiye topluluğunun yeni katılımcıları,  
> Tercih edebilecekleri cihaz çeşitliliğinin az olması ve mevcut altyapılarının teknolojileri doğrultusunda  
> Özellikle DSL altyapılarda erişilebilen OpenWRT destekli DSL modemlerin yetersiz donanımları sebebiyle  
> İyi bir OpenWRT deneyimi için birden fazla cihaz kullanma ihtiyaçları doğabiliyor.  
> 
> Bu kısımda, donanımları daha kuvvetli olması sebebiyle edindikleri OpenWRT destekli routerlarını  
> DSL altyapıda kullanabilmeleri için OpenWRT üzerinde köprü moduna ihtiyaç duyuluyor.  
> Ancak OpenWRT'ye yeni adım atan kişiler için bu ayarları tamamlamak kolay olmayabiliyor.  
> 
> Hızlı kurulum sihirbazımız bu kısımda devreye girerek sadece bir ethernet kablosu ve terminal ile  
> Tüm kurulumu olabilecek en hızlı şekilde tamamlanabilir hale getirmeyi hedefliyor.

## 📥 Kuruluma Başlarken
> Tercihen kurulum yapacağınız cihazın tüm bağlantılarını sökün, sadece bilgisayar bağlı olarak kalsın.  
> Hızlı kurulum işleminde bilgisayarınızı, kablolu/kablosuz **`cihaza direkt bağlamanız`** daha sağlıklı olacaktır.  

## 🪄 Nasıl Kurulur?
* SSH/Telnet üzerinden cihazın terminal arayüzüne erişin ve ardından aşağıdaki komutları satır satır girin.  
```sh
wget https://frudotz.com/setup.sh -O setup.sh
chmod +x setup.sh
./setup.sh
```

* Script sorunsuz olarak çalışmaya başlarsa terminal arayüzünde şuna benzer yazılar göreceksiniz:  
```
OpenWRT Kopru Modu Hizli Kurulum Sihirbazi - @frudotz  
------------------------------------------------------
DSL/Router cihaz algilandi. DSL/Router yapilandirmasi uygulanacak.
dsl.sh/router.sh dosyasi indiriliyor...
```

## 🫠 Sorun Giderme
* Bu kısımda bir hatayla karşılaşmanız durumunda, eğer cihaza erişiminiz kesilirse:
    <details>
  <summary> Denetim masası üzerinden IP'nizi sabitleyerek cihaza SSH/Telnet üzerinden erişin.</summary>
      <br>
  <img width="auto" height="420" src="https://github.com/frudotz/openwrt-dsl-bridge-wizard/blob/main/denetim-masasi.png?raw=true">
    </details>
  
  * `cat /tmp/setup-frudotz.log` komutu ile `/tmp/setup-frudotz.log` dosya içeriğine ulaşın.
  * Çıkan hata loglarını Discord/Telegram üzerinden bana iletebilirsiniz.  
* Cihazda farklı ayarlar mevcutsa resetleyip tekrar sihirbazı çalıştırmayı deneyebilirsiniz.

## 🚀 Projeyi Bizimle Geliştirin
*Eksik gördüğünüz, geliştirilmesini istediğiniz kısımları **`📍 Pull Request/Issues`** kısmından iletebilir,*  
*aklınıza gelen çözümleri -kod düzeltmeleri de dahil- bizimle paylaşabilirsiniz.*  

-----------
🎀 Rehberimizi okuduğunuz için teşekkür ederiz!  
✨ İçeriği faydalı bulduysanız desteklemek için **⭐ Star** verebilirsiniz.  
