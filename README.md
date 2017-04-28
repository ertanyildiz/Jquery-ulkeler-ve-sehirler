# BootstrapFormHelpers
Jquery ile ülkeler ve şehirler

<select> elementi ile birlikte çalışır. önce ülkeler yüklenir. seçilen ülkeye göre şehirler yüklenir.

kullanımı:

scripti'i sayfaya dahil edin:
s
<script src="<?php echo base_url(); ?>UlkeSehirHelper.js"></script>

select elementini form tag'inin arasına yazın:s

<select id="countries_states1" name="ulke"  class="form-control bfh-countries" data-country="TR" ></select>

select options:
country	Two letters country code. To select a country. Required when blank is set to false. Default: ''
available	Comma separated list of two letters country code. To restrict the list of countries. Default: ''
flags	Boolean. To show the country flags. Default: false
blank	Boolean. To show a blank option. Default: trues
