# SQL Homework

- 1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

        CREATE TABLE employee(
            id INTEGER NOT NULL,
            name VARCHAR(50) NOT NULL,
            birthday DATE,
            email VARCHAR(100)
        );
----------------------------
- 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

        insert into employee (id, name, birthday, email) values (1, 'Brenna Mulhall', '1905-07-04', 'bmulhall0@go.com');

----------------------------
- 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

        UPDATE employee
        SET name = 'Albus Dumbledore'
        WHERE birthday = '1962-03-22'
        RETURNING *;

----------------------------
- 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

        DELETE FROM employee
        WHERE name = 'Brittaney Ysson'
        RETURNING *;
