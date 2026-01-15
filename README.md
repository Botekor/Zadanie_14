# Zadanie_14

Login (nazwa użytkownika)
Reguły:

required – pole nie może być puste
minlength: 4 – minimum 4 znaki
loginAvailable – własna reguła, sprawdza czy login nie istnieje już w tablicy existingLogins

Komunikaty:

„Podaj nazwę użytkownika”
„Minimum 4 znaki”
„Ten login jest już zajęty”

Imię
Reguły:

required – pole obowiązkowe
minlength: 2 – co najmniej 2 znaki

E-mail
Reguły:

required – pole obowiązkowe
email – musi mieć poprawny format adresu e-mail

Hasło
Reguły:

required – pole obowiązkowe
minlength: 6 – minimum 6 znaków

Powtórz hasło
Reguły:

required – pole obowiązkowe
equalTo: "#has1" – musi być identyczne jak pierwsze hasło

Wiek
Reguły:

required – pole obowiązkowe
digits – tylko cyfry
minlength: 18 – błąd logiczny: sprawdza liczbę znaków, a nie wartość wieku
