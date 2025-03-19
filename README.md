# scratchInsertSort


Beszúró rendezést alkalmaz egy adott listára(tömbre) azaz növekvő sorrendbe rakja n darab szám sorozatát.<br>
> [!Important]
> A lista elemei random generáltak, n darab.
<br>
Miután rendezve van a lista,
az egyik sprite (kártya sprite) kártyákat kezd el pakolni növekvő sorrendbe jelezve hogy a lista rendezve van.
<br>
Miután a kátyák le lettek pakolva, a második sprite (bogár) azt mondja hogy rendezve van 2 másodpercig.
<br>
Ezután kisétál 100 move onként az ablak szélére és eltünik.
<br>

[Wikipédia beszúrásos rendezés](https://hu.wikipedia.org/wiki/Besz%C3%BAr%C3%A1sos_rendez%C3%A9s)

![https://myoctocat.com/assets/images/base-octocat.svg](https://github.com/brinyipeti/scratchInsertSort/blob/main/scrachprojbg.png)
## Tehát a kártyák csak ezt imitálják hogy:


Bemenet : 
```
<a1,a2,...,an>
```
Kimenet: a bemenő sorozat olyan 
```
<a1',a2',...,an'>
```
permutációja hogy
```
<a1' < a2' < ... < an'>
```


> [!NOTE]
> Tehát a kártyák csak egy vizuális kiegészítés a rendezés végére.

