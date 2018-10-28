# Kommunity App
 
Proje gereksinim dokumani: [gdoc](https://docs.google.com/document/d/1P9znOKfQIHDP3BVS5ptvFgzSLmL0vo4WTAZrcKatFBA)

Server: node.js **"8.11.4"** (eger node versiyonunuzu degistirmek istiyorsaniz bakiniz [nvm](https://github.com/creationix/nvm#node-version-manager---) or [nvs](https://github.com/jasongin/nvs#nvs-node-version-switcher)) <br/>
Client: react.js <br/>
[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

## Misyonumuz
buraya misyon eklenecek

## Projeyi kendi bilgisayarinda kurma

- **Clone or download** butonuna tikla ve linki kopyala
- Terminaline **git clone {your link}** seklinde yaz
- Daha sonra **cd kommunity-frontend** yaz
- Son olarak **npm install** yada **yarn**

## Projeyi kendi bilgisayarinda calistirma

- [Bu](https://github.com/Kommunity-app/kommunity-backend) adresten projenin backendini indir ve calistir
- makinene indirdigin kommunity-frontend pojesine git ve **npm start** yada **yarn start** komutunu calistir
- Tarayicidan **[localhost:3000](http://localhost:3000/)** adresine git

## Projede kullanilan npm komutlari hakkinda bilgi

NPM komutu calistirma: `npm run KOMUT` yada `yarn KOMUT`

Mevcut komutlar:

- `"build"`: projeyi yayinlayacakken kullan

- `"tailwindcss"`: projeyi yayinlayacakken kullan

- `"start"`: projeyi yayinlayacakken kullan

- `"start:prod"`: projeyi yayinlayacakken kullan

- `"check-if-not-committed"`: projeyi yayinlayacakken kullan

- `"check-travis"`: projeyi yayinlayacakken kullan

- `"test"`: projeyi yayinlayacakken kullan

- `"cover"`: projeyi yayinlayacakken kullan

- `"lint"`: projeyi yayinlayacakken kullan

- `"lint-fix"`: projeyi yayinlayacakken kullan

## Yapilan degisiklikten sonra PR olusturma

- Bu adima baslamadan once [buradan](#github-command-docs) bu adimda kullanilacak komutlarin detayli bilgisini bulabilirsin burada sadece nasil kullanacagin yazacak

- (**github ui**) Projeden bir [Fork](https://github.com/Kommunity-app/kommunity-frontend/fork) olusturun dosyalari kendi forkunuza gondermeniz gerek
- (**terminal**) Kendi branchini olusturmak icin `git checkout -b {your branch name}`
- (**terminal**) Degisiklikleri kaydettikten sonra `git add .` komutunu yaz
- (**terminal**) Staging area daki dosyaliri branch e gondermek icin `git commit -m "your commit message"` komutunu yaz
- (**terminal**) Projeyi githuba gondermek icin `git push -u {your fork link} {your branch name}` komutunu yaz
- (**github ui**) Daha sonra yeni bir **Pul Request** olustur projenin lint ve unit testleri yapildiktan sonra review edilecek hersey dogruysa proje dev branchine merge edilecek

## Kullanilan Teknolojiler

- [nodejs](#nodejs)
- [react](#react)
- [razzle](#razzle)
- [axios](#axios)
- [react router](#react-router)
- [redux](#redux)
- [styled components](#styled-components)
- [eslint](#eslint)
- [enzyme](#enzyme)
- [jest](#jest)
- [tailwind css](#tailwind-css)
- [babel](#babel)


