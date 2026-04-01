# Datu-bazes-un-SQL

Apmācības prezentācija, kas sagatavota kā daļa no kursa par datu struktūrām un vaicājumu valodas pamatiem.

## 👥 Autori
* **Ņikita Dubovskis**
* **Devids Klimko**

---

## 🚀 Par projektu
Šis projekts ir soli pa solim sniegta rokasgrāmata par datu bāzes pamatiem. Materiāls vienkāršā valodā izskaidro sarežģītus tehniskos terminus:
* **Datu bāze** ir "liela kaste vai piezīmju grāmatiņa" informācijas glabāšanai.
* **SQL** ir "maģiska valoda" saziņai ar datoru.

## 📚 Galvenās tēmas
### 1. Datu bāzes koncepcijas
* Kāpēc ir nepieciešamas datu bāzes (efektivitāte, drošība, integritāte).
* Relāciju (MySQL) un nerelāciju (MongoDB) datu bāzu salīdzinājums.

### 2. Datu struktūra
* Tabulas, rindas un kolonnas.
* **Primārā atslēga** un **Ārējā atslēga**.
* Relāciju veidi: 1:1, 1:N, M:N.

### 3. SQL valoda
Šajā prezentācijā ir apskatītas galvenās komandu grupas:
* **DDL**: CREATE, ALTER, DROP
* **DML**: INSERT, UPDATE, DELETE
* **DQL**: SELECT
* **TCL**: COMMIT, ROLLBACK

---

## 🛠 Praktiskie vingrinājumi
Ietver vingrinājumus par Product tabulas noformēšanu un vaicājumu rakstīšanu.

**SQL vaicājuma piemērs no kursa:**
```sql
-- Meklēt produktus, kas pārsniedz 20
SELECT * FROM Produkti
WHERE Price > 20
ORDER BY Price ASC;
