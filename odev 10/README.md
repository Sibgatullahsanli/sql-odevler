[PATİKA](https://app.patika.dev/) dev in Php dersleri çerçevesinde çelıştığımız SQL için verilen 10.cu ödevimiz.

[Patika Profilim](https://app.patika.dev/sibgat)

[GitHub Profilim](https://github.com/Sibgatullahsanli)

Ödev 10
Merhabalar,


Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.

Kolay Gelsin.

CEVAPLAR:

1. SELECT city,country FROM city 
LEFT JOIN country ON city.country_id=country.country_id;

2. SELECT payment.payment_id, customer.first_name, customer.last_name FROM payment
RIGHT JOIN customer ON payment.customer_id = customer.customer_id;

3. SELECT rental.rental_id, customer.first_name, customer.last_name FROM rental
FULL JOIN customer ON rental.customer_id = customer.customer_id;