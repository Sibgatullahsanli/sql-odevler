[PATİKA](https://app.patika.dev/) dev in Php dersleri çerçevesinde çelıştığımız SQL için verilen 9.cu ödevimiz.

[Patika Profilim](https://app.patika.dev/sibgat)

[GitHub Profilim](https://github.com/Sibgatullahsanli)

Ödev 9


Merhabalar,



Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

Kolay Gelsin.

CEVAPLAR:


1. 

SELECT city, country FROM city
JOIN country ON city.country_id = country.country_id;

2. 

SELECT payment_id, first_name, last_name FROM customer
JOIN payment ON customer.customer_id = payment.customer_id;

3. 

SELECT rental_id, first_name, last_name FROM customer
JOIN rental ON customer.customer_id = rental.customer_id;