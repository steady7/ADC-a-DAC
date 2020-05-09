﻿# 2 typy signálu
analogový signál = hodnota se přenáší jako úroveň napětí či proudu
digitální signál = hodnota je zakódována jako binární číslo
### Analogový přenos
Libovolná hodnota signálu je platná, s časem se hodnota mění postupně (spojitě). 
+ Jednoduchost
+ Efektivita →  v jednom okamžiku můžeme přenášet teoreticky nekonečně mnoho informace (ve skutečnosti jsme omezeni přesností měření a mírou šumu — rušení) 
- Nelze detekovat chybu (rušení signálu)
- Nelze opravit vzniklé zkreslení
### Digitální přenos
Vyhradíme pouze několik hodnot signálu, které jsou povolené. 
Výskyt jiných hodnot indikuje chybu při přenosu (porušení přenášeného signálu). 
Můžeme chybu „opravit“:
    1)Zaokrouhlíme ji na nejbližší platnou hodnotu.
    2)Často tak získáme správnou (odvysílanou) hodnotu (ale ne vždy)! 
![priklady_digital](digital_priklady.png)
# ADC
![adc](https://i.imgur.com/2pGoFVo.png)
### Příklad využití
Když mluvíme po telefonu, mikrofon převádí náš hlas na elektrický signál a pomocí ADC je tento signál digitalizován a je přenášen ve formě rádiových vln.
![priklad](priklad_ADC.png)
Podobně, na straně přijímače, s použitím DAC jsou tato přijímaná digitální data převedena na analogový signál a prostřednictvím reproduktoru jsme schopni slyšet hlas jiné osoby.
# DAC
![dac](DAC.png)
### Příklad využití DAC
Když streamujeme hudbu na našem smartphonu, pak se tento digitální bitový tok převede na elektrický signál a prostřednictvím reproduktoru smartphonu jsme schopni tuto hudbu slyšet.
.... zde tento DAC uvnitř smartphonu převádí digitální bitový proud na analogový signál.
![priklad](priklad_DAC.png)