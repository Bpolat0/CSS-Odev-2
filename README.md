# CSS > Ödev 2 > Eski Google Sayfasını Kopyalamak
## Site Son Görünümü
![img](/Images/Last%20view%20of%20the%20site.png)

## Kullandığım Kodlar Ve İşlevleri
### HTML Kodları
```
<form action=""></form>   : Html form etiketlerinin görevi, <form> ... </form> etiketleri içinde bulunan html kontrolleri aracılığıyla kullanıcılardan toplanan bilgileri server'a göndermektir.

<input type="text">   :  Alınacak olan bilgi sözel bir ifade ise kullanılır. Örneğin ; Ad ,adres vb.
```
### CSS Kodları
```
display: block; Bir elementin kutu şeklinde alan kaplamasını sağlayan kod parçasıdır. Kullanıldığı anda element yeni bir satırdan başlar.

text-align: center;   : Bir metne yatayda hizalama vermek için kullanılır.

margin:;   : Margin özelliği elementin etrafındaki boşluk olarak tanımlanır.

padding:;   : Padding ise “iç kenar boşluğu” olarak tanımlanabilir.

background-color: ;   : Arka plan rengi verir.

width: ;   : Genişlik değeri verir.

height: ;   : Yükseklik değeri verir.

float: left;   : CSS float özelliği web sayfalarında konulandırma ve düzen için kullanılır. Bir öğenin sayfa akışı içinde hangi yöne yaslanması gerektiğini ifade eder.
```
<!DOCTYPE html>
<html>
   <head>
   </head>
   <body>
      Patika.dev Linkim İçin Tıklayabilirsiniz:<br>
      <a href="https://app.patika.dev/bpolat">
         <img alt="Qries" src="https://patika-prod.s3.eu-central-1.amazonaws.com/staticFiles/patikaLogo.png"
         width="150" height="150">
      </a>
   </body>
</html>