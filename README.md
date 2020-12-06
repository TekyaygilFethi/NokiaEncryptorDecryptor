# Nokia Encryptor-Decryptor
<img src="https://n11scdn.akamaized.net/a1/450/elektronik/diger-yedek-parca/nokia-6020-a-kalite-tus-takimi-bas-konuslu-nokia-telefon-icin__1031264186966757.jpg">
Bu proje cümlelerinizi ve kelimelerinizi Nokia klavyeye göre şifreleri ve bu şifreleri deşifre eder. Oluşturulan sözlük aşağıdaki gibidir.
<img src="https://i.ibb.co/TPZQGqF/Nokia-Dict.png">
<br>
Şifreleme kuralları bazıları aşağıdaki gibidir:

1. Büyük karakterler için öncelikle küçük karakterlerin tümünü gezmelisiniz. Örneğin "A" karakteri için önce 2 tuşundaki tüm küçük karakterleri 2'ye basa basa gezmeniz gerekmektedir. Örneğin büyük "A" için 2222 yapmalısınız. 
  a. İlk 2 -> a
  b. İkinci 2 -> b
  c. Üçüncü 2 -> c
  d. Dördüncü 2 -> A
  
 2. Sayının kendisini yazmak istiyorsanız tüm karakter kombinasyonlarını gezmelisiniz. Örneğin "0" için 00 yapmalısınız.
  a. İlk 0 -> " "
  b. İkinci 0 -> "0"
  
 3. Kelimeler arası boşluk bırakmak için 0 kullanılır. 0, 00'ın aksine bir boşluk koyar. Örneğin 202 -> "a a" olur.
 
 4. Eğer iki karakter yan yanaysa ve aynı tuş üzerinden elde ediliyorsa (örneğin ab. Bu karakterlerin ikisi de 2 tuşundan elde edilir.) O zaman aynı tuştan ard arda iki karakter elde etmek için"-" kullanılır. "-" kulanılmazsa; 
    * a için 2
    * b için 22
    * Yanyana yazımları 222 olur. Ancak 222 encryption'da c'yi verir. 
    <br><br>
    <p>
Bunun önüne geçmek için ab -> 2-22 şeklinde yazılır. Aradaki - sayesinde tuşa basma sırası sıfırlanmış ve yeni bri karakter yazımına geçilmiş olur.
  </p>
