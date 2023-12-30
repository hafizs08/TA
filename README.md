## Konfigurasi Database MySQL
import mipoka.sql dengan nama database mipoka

Aplikasi ini menggunakan MySQL sebagai database. Anda perlu mengonfigurasi koneksi database dengan mengubah properti berikut dalam berkas `application.properties` atau `application.yml`:

- `spring.datasource.url`: URL koneksi ke database MySQL. Pastikan untuk mengganti `localhost:3306/mipoka` dengan URL database MySQL yang sesuai dengan pengaturan Anda.
- `spring.datasource.username`: Nama pengguna MySQL Anda.
- `spring.datasource.password`: Kata sandi MySQL Anda.

Berikut adalah contoh konfigurasi yang dapat Anda gunakan:

```properties
spring.datasource.url = jdbc:mysql://localhost:3306/mipoka?useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC
spring.datasource.username = root
spring.datasource.password = 

Setelah mengonfigurasi database, dapat menjalankan aplikasi Spring Boot Anda dengan terminal menggunakan perintah
./mvnw spring-boot:run 

pastikan sudah mempunyai Java Development Kit (JDK)

Setelah aplikasi berhasil dijalankan, Anda dapat mengaksesnya melalui browser atau postmat  pada endpoint yang sesuai di Api document

https://docs.google.com/document/d/1zAcf9kd2B8xhF1jNc1HmPFxB_YRcdTFXhvUJYeoNpkc/edit?usp=sharing
