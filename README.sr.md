<a href="https://diamondlux.svilenkovic.rs/"><img src="media/cover.jpg" alt="Diamond Lux Kopaonik, naslovna strana na laptopu i telefonu" width="100%"></a>

# Diamond Lux Kopaonik

Sajt na jednoj strani, na srpskom i engleskom, za ski-to-door apartman u centru Kopaonika, sa WebGL dijamantom koji prati skrol.

**[diamondlux.svilenkovic.rs](https://diamondlux.svilenkovic.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/diamond-lux-kopaonik) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Diamond Lux</td></tr>
  <tr><td><b>Delatnost</b></td><td>Izdavanje apartmana</td></tr>
  <tr><td><b>Lokacija</b></td><td>Kopaonik</td></tr>
  <tr><td><b>Vrsta</b></td><td>Dvojezični sajt na jednoj strani</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>Next.js 15, React Three Fiber, next-intl, Tailwind 4, Lenis</td></tr>
</table>

## O projektu

Diamond Lux je apartman od 33 m² za četiri osobe u Vili Montana, u centru Kopaonika, 50 m od hotela Grand, sa skijašnicom u zgradi i stazom preko puta. Oglašavao se na portalima za smeštaj i na Instagramu, a vlasnik je hteo sopstveni sajt koji brzo ubedi gosta i dovede ga do poziva, bez forme. Sve što odlučuje o rezervaciji moralo je da stane u jedan skrol, na srpskom i engleskom.

Ime apartmana dalo je i ideju: na računaru dijamant iscrtan u WebGL-u lebdi iza sadržaja i pomera se dok se skroluje. Kamen je brilijantni brus napisan u kodu, sa indeksom prelamanja 2,42, a geometrija mu je namerno neindeksirana, pa svaka faseta ima svoje normale i izgleda ravno i oštro. Providan kamen na toploj, svetloj pozadini sajta jednostavno je nestajao, pa iza njega sada stoji svetao, ledenoplav oreol koji daje kontrast i bledi kako se skroluje naniže.

## Šta sam uradio

- Sedam odeljaka sa navigacijom po sidrima: apartman, galerija, sadržaji, lokacija, sezone, pitanja i kontakt
- Rezervacija samo pozivom ili Viber porukom sa već napisanim prvim redom, uz dugme za poziv koje lebdi uz ivicu ekrana
- Biblioteka za 3D u posebnom paketu, učitana tek kad se potvrdi WebGL, a zaštitna komponenta u slučaju greške prikazuje fotografiju planine
- Osvetljenje scene postavljeno u kodu, bez mape okoline sa tuđeg servera
- Srpski tekstovi zaostali u komponentama prebačeni u prevodne fajlove, što sam proverio tražeći naša slova u engleskom HTML-u
- OpenStreetMap mapa umesto Google mape koju su bezbednosna pravila tiho blokirala

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 93 | 100 | 100 | 100 |
| Desktop | 99 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `Apartment`, `BreadcrumbList`, `FAQPage`, `LodgingBusiness`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Diamond Lux Kopaonik, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Diamond Lux Kopaonik, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="O apartmanu: premium apartman u Vili Montana i objašnjenje šta znači ski-to-door">
<sub>O apartmanu: premium apartman u Vili Montana i objašnjenje šta znači ski-to-door</sub>

<img src="media/inner-2.webp" alt="Galerija: dnevna soba, trpezarija i kuhinja, svaka fotografija sa svojim opisom">
<sub>Galerija: dnevna soba, trpezarija i kuhinja, svaka fotografija sa svojim opisom</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
