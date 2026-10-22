# salon-stawki

Stawki z przepisów (płaca minimalna, składki ZUS, PIT, limit VAT) dla aplikacji Salon.
Aplikacja pobiera `stawki.json` i sprawdza podpis `stawki.json.podpis` kluczem wbudowanym w aplikację,
więc ręcznie zmieniony plik zostanie odrzucony. Nowe wersje wydaje skrypt `narzedzia/wydaj-stawki.sh` z depotu SalonMamy.
