# 🍔 YBS Burger & Tıklama Oyunu

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0078D6?style=for-the-badge&logo=windows&logoColor=white)

Kullanıcıların 10 saniyelik refleks oyunuyla sanal para kazandığı ve kazandıkları bakiyeyle kendi özel burgerlerini oluşturup satın alabildiği **C# Windows Forms** masaüstü uygulamasıdır.

---

## 🎮 Uygulama Görselleri ve Oynanış

### 1. Oyun Sekmesi (Para Kazanma)
Kullanıcı adını girip **Başla** butonuna bastığında 10 saniyelik geri sayım başlar. Ekranda rastgele konumlarda beliren gülen yüze her tıklandığında bakiye **20 ₺** artar. Süre dolduğunda kullanıcı adı ve toplam kazancı sağ taraftaki **Kullanıcı Listesi**'ne kaydedilir.

<p align="center">
  <img src="oyun-demo.gif" alt="Oyun Oynanış Demosu" width="750">
</p>

### 2. YBS Burger Sekmesi (Sipariş & Ödeme)
Kullanıcı listeden kendi profilini seçerek kazandığı bakiyeye uygun şekilde **köfte**, **ekmek** ve **ekstra malzemeleri** özelleştirip adet belirleyerek ödeme yapabilir.

<p align="center">
  <img src="ybs-burger.png" alt="YBS Burger Sipariş Ekranı" width="750">
</p>

---

## ✨ Özellikler

* **Refleks ve Skor Sistemi:** 10 saniyelik zamanlayıcı (`Timer`) ve dinamik konumlanan hedef mekaniği.
* **Kullanıcı ve Bakiye Takibi:** Oyun sonunda kazanılan tutarın kullanıcı adıyla birlikte listeye aktarılması ve sipariş ekranında seçilebilmesi.
* **Özelleştirilebilir Burger Menüsü:**
  * **Köfte Seçimi:** Tek Köfte (+20 ₺), Çift Köfte (+40 ₺), Üçlü Köfte (+75 ₺)
  * **Ekmek Seçimi:** Klasik (+0 ₺), Tam Buğday (+10 ₺), Brioche (+15 ₺)
  * **Ekstra Malzemeler:** Pastırma (+25 ₺), Soğan Halkası (+10 ₺), Mantar (+8 ₺), Jalapeno (+7 ₺), Cheddar (+12 ₺)
* **Bakiye Kontrolü:** Seçilen malzemeler ve adede göre toplam tutar hesaplama ve kullanıcının mevcut bakiyesine göre ödeme doğrulaması.

---

## 🛠️ Kullanılan Teknolojiler

* **Dil:** C#
* **Arayüz:** Windows Forms (WinForms)
* **Geliştirme Ortamı:** Visual Studio
