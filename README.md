# **A)**


### A) Vásárló osztály létrehozása

Hozzon létre egy osztályt a vásárlók tárolására. Minden vásárlónak ismert a neve, email címe és keretösszege pénznem értékben, amit a vásárlásokra szánhat.

* A név módosítható legyen, az email cím és a keretösszeg viszont nem változtatható meg a vásárló létrehozása után közvetlenül.
* A vásárló létrehozásakor az email címet és a keretösszeget kötelező megadni.
* A vásárló nem jöhet létre negatív keretösszeggel. Ilyenkor a program dobjon kivételt (InvalidOperationException vagy saját NegativeBalanceException).
* A nulla keretösszeg megengedett, de ebben az esetben a vásárló nem tud vásárolni.

## Feladatok

### 1. feladat

* Hozzon létre egy vásárlót -500 Ft keretösszeggel. Jelenítse meg a képernyőn a keletkezett kivétel szövegét!
* Hozzon létre egy érvényes vásárlót, és írja ki az adatait! A vásárló adatai a következő formátumban jelenjenek meg: Vásárló Valér (vasarlo.valer@sokatveszek.hu) -> 20000 Ft

---
    
### 2. feladat

A keretösszeg pozitív értékkel növelhető, és az osztály tartsa nyilván, hogy hányszor történt növelés.

* Növelje Valér keretösszegét 5000 Ft-tal, majd 10 000 Ft-tal.
* Írja ki a képernyőre Valér objektumát használva a keretösszeg-növelések számát!

A vásárlóról megállapítható legyen, hogy:

* Vásárolhat-e (van-e legalább 1 Ft keretösszege).
* Egy adott összegnél többet vásárolhat-e (pl. egy adott termék árát megengedheti-e magának).

**Feladat:** Írja ki a képernyőre, hogy **Valér meg tudja-e vásárolni egy 45 000 Ft-os monitort!**

---

### 3. feladat

Fejlessze ki a vásárlás lehetőségét a vásárló osztályban!

* Csak pozitív pénzösszegű vásárlás engedélyezett.
* A vásárló nem vásárolhat többet, mint amennyi pénze van, ellenkező esetben dobjon kivételt (InvalidOperationException vagy saját InsufficientFundsException).

**Feladatok:**

* Vásároljon Valér 200 000 Ft értékben, és kapja el a keletkezett kivételt!
* Vásároljon Valér 10 000 Ft értékben, majd írja ki a képernyőre Valér új keretösszegét!

---

### 4. feladat

Hozzon létre még négy vásárlót, amelyek közül egynek nulla a keretösszege! \
 Írja ki az adataikat a képernyőre a megadott formátumban.
