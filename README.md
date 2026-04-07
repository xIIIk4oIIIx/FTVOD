# 🎬 FTVOD (Android & Smart TV VOD App)



<p align="center">

  <img src="https://img.shields.io/badge/Kotlin-Android_Dev-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />

  <img src="https://img.shields.io/badge/Jetpack_Compose-Modern_UI-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose" />

  <img src="https://img.shields.io/badge/Media3-ExoPlayer-3DDC84?style=flat-square&logo=android&logoColor=white" alt="ExoPlayer" />

</p>



Kompletna, natywna aplikacja multimedialna stworzona na platformę Android ze wsparciem dla interfejsów dużych ekranów (Android TV / Google TV). Aplikacja służy do przeglądania i streamowania zawartości wideo z zewnętrznych katalogów, zapewniając czysty, pozbawiony reklam interfejs oraz wbudowany system omijania zabezpieczeń anty-botowych.





## ✨ Główne funkcje



* **Headless Cloudflare Bypass:** Zastosowanie ukrytego komponentu WebView (`HeadlessLoginProvider`) do autoryzacji i omijania restrykcyjnych zabezpieczeń Cloudflare bez przerywania doświadczeń użytkownika (UX).

* **Ekstrakcja Strumieni Wideo (Anti-Adblock):** Autorski mechanizm wyodrębniania bezpośrednich linków do plików wideo (.mp4, .m3u8) ukrytych za systemami reklamowymi i w iframe'ach.

* **Natywny Odtwarzacz:** Zintegrowany, wysoce zoptymalizowany `ExoPlayer` (z najnowszej biblioteki Jetpack Media3) gwarantujący płynne odtwarzanie strumieni wideo, buforowanie i obsługę napisów.

* **Smart UI & Zarządzanie Stanem:** Obsługa paginacji danych, rozbudowane filtry gatunków/dat, zarządzanie lokalną historią oglądania oraz zakładką "Ulubione".

* **Wsparcie dla Android TV:** Interfejs zaprojektowany pod kątem obsługi pilotem (D-Pad Navigation).



## 🛠️ Architektura & Tech Stack



* **Kotlin:** W pełni nowoczesna baza kodu (Coroutines do programowania asynchronicznego).

* **Jetpack Compose:** Deklaratywny interfejs użytkownika zoptymalizowany pod kątem responsywności na różnych rozmiarach ekranów.

* **OkHttp & Jsoup:** Zaawansowane zapytania sieciowe, zarządzanie ciasteczkami sesyjnymi oraz scrapowanie / parsowanie węzłów HTML w locie.

* **Jetpack Media3 (ExoPlayer):** Natywny, potężny silnik do renderowania multimediów.

* **Coil:** Asynchroniczne, wydajne ładowanie okładek i grafik z wbudowanym mechanizmem cachowania.


## 📸 Zrzuty ekranu / UI Showcase

<img width="1426" height="793" alt="image" src="https://github.com/user-attachments/assets/f48ddbff-7f61-4de3-9616-ef6375da5079" />
<img width="1429" height="804" alt="image" src="https://github.com/user-attachments/assets/7a78fb31-d0fe-44ad-8fed-53e216f378fe" />
<img width="1434" height="809" alt="image" src="https://github.com/user-attachments/assets/afef59f1-d223-4e6d-b67c-4fa5f5d5c602" />
<img width="1428" height="798" alt="image" src="https://github.com/user-attachments/assets/15de86c8-0885-4674-8c7b-04fd10434193" />
<img width="1428" height="794" alt="image" src="https://github.com/user-attachments/assets/9f515e67-8413-44fd-ae54-ab504cf46d7a" />
<img width="1427" height="820" alt="image" src="https://github.com/user-attachments/assets/23878742-d834-44cb-9f57-57542e31a8d5" />
<img width="1426" height="810" alt="image" src="https://github.com/user-attachments/assets/aa00d908-c2b4-45f4-9f64-97a64bb83b7c" />








-----



**⚠️ Informacja Prawna (Disclaimer):**

*Aplikacja ma charakter projektu edukacyjnego (Proof of Concept), mającego na celu eksplorację natywnych technologii Android TV, biblioteki ExoPlayer oraz technik web-scrapingu. Kod źródłowy nie zawiera chronionych prawem autorskim treści wideo, a jedynie przetwarza ogólnodostępne w sieci linki.*

