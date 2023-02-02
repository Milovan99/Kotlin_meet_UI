# Kotlin meet UI

## O aplikaciji 

<img src="https://user-images.githubusercontent.com/29107405/216352807-49034d7c-09f0-4452-9622-6b642c65a245.png" width="200" height="350">

Ova aplikacija sadrži Kotlin kod za glavnu aktivnost Android aplikacije. Aktivnost proširuje klasu AppCompatActivity i implementira View.OnClickListener.

Kod postavlja prikaz sadržaja na R.layout.activity_main i implementira sledeće ponašanje za svu dugmad:

btnAdd povećava vrednost za 1 i ažurira tekst txtValue.
btnTake smanjuje vrednost za 1 i ažurira tekst txtValue.
btnReset postavlja vrednost na 0 i ažurira tekst txtValue.
btnGrow povećava skalu teksta txtValue.
btnShrink smanjuje skalu teksta txtValue.
btnHide prebacuje vidljivost txtValue između vidljive i nevidljive i ažurira tekst btnHide.
