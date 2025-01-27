# jskendimenotlar

### Array (Dizi) Metodları

1. **`push(element)`**: Dizi sonuna bir veya daha fazla eleman ekler ve yeni uzunluğunu döndürür.
2. **`pop()`**: Dizinin sonundaki elemanı çıkarır ve döndürür.
3. **`shift()`**: Dizinin başındaki elemanı çıkarır ve döndürür.
4. **`unshift(element)`**: Dizi başına bir veya daha fazla eleman ekler ve yeni uzunluğunu döndürür.
5. **`splice(start, deleteCount, item1, item2, ...)`**: Belirli bir konumdan eleman ekler veya çıkarır.
6. **`sort(compareFunction)`**: Dizi elemanlarını sıralar.
7. **`reverse()`**: Dizi elemanlarını tersine çevirir.
8. **`fill(value, start, end)`**: Dizinin belirli bir bölümünü (veya tamamını) belirli bir değer ile doldurur.
9. **`concat(array1, array2, ...)`**: İki veya daha fazla diziyi birleştirir ve yeni bir dizi döndürür.
10. **`slice(start, end)`**: Dizinin belirli bir bölümünü alır ve yeni bir dizi döndürür.
11. **`join(separator)`**: Dizi elemanlarını birleştirip bir string olarak döndürür.
12. **`map(callback)`**: Dizi elemanlarını belirli bir işleve göre dönüştürerek yeni bir dizi döndürür.
13. **`filter(callback)`**: Belirli bir koşulu sağlayan elemanları içeren yeni bir dizi döndürür.
14. **`reduce(callback, initialValue)`**: Dizi elemanlarını bir değere indirger.
15. **`find(callback)`**: Belirli bir koşulu sağlayan ilk elemanı döndürür.
16. **`findIndex(callback)`**: Belirli bir koşulu sağlayan ilk elemanın indeksini döndürür; bulunamazsa `-1` döner.
17. **`some(callback)`**: Dizi elemanlarının en az birinin belirli bir koşulu sağlayıp sağlamadığını kontrol eder.
18. **`every(callback)`**: Dizi elemanlarının hepsinin belirli bir koşulu sağlayıp sağlamadığını kontrol eder.
19. **`indexOf(element)`**: Dizi içinde belirli bir elemanın ilk bulunduğu konumu döndürür; bulunamazsa `-1` döner.
20. **`lastIndexOf(element)`**: Dizi içinde belirli bir elemanın son bulunduğu konumu döndürür; bulunamazsa `-1` döner.
21. **`includes(element)`**: Dizi içinde belirli bir elemanın olup olmadığını kontrol eder ve boolean döner.
22. **`forEach(callback)`**: Dizi elemanları üzerinde belirli bir işlem gerçekleştirir.
23. **`length`**: Dizi uzunluğunu döndürür.
24. **`entries()`**: Dizi elemanlarını anahtar-değer çiftleri olarak içeren bir dizi döndürür.
25. **`keys()`**: Dizi elemanlarının indekslerini içeren bir dizi döndürür.
26. **`values()`**: Dizi elemanlarını içeren bir dizi döndürür.

### String (Stringler) Metodları

1. **`charAt(index)`**: Belirli bir konumdaki karakteri döndürür.
2. **`charCodeAt(index)`**: Belirli bir konumdaki karakterin Unicode değerini döndürür.
3. **`concat(string1, string2, ...)`**: İki veya daha fazla stringi birleştirir ve yeni bir string döndürür.
4. **`includes(substring)`**: Bir stringin içinde belirli bir alt stringin olup olmadığını kontrol eder.
5. **`indexOf(substring)`**: Bir alt stringin ilk bulunduğu konumu döndürür.
6. **`lastIndexOf(substring)`**: Bir alt stringin son bulunduğu konumu döndürür.
7. **`slice(start, end)`**: Stringin belirli bir bölümünü alır.
8. **`substring(start, end)`**: Stringin belirli bir bölümünü alır.
9. **`substr(start, length)`**: Belirli bir konumdan başlayarak belirli bir uzunlukta string döndürür.
10. **`split(separator)`**: Stringi belirli bir ayırıcıya göre parçalara ayırır ve bir dizi döndürür.
11. **`toLowerCase()`**: Tüm karakterleri küçük harfe çevirir.
12. **`toUpperCase()`**: Tüm karakterleri büyük harfe çevirir.
13. **`trim()`**: Stringin başındaki ve sonundaki boşlukları temizler.
14. **`replace(searchValue, newValue)`**: Belirli bir alt stringi başka bir string ile değiştirir.
15. **`replaceAll(searchValue, newValue)`**: Belirli bir alt stringin tüm örneklerini başka bir string ile değiştirir.
16. **`repeat(count)`**: Stringi belirli bir sayıda tekrar eder.
17. **`startsWith(searchString)`**: Stringin belirli bir alt string ile başlayıp başlamadığını kontrol eder.
18. **`endsWith(searchString)`**: Stringin belirli bir alt string ile bitip bitmediğini kontrol eder.
19. **`match(regex)`**: Stringin belirli bir düzenli ifade ile eşleşip eşleşmediğini kontrol eder.
20. **`search(regex)`**: String içinde belirli bir düzenli ifade arar.
21. **`length`**: Stringin uzunluğunu döndürür.


