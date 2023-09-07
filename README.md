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

# Opis Posameznih Komponent

## Arduino Nano

Arduino NANO je mikrokrmilnik, ki temelji na mikrokontrolerju Atmel AVR – ATmega328. Ima 14 digitalnih vhodno-izhodnih povezav, 8 analognih vhodov, kot tudi USB priključek za povezavo s računalnikom in napajanje. Velikost je zelo majhna in enostavna za uporabo, kar omogoča enostavno integracijo v različne projekte. NANO ima tudi možnost programiranja preko spletnega vmesnika za razvoj Arduino in drugih programskih jezikov, kot so C in C++. Napaja se prek USB vmesnika ali prek zunanjega napajalnika. Ima regulator napetosti, ki omogoča napajanje v območju 7-12 V.
