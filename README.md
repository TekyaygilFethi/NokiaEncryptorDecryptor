# Nokia Encryptor-Decryptor
<img src="https://n11scdn.akamaized.net/a1/450/elektronik/diger-yedek-parca/nokia-6020-a-kalite-tus-takimi-bas-konuslu-nokia-telefon-icin__1031264186966757.jpg">
Bu proje cümlelerinizi ve kelimelerinizi Nokia klavyeye göre şifreleri ve bu şifreleri deşifre eder. Oluşturulan sözlük aşağıdaki gibidir.
<img src="https://i.ibb.co/TPZQGqF/Nokia-Dict.png">
<br>
Şifreleme kuralları bazıları aşağıdaki gibidir:
<ol>  

  <li>Büyük karakterler için öncelikle küçük karakterlerin tümünü gezmelisiniz. Örneğin "A" karakteri için önce 2 tuşundaki tüm küçük karakterleri 2'ye basa basa gezmeniz gerekmektedir. Örneğin büyük "A" için 2222 yapmalısınız. 
  <ul>
    <li>İlk 2 -> a </li>
    <li>İkinci 2 -> b </li>
    <li>Üçüncü 2 -> c </li>
    <li>Dördüncü 2 -> A </li>
  </ul>
</li>
  
 <li> Sayının kendisini yazmak istiyorsanız tüm karakter kombinasyonlarını gezmelisiniz. Örneğin "0" için 00 yapmalısınız.
  <ul>
    <li>İlk 0 -> " "</li>
    <li>İkinci 0 -> "0"</li>
  </ul>
  </li>
 <li>Kelimeler arası boşluk bırakmak için 0 kullanılır. 0, 00'ın aksine bir boşluk koyar. Örneğin 202 -> "a a" olur.</li>
 
 <li>Eğer iki karakter yan yanaysa ve aynı tuş üzerinden elde ediliyorsa (örneğin ab. Bu karakterlerin ikisi de 2 tuşundan elde edilir.) O zaman aynı tuştan ard arda iki karakter elde etmek için"-" kullanılır. "-" kulanılmazsa; 
    <ul>
      <li>a için 2</li>
      <li>b için 22</li>
      <li>Yanyana yazımları 222 olur. Ancak 222 encryption'da c'yi verir. </li>
     </ul>
    <br>
   Bunun önüne geçmek için ab -> 2-22 şeklinde yazılır. Aradaki - sayesinde tuşa basma sırası sıfırlanmış ve yeni bir karakter yazımına geçilmiş olur.
  
  </li>
  
 </ol>
