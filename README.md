# Northwind.Mvc – Laboration 4

Hej! 👋  
Det här projektet är min lösning på **Laboration 4** i kursen *Fördjupad programmering*. Målet var att bygga vidare på ett befintligt MVC-projekt och få routing, databasanslutning och vyer att fungera korrekt – särskilt för kategorier.

---

### Vad jag har gjort
- Fixat routing för **`/category/{id}`** så man kan klicka på en kategori och se mer information om den.
- Kopplat projektet till **Northwind-databasen** så datan hämtas från riktiga tabeller.
- Skapat en **vy** som visar namn och beskrivning för varje kategori.
- Lagt till lite **Bootstrap-styling** så det ser bättre ut.
- Skrivit **3 tester** (med xUnit) som kontrollerar att routing, datahämtning och vyerna fungerar.

---

### Så här kör du projektet
1. Klona repot eller ladda ner det som ZIP.
2. Öppna lösningen i **Visual Studio**.
3. Kör `Update-Database` om databasen behöver byggas upp.
4. Starta projektet (F5) och navigera till t.ex. `https://localhost:5001/category/1` för att testa.

---

### Testning
Det finns 3 xUnit-tester som du kan köra via **Test Explorer** i Visual Studio. De testar bl.a. att:

- En kategori visas korrekt.
- Felaktigt ID ger "NotFound".
- Vyn returneras som förväntat.

---

### Skapad av
**Samir**  
Student på TUC Yrkeshögskola  
Laboration 4 – ASP.NET Core MVC
