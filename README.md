Jquery ile ülkeler ve şehirler
===================
> JQuery ile ülkeleri ve seçilen ülkeye göre şehirleri getiren script.


#### <i class="icon-file"></i> Kullanımı:
  

  script'i sayfaya dahil edin
   

    <script src="UlkeSehirHelper.min.js"></script>

**select** elementini form tag'inin arasına yazın (ülke)

    <select id="countries_states1" name="ulke"  class="form-control bfh-countries" data-country="TR" ></select>
**select** elementini form tag'inin arasına yazın (şehir)

    <select class="form-control bfh-states" name="sehir"  data-country="countries_states1" data-state="GAZ"></select>

**select** option attribute açıklamaları:

Attribute     | Açıklama
-------- | ---
country | 2 harfli ülke kodu. Ülke seçimi için kullanılır. blank false is boş olamaz. default :''
available    |Seçili ülkeleri getirir. Virgüllere ayırarak ülke kodu girilir. Default: ''
blank     |Boolean. Boş select option. Default: true

**Not:** select elementi form tag'leri arasına yazılmazsa script çalışmayacaktır.

script'in orjinal repo'su: https://github.com/winmarkltd/BootstrapFormHelpers
