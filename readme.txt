myHud to hud gracza, który zawiera wyświetlacz

Pieniądze
Zasięg głosu
Zdrowie
Głód
Pragnienie
Alkohol
W pliku Config.lua możesz po prostu wyłączyć / włączyć zdrowie, zasięg głosu i pieniądze, aby jak najłatwiej dostosować HUD do swoich przekonań.

Dodatkowo znajdują się tam objaśnienia dotyczące prostej edycji kolorów i grubości paska postępu HUD!

 

Jeśli chodzi o zakres głosu:

Ponieważ istnieje mnóstwo różnych sposobów na czat głosowy, musisz dodać proste zdarzenie do czatu głosowego, gdy zakres głosu zostanie zmieniony. Zdarzenie jest wywoływane: TriggerEvent("myHUD:updateVoiceRange", progress). -> Zamiast postępu dodaj tam swój zakres głosu.

Jeśli nie chcesz używać funkcji zakresu głosu w ogóle, po prostu wyłącz to w Config.lua.

 

Zależności:

esx_status (musisz dodać zdarzenie do esx_status -> całkowicie wyjaśnione w readme.txt)
esx_basicneeds
