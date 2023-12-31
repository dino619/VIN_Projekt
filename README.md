# VIN_Projekt
# Analiza Vremenskih Podatkov s Pomočjo Arduino Nano in Senzorja BME/BMP280

## Uvod

V tem poročilu predstavljamo analizo podatkov o vremenskih razmerah, pridobljenih s pomočjo Arduino Nano mikrokrmilnika in senzorja BME/BMP280. Poročilo zajema raziskavo in prikaz temperature, tlaka, višine nad morjem in vlažnosti v okolici. Poleg tega bomo razpravljali o postopku izvajanja meritve in prikazu teh podatkov na zaslonu.

Vedeti in razumeti trenutne vremenske razmere je ključnega pomena za številne aplikacije, vključno z meteorologijo, kmetijstvom, varnostjo in načrtovanjem aktivnosti na prostem. S tem projektom želimo ustvariti preprosto in učinkovito rešitev za merjenje in prikazovanje vremenskih podatkov v realnem času.

Sistem zajema tudi druge komponente, kot so modul NRF (Nordic Radio Frequency) za brezžično komunikacijo, tipke in piskac, ki so del prvotne zasnove vezja. Za potrebe tega poročila bomo osredotočeni izključno na zasnovo za merjenje in prikazovanje vremenskih podatkov.

# Seznam Potrebnih Delov

## Mikrokrmilnik – Arduino Nano

Arduino NANO je mikrokrmilnik, ki temelji na mikrokontrolerju Atmel AVR – ATmega328. Ima 14 digitalnih vhodno-izhodnih povezav, 8 analognih vhodov, kot tudi USB priključek za povezavo s računalnikom in napajanje. Velikost je zelo majhna in enostavna za uporabo, kar omogoča enostavno integracijo v različne projekte. NANO ima tudi možnost programiranja preko spletnega vmesnika za razvoj Arduino in drugih programskih jezikov, kot so C in C++. Napaja se prek USB vmesnika ali prek zunanjega napajalnika. Ima regulator napetosti, ki omogoča napajanje v območju 7-12 V.

## Senzor za Merjenje Vremenskih Parametrov – BME / BMP280

Senzor BME/BMP280 je visoko zmogljiv senzor za merjenje temperature, tlaka in vlažnosti z izjemno natančnostjo. Uporablja se v različnih vremenskih aplikacijah in ponuja natančne meritve za spremljanje vremenskih razmer. Ta senzor omogoča zanesljivo merjenje parametrov, ki so ključni za razumevanje vremenskih sprememb.

## Zaslon – KMR - 1.8 SPI

KMR - 1.8 SPI je 1,8-palčni zaslon s tehnologijo SPI, ki omogoča prikazovanje vizualnih informacij. Uporablja se za prikazovanje različnih podatkov, vključno s temperaturo, tlakom, višino in vlažnostjo, ki jih meri senzor BME/BMP280. Ta zaslon omogoča enostavno prikazovanje podatkov v realnem času na majhnem zaslonu.


# Seznam Potrebnih Delov

## Mikrokrmilnik – Arduino Nano

Arduino NANO je mikrokrmilnik, ki temelji na mikrokontrolerju Atmel AVR – ATmega328. Ima 14 digitalnih vhodno-izhodnih povezav, 8 analognih vhodov, kot tudi USB priključek za povezavo s računalnikom in napajanje. Velikost je zelo majhna in enostavna za uporabo, kar omogoča enostavno integracijo v različne projekte. NANO ima tudi možnost programiranja preko spletnega vmesnika za razvoj Arduino in drugih programskih jezikov, kot so C in C++. Napaja se prek USB vmesnika ali prek zunanjega napajalnika. Ima regulator napetosti, ki omogoča napajanje v območju 7-12 V.

<img src="https://github.com/dino619/VIN_Projekt/assets/77354182/21be8681-772f-48d3-8ff5-2b0e00cada9e" width="20%">

##  Senzor za Merjenje Vremenskih Parametrov – BME / BMP280

BME / BMP280 je digitalni barometrični senzor, ki se uporablja za merjenje vremenskih parametrov v okolju. To omogoča uporabnikom, da spremljajo spremembe vremenskih pogojev ter nadmorske višine. Je majhen in kompakten senzor, kar omogoča enostavno vgradnjo v različne naprave in projekte. Senzor podpira komunikacijo prek standardnih I2C (Inter-Integrated Circuit) in SPI (Serial Peripheral Interface) vmesnikov, kar omogoča enostavno povezovanje z mikrokrmilniki, kot je Arduino. Senzor lahko meri tlak v območju od 300 hPa do 1100 hPa, kar je primerljivo z razponom tlaka na različnih nadmorskih višinah. Senzor se tudi uporablja v meteoroloških postajah, napravah za sledenje višine, vremenskih balonih, pametnih napravah za nošenje in drugih aplikacijah, kjer je potrebno merjenje tlaka in temperature.

<img src="https://github.com/dino619/VIN_Projekt/assets/77354182/c4373aeb-35f8-4522-914b-439f59cc0080" width="20%">



##  KMR - 1.8 SPI

1.8-palčni SPI TFT (Thin-Film Transistor) zaslon je barvni zaslon, ki uporablja tehnologijo tankoslojnih tranzistorjev za prikaz slike. To omogoča bogate barve in visoko kakovost slike. Njegova resolucija je običajno 128x160 pikslov, kar omogoča jasen in podroben prikaz informacij. Ta zaslon se povezuje s pomočjo serijskega perifernega vmesnika (SPI - Serial Peripheral Interface). To omogoča enostavno povezovanje z mikrokrmilniki, kot je Arduino, ki podpirajo SPI komunikacijo.
Zasloni podpirajo risanje besedila, oblikovanje grafičnih elementov, kot so črte in pravokotniki ter prikazovanje ikon. To omogoča ustvarjanje interaktivnih uporabniških vmesnikov.

## Končni izdelek

![Screenshot_1](https://github.com/dino619/VIN_Projekt/assets/77354182/f9b569e6-edcf-4547-add6-df55c697baf0)

## Končni izdelek video
https://www.youtube.com/embed/VIDEO_ID](https://youtube.com/shorts/3uMXSxRAEEw




