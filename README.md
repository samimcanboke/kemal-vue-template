# kemalcr ile vue entegrasyonu

Web paketi ile Kemal × Vue için şablon, webpack-dev-server ile çalışırken otomatik build destekler.
Kemal × Vue uygulamasını hızlı ve sorunsuz bir şekilde oluşturmayı sağlar.


## Yükleme

`git clone https://github.com/samimcanboke/kemal-vue-template.git`  
`cd kemal-vue-template`  
`yarn install`  
`shards install`  

## Geliştirme

Sunucuyu başlatma:  
`crystal run app/kemal-vue-template.cr`  
`yarn start`  

webpack-dev-server kullandığı port 3035 ve Kemalcr ise 3000 varsayılan portu kullanıyor.

uses port 3035 and kemal uses port 3000 as default.
webpack-dev-server'ın çalışırken rebuild işlemi için her iki işlemi de başlattığınızdan emin olun.

## Productiona alma
production için : `yarn build` çalıştırın

## Katkıda bulunun

1. Fork'la (<https://github.com/samimcanboke/kemal-vue-template>)
2. Kendi branch'ını oluştur. (`git checkout -b yeni-ozellik`)
3. Değişikliklerini commitle (`git commit -am 'Yeni Özellik'`)
4. Pushla (`git push origin yeni-ozellik`)
5. Yeni pull talebi oluştur

## Katkıda Bulunanlar

- [Samimcan BÖKE](https://github.com/samimcanboke) - Üretici
