# UI Web Test Automation Framework
## Tools used:
- Selenium
- Cucumber
- Java
- JUnit
- Intellij IDEA

## Penjelasan Proyek
Test ini dilakukan pada Halaman Login pada web target. Beberapa tes yang dilakukan antara lain yaitu User akan memasukan username dan password yang Valid dan berhasil login kedalam web, 
kemudian user memasukan username yang valid dan password invalid, tes ini ingin menguji tampilan error web dengan memunculkan teks error dan user tidak berhasil login. Tes terakhir yaitu
dengan menggunakan boundaries atau batasan pada field username / password, pada tes ini dilakukan tes jika user memasukan username dengan karakter sangat panjang, tes ini ingin menguji 
tampilan error web dengan memunculkan teks error dan user tidak berhasil login.

  
## Scenario
- Visit website https://www.saucedemo.com/
- User Login with valid username and password
- User Login with invalid username and password 
- User Login with boundaries (long username)

## Testing Browser
Test ini menggunakan Chrome
