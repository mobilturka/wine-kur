# wine-kur

.deb paketi indirme linki:
https://github.com/mobilturka/wine-kur/releases/tag/current

Bu paket Debian ve Debian tabanlı dağıtımlar için resmi depodaki Wine paketini sisteme kurar. 

ÖNEMLİ: wine-kur.deb paketini çalıştırmadan önce sisteminizde i386 mimarisi ekli olmalı!
Sisteme i386 mimarisi eklemek için terminalde aşağıdaki komutu çalıştırınız.

```
sudo dpkg --add-architecture i386 && sudo apt update
```

Wine kurulumu sonrasında: 
"winecfg" komutu ile wine mono yükleyiciyi yükleyelim.

Menü de Wine kategorisinin eklenmiş olduğunu göreceksiniz. Wine ile kurulan uygulamalar burada yer alır. 

"wine --version" komutu ile de versiyon kontrolü yapabilirsiniz.
