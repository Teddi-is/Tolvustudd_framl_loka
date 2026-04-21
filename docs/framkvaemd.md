# Framkvæmd

## Gerð á móti

Við hönnun á mótinu fyrir toolpath þarf að hafa amk 5mm pláss fyrir botn í frauðplastinu og 25mm frá búknum yfir í vegginn á frauðplastinu svo það sé nægt pláss fyrir putta til að taka búkinn úr frauðplastinu. Það eina sem heldur þá búknum föstum við frauðplastið að fræsingu lokinni er 5mm botninn.

Þar sem CAD módelið okkar var 55mm á hæð en frauðplastið bara 50mm ákváðum við að líma saman tvær plötur af frauðplasti (eina 50mm og aðra 25mm) svo heildar hæð frauðplastsins væri 75mm sem dugar fyrir okkar módel. Við hefðum líka getað skipt módelinu í tvo parta og límt það saman eftirá en okkur fannst þetta nákvæmara.

## Vél og búnaður
Verkefnið var unnið á Shop Bot PRS5 Alpha sem er CNC fræsir sem er ætlaður til að fræsa plast, frauð, ál og fleira. Sem er svolítið overkill fyrir okkar frauðplast en virkar vel. 

## Fræsibitar
Fræsibitinn sem er notaður í að fjarlægja mest allt efnið er 6mm flat end karbít biti.
Fræsibitinn sem er notaður í fínpússun og til að gera göt og lítil features er 6mm karbít shank biti.


## Undirbúningur
Hér verður lýst undirbúningi fyrir vinnslu, festingum, núllstillingu og vali á verkfærum.

## Roughing
Hér verður lýst roughing toolpath, verkfærum, feeds og speeds.

Feedrate á roughing er 5000 mm/min
Spindle speed er 12000 rpm
Tolerance er 10mm

Í roughing er stærri biti notaður til að taka sem mest efni í burtu á meiri hraða og með minni nákvæmni. Ef þetta væri ekki gert þá myndi fræsingin taka töluvert lengri tíma ef það væri notaður fínn biti í allt mótið.

![Roughing Toolpath](../images/roughing-toolpath.png)   

## Finishing
Hér verður lýst finishing toolpath, verkfærum, feeds og speeds.

Feedrate á finishing er 3000 mm/min
Spindle speed er 12000 rpm
Tolerance er 0.5mm

Í finishing tekur hann tvær ferðir, annars vegar tekur hann "passes" í x átt, og svo þegar hann er búinn af því yfir allann búkinn tekur hann "passes" í y átt. Það er til þess að jafna úr ribbunum sem myndast þegar hann fer í x átt því fræsibitinn skilur eftir rauf í hvert skipti.


![Finishing toolpath](../images/finishing-toolpath.png)   

## Mótun á efni við frauðplastið.

Við mótun við frauðplastið er notað einskonar striga efni sem er lagt yfir plastið og penslað með 

