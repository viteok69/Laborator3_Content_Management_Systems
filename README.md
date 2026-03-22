> Realizat de studentul: Badia Victor \
> Grupa: I2301
> \
> Verificat de N. Nartea

## Scopul lucrării
Să înveți cum să creezi o temă WordPress personalizată, să înțelegi structura sa minimă și principiile de funcționare ale șabloanelor.

## Condiții
Pasul 1. Pregătirea mediului
1. În instalarea locală WordPress, accesează folderul wp-content/themes.
2. Creează un director pentru tema ta, de exemplu usm-theme.
   <img width="786" height="296" alt="image" src="https://github.com/user-attachments/assets/6ca11cb8-7bd0-47a6-a431-0745259ca819" />

3. Activează modul de depanare în wp-config.php, adăugând define('WP_DEBUG', true);.
  <img width="722" height="67" alt="image" src="https://github.com/user-attachments/assets/da680efa-4f2c-41b7-a02e-6c7f4d25cbe7" />

Pasul 2. Crearea fișierelor obligatorii ale temei
1. În folderul temei, creează fișierul style.css cu metadatele temei.
2. După metadate, poți adăuga reguli CSS de bază.
   <img width="495" height="290" alt="image" src="https://github.com/user-attachments/assets/7807cdab-c3a0-4674-abf3-7e6df48cd740" />

3. Creează fișierul index.php – șablonul principal al temei. Pentru început, adaugă o structură HTML de bază.
   <img width="517" height="247" alt="image" src="https://github.com/user-attachments/assets/e7c50969-968d-4b4d-ba35-a4df40780e75" />

Pasul 3. Componente comune ale șabloanelor
1. Creează fișierul header.php și mută acolo codul antetului site-ului (până la începutul conținutului principal).
   <img width="980" height="256" alt="image" src="https://github.com/user-attachments/assets/5a92a871-ca31-4976-9c28-acaeac2eae9c" />

2. Creează fișierul footer.php și mută acolo codul subsolului site-ului (după conținutul principal).
   <img width="1201" height="210" alt="image" src="https://github.com/user-attachments/assets/36912e92-86e5-4f2e-960a-ed1cb92b567b" />

3. În index.php, include header.php și footer.php folosind funcțiile get_header() și get_footer().
   <img width="1188" height="596" alt="image" src="https://github.com/user-attachments/assets/a5272661-d47a-4263-b8c9-b9871350e112" />

4. Pe pagina principală, afișează o listă cu ultimele 5 postări folosind bucla WordPress.
   <img width="1915" height="952" alt="image" src="https://github.com/user-attachments/assets/305464dc-41b3-4368-abd4-ed4036a9ea68" />

Pasul 4. Fișierul de funcții
1. Creează fișierul functions.php în directorul temei.
2. În functions.php, adaugă o funcție pentru încărcarea stilurilor temei folosind wp_enqueue_style().
   <img width="1408" height="234" alt="image" src="https://github.com/user-attachments/assets/10cc7a84-a76f-40bc-a7c8-e7b7888181d2" />

Pasul 5. Șabloane suplimentare
1. Creează fișierul single.php pentru afișarea unei postări individuale.
   <img width="440" height="344" alt="image" src="https://github.com/user-attachments/assets/81e39ca3-0aa4-4f4d-b075-0f056630cb5c" />

2. Creează fișierul page.php pentru afișarea paginilor.
   <img width="330" height="167" alt="image" src="https://github.com/user-attachments/assets/d39b7c5f-5ea7-4b31-bd3c-d50d3901c394" />

3. Creează fișierul sidebar.php pentru bara laterală și include-l în șabloanele relevante cu get_sidebar().
   <img width="334" height="149" alt="image" src="https://github.com/user-attachments/assets/099fdcba-7f5f-4447-94e6-08c4a329825a" />

4. Creează fișierul comments.php pentru afișarea comentariilor și include-l în single.php și page.php.
   <img width="433" height="504" alt="image" src="https://github.com/user-attachments/assets/91029a13-8c87-46a8-a89d-9109fccabb1f" />

5. Creează fișierul archive.php pentru afișarea arhivelor postărilor.
   <img width="401" height="373" alt="image" src="https://github.com/user-attachments/assets/02c8c64b-4db1-4328-b7a3-bfc43f5c86b4" />

Pasul 6. Stilizarea temei
1. Adaugă stiluri pentru elementele principale ale temei (antet, subsol, conținut, bara laterală).
   <img width="532" height="585" alt="image" src="https://github.com/user-attachments/assets/770cc9c8-2548-4df7-a36e-26cf5a54cf82" />

Pasul 7. Captura de ecran a temei
1. Adaugă în folderul temei fișierul screenshot.png – o imagine de previzualizare a temei (dimensiune 1200x900px).
   <img width="347" height="523" alt="image" src="https://github.com/user-attachments/assets/1bca3f0d-e672-449c-9c75-b919ac01fbca" />

Folderul temei cu screenshot salvat:
  <img width="1065" height="578" alt="image" src="https://github.com/user-attachments/assets/2e0e31a2-f202-4a50-8394-94f8dae4d1f0" />

Pasul 8. Activarea temei
1. În panoul de administrare WordPress, accesează secțiunea Appearance → Themes.
2. Găsește tema ta și activeaz-o.
  <img width="1376" height="513" alt="image" src="https://github.com/user-attachments/assets/a6d3d918-fe7f-4e07-8f11-d8ef98514d0e" />

3. Verifică modul în care site-ul este afișat cu tema ta.
   <img width="1919" height="868" alt="image" src="https://github.com/user-attachments/assets/baec2fdb-a17e-4903-a057-3a32587b6c05" />

Întrebări de control
1. Care sunt cele două fișiere obligatorii pentru orice temă WordPress?
   Cele două fișiere obligatorii sunt: style.css care conține metadatele temei (nume, autor, descriere) și stilurile CSS,
   index.php - șablonul principal care afișează conținutul site-ului.

2. Cum se includ părțile comune ale șabloanelor (header, footer, sidebar)?
   Se folosesc funcțiile WordPress: get_header(); get_footer(); get_sidebar();

3. Care este diferența dintre index.php, single.php și page.php?
   * index.php
     Este șablonul de bază (fallback)
     Se folosește dacă nu există alte șabloane specifice
     Afișează lista de postări (blog)
  * single.php
    Afișează o postare individuală (blog post)
    Se folosește când deschizi un articol
  * page.php
    Afișează o pagină statică (ex: Contact, Despre noi)
    Nu este pentru articole de blog

4. Care este rolul fișierului functions.php într-o temă?
   Fișierul functions.php este folosit pentru: adăugarea funcționalităților temei, încărcarea stilurilor și scripturilor, activarea unor funcții WordPress.
