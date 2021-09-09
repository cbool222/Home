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
   
    Komponent | Przeznaczenie | Sklep | Ilość 
    ------------ | ------------- | ------------- | -------------
    Skrzynka Rozdzielcza 600x500 | --- | [Allegro](https://allegro.pl/oferta/skrzynka-szafa-obudowa-abs-plastikowa-600x500x220-9786926675) | 1
    Stycznik DILM 15-10 7.5kW | Zdalne wyłączanie płyty indukcyjnej | [Allegro](https://allegro.pl/oferta/stycznik-dilm-15-10-7-5-kw-cewka-24v-ac-1no-10904455058) | 1
    Shelly 1 | Zdalne wyłączanie płyty indukcyjnej | [Allegro](https://allegro.pl/oferta/shelly-1-przekaznik-wifi-zdalnie-sterowany-3500w-9472100995) | 1
    MEAN WELL MDR-40-24 | Zasilanie 24V | [Allegro](https://allegro.pl/oferta/zasilacz-din-mdr-40-24-24v-1-7a-40w-mean-well-8725147785) | 1
    Przetwornica XY-3606 | Przetwornica na 5V do ESP32 | [Allegro](https://allegro.pl/oferta/przetwornica-xy-3606-step-down-z-9-36v-do-5v-5a-9694436548) | 2
    


    
   
   
- # Licznik energii
  Pomiar energii zużytej, oddanej i autokonsumpcji
  
  Czujnik [Shelly 3EM](https://shelly.cloud/products/shelly-3em-smart-home-automation-energy-meter/)
