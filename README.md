# SmartHome
- # Piwnica
  - ## Hydrofor
    - ### Stany pompy

        Odczyt stanów pompy:

        * Zasilanie
        * Praca
        * Błąd

        "Zasilanie" oraz "Błąd" przy pomocy przekaźników [PK-1P 230 V](https://www.fif.com.pl/pl/przekazniki-elektromagnetyczne/306-przekaznik-elektromagnetyczny-pk-1p-230-v.html),
        a "Praca" przy pomocy styku pomocniczego **22DILE**

    - ### Reset pompy
    
      - #### Automatyczny

        Zdalny reset logiki/timera przy pomocy [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/)

      - #### Manualny

        Przełącznik **M22-WRK** podłączony do **Shelly 1**

   - ## Zimna woda
      - ### Pomiar przepływu wody
      
        Pomiar cieczy z wykorystaniem czujnika [YF-B7](https://www.seeedstudio.com/Water-Flow-Sensor-YF-B7-p-2884.html).
        
        Umiejscowione za wyjściem z licznkika wody (Pomiar żużycia wody państwowej) oraz za zbiornikiem wody ze studni
        
      - ### Zawór trójdrożny

        Połączenie wody państwowej i wody ze studni przełączanie manualnie lub automatycznie na podstawie danych z hydroforu.
        
        Można wykorzystać zawór **IB-Q20-3** lub **IB-Q25-3**
        
        [Instrukcja](http://www.download.insbud.net/pl/manuals/pl_ib-qxx-3.pdf)
   - ## WiFi
   
    Access Point [MikroTik RB760iGS](https://mikrotik.com/product/hex_s) obok inwertera 
    
   - ## Skrzynka Rozdzielcza: Remastered

   
- # Licznik energii
  Pomiar energii zużytej, oddanej i autokonsumpcji
  
  Czujnik [Shelly 3EM](https://shelly.cloud/products/shelly-3em-smart-home-automation-energy-meter/)
  
- # Lista zakupów
   
    Komponent | Przeznaczenie | Lokalizacja | Sklep | Ilość 
    ------------ | ------------- | ------------- | ------------- | -------------
    22DILE | Stycznik pomocniczy 22DILE | Hydrofor | [Allegro](https://allegro.pl/oferta/22dile-modul-stykow-pomocniczych-2z-2r-mont-cen-10533039511) | 1
    IB-Q25-3 | Połączenie wody ze studni i państwowej | Hydrofor | [Allegro](https://allegro.pl/oferta/zawor-trojdrozny-silownik-3-drogowy-dn20-10184767149) | 1
    M22-WRK | Wyłączenie logiki w hydroforze | Hydrofor | [Allegro](https://allegro.pl/oferta/przelacznik-m22-wrk-k10-10896796019) | 1
    MEAN WELL MDR-40-24 | Zasilanie 24V | Rozdzielka | [Allegro](https://allegro.pl/oferta/zasilacz-din-mdr-40-24-24v-1-7a-40w-mean-well-8725147785) | 1
    MikroTik RB760iGS | Router pod inwerter | Inverter | [Allegro](https://allegro.pl/oferta/mikrotik-routerboard-rb760igs-hex-s-sfp-8437932024) | 2
    PK-1P 230 V | Przekaźniki do hydroforu | Hydrofor | [Allegro](https://allegro.pl/oferta/f-f-przekaznik-elektromagnetyczny-pk-1p-230v-9297384944) | 3
    Przetwornica XY-3606 | Przetwornica na 5V do ESP32 | Rozdzielka | [Allegro](https://allegro.pl/oferta/przetwornica-xy-3606-step-down-z-9-36v-do-5v-5a-9694436548) | 2
    Skrzynka Rozdzielcza 600x500 | --- | Hydrofor | [Allegro](https://allegro.pl/oferta/skrzynka-szafa-obudowa-abs-plastikowa-600x500x220-9786926675) | 1
    Stycznik DILM 15-10 7.5kW | Zdalne wyłączanie płyty indukcyjnej | Rozdzielka | [Allegro](https://allegro.pl/oferta/stycznik-dilm-15-10-7-5-kw-cewka-24v-ac-1no-10904455058) | 1
    Shelly 1 | Zdalne wyłączanie płyty indukcyjnej oraz reset hydroforu | Hydrofor + Rozdzielka| [Allegro](https://allegro.pl/oferta/shelly-1-przekaznik-wifi-zdalnie-sterowany-3500w-9472100995) | 2
    Shelly 3EM | Pomiar zużycia prądu | Rozdzielka | [Allegro](https://allegro.pl/oferta/shelly-3em-licznik-pomiar-zuzycia-energii-wifi-pv-10854292354) | 1
    
