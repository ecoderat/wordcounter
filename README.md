# wordcounter
bir kelimenin ne kadar tekrar ettiğini bulur.

# kullanım
aradığınız kelimeyi ve aradığınız kaynağı belirtin. 
```bash
curl -s https://www.gazeteduvar.com.tr/yazarlar/2020/01/30/yuruyen-merdivenin-sosyolojisi/ | go run wordcounter.go antropolojik
```
ya da
```
go run wordcounter.go antropolojik < yuruyen-merdivenin-sosyolojisi.txt
```
çıktısı
```
The input contains "antropolojik" 9 times.
```
