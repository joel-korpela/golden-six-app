# 🏋️ Golden Six – PWA-treeniappi

Arnoldin Golden Six -treeniohjelma iPhonelle. Toimii täysin offline-tilassa ja tallentaa tiedot puhelimen muistiin.

---

## 📱 Asennus iPhoneen (2 min)

1. **Avaa Safari** iPhonessa *(ei Chrome tai Firefox!)*
2. Mene appin osoitteeseen
3. Paina **Jaa-painike** (neliö, jossa ylöspäin osoittava nuoli) ↑
4. Selaa alaspäin ja valitse **"Lisää Koti-valikkoon"**
5. Paina **"Lisää"** oikeassa yläkulmassa
6. Valmis! 🎉 Appsi näkyy nyt kotinäytöllä kuin mikä tahansa appi.

---

## ✅ Ominaisuudet

- **Arnold's Golden Six** -ohjelma (fullbody, 3 × viikossa)
  - Takakyykky – 4 × 10
  - Penkkipunnerrus – 3 × 10
  - Leuanveto – 3 × max
  - Pystypunnerrus (niskan takaa) – 4 × 10
  - Hauiskääntö tangolla – 3 × 10
  - Istumaannousut – 4 × 20
- ✅ Rastita sarjat tehdyksi
- 📊 Kirjaa paino (kg) ja toistot jokaiselle sarjalle
- ⏱️ Automaattinen palautusajastin sarjojen välille (2 min / 1 min vatsaliikkeille)
- 🔔 Ajastin hälyttää ääni + värinällä kun palautus on ohi
- 📅 Treenihistoria päivämäärän kera
- 📈 Edellisen treenin painot näkyvät viitteenä
- ☁️ iCloud-varmuuskopiointi (lataa/palauta JSON-tiedosto)
- 💾 Kaikki data tallennetaan vain omalle puhelimellesi (localStorage)
- 🌐 Toimii täysin offline-tilassa – ei vaadi internetiä

---

## ☁️ iCloud-varmuuskopiointi

1. Avaa **☁️ iCloud** -välilehti appissa
2. Paina **"Tallenna iCloudiin"** – JSON-tiedosto latautuu puhelimeesi
3. Tallenna tiedosto **iCloudin Tiedostot-appiin**
4. Tiedosto synkronoituu automaattisesti iCloudiin ✅

Voit palauttaa datan milloin tahansa "Palauta varmuuskopiosta" -napilla.

> ⚠️ **Tärkeää:** Ota varmuuskopio ennen puhelimen vaihtoa tai Safarin välimuistin tyhjennystä!

---

## 🛠️ Tekniset tiedot

- Yksittäinen `index.html`-tiedosto – ei ulkoisia riippuvuuksia
- Kaikki koodi inline (HTML + CSS + JavaScript)
- Tiedot tallennetaan `localStorage`-muistiin
- PWA-metatagit iOS-kotinäyttöasennusta varten
- Tumma teema, optimoitu iPhonen näytölle