### Object (Nesneler) Metodları

1. **`Object.keys(object)`**: Nesnedeki tüm keyleri (properties) içeren bir dizi döndürür.
2. **`Object.values(object)`**: Nesnedeki tüm değerleri içeren bir dizi döndürür.
3. **`Object.entries(object)`**: Anahtar-değer çiftlerini içeren bir dizi döndürür.
4. **`Object.assign(target, ...sources)`**: Bir veya daha fazla nesneyi `target` nesnesine birleştirir ve döner.
5. **`Object.freeze(object)`**: Bir nesneyi dondurur, böylece değiştirilemez hale gelir.
6. **`Object.seal(object)`**: Bir nesneye yeni özellik eklemeyi engeller, ancak mevcut özelliklerin değerlerini değiştirmeye izin verir.
7. **`Object.getOwnPropertyNames(object)`**: Nesnedeki tüm özellik adlarını içeren bir dizi döndürür.
8. **`Object.hasOwnProperty(property)`**: Belirli bir özelliğin nesnenin kendi özelliği olup olmadığını kontrol eder ve boolean döner.
9. **`Object.create(prototype)`**: Belirtilen prototip nesnesi ile yeni bir nesne oluşturur.
10. **`Object.defineProperty(object, property, descriptor)`**: Belirtilen özelliği nesneye ekler veya var olan özelliğin tanımını değiştirir.
11. **`Object.defineProperties(object, descriptors)`**: Birden fazla özelliği nesneye ekler veya mevcut özelliklerin tanımlarını değiştirir.
12. **`Object.getOwnPropertyDescriptor(object, property)`**: Belirtilen özelliğin özellik tanımını döndürür.
13. **`Object.getPrototypeOf(object)`**: Belirtilen nesnenin prototipini döndürür.
14. **`Object.setPrototypeOf(object, prototype)`**: Belirtilen nesnenin prototipini ayarlar.

![arr-method](https://github.com/user-attachments/assets/8315b525-ad71-4e1f-acec-d53260ea164e)


bir değişken bir kere tanımlandıktan sonra istediğin yerde kullanılabilir , without let const 
document sayfa içeriğini değiştiren bir özellik
% -->  bölmeden kalanı bulur 
call: fonksiyon içine dışarıdan obje çağırma ,sonra fonksiyonda belirli işlemler yapabilirsin
apply: fonksiyon içine dışarıdan array çağırma ,sonra fonksiyonda belirli işlemler yapabilirsin
bind : başlangıçdaki this değeini değişmek
slice,substirng --> js deki stringlere kesme özelliği
aralarındaki tek fark
slice --> negatif durumlarda da keser
substring --> negatif durumlarda kesme işlemi yapmaz
package.json --> js kutuphaneler dosyası --> npm init -y --> npm i axios / axios yerine istediğin kütüphane

Hangi Kütüphaneleri/Framework'leri Öğrenmelisin?

    Frontend odaklıysan: React.js, Next.js, Vue.js, Angular.
    Backend geliştirme için: Node.js, Express.js, Nest.js.
    Modern projeler için: TypeScript çok yaygın ve kullanışlıdır.


seTiemout bir callbackdir , işlemleri sıralamak , bekletmek için kullanılır

breaked notation,dot(.) notation çağırma methodları (obje için)    obje.name  obje["name] 
nested object --> obje içinde obje demek

if --> eğer 
else if --> ya da böyleyse + (bi koşul ekler)
else --> değilse bu

switch case --> birden fazla koşul varsa (if le benzer)

continue atlar


- **`for` Döngüsü**: Belirli sayıda tekrar yapılacaksa.
- **`while` Döngüsü**: Koşul sağlandığı sürece tekrar yapılacaksa.
- **`do...while` Döngüsü**: En az bir kere çalışması gereken ve koşula bağlı olarak devam edecek döngüler için.
- **`if...else`**: Tek bir koşul veya az sayıda koşul varsa ve duruma göre farklı işlemler yapılması gerekiyorsa.
- **`switch`**: Çok sayıda sabit durumun kontrol edilmesi gerekiyorsa.
