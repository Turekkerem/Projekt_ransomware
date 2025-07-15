# 🛑 Projekt Ransomware: Parodia WannaCry 🛑

> ⚠️ **OSTRZEŻENIE:** Ten projekt zawiera **prawdziwe oprogramowanie typu ransomware** stworzone w celach edukacyjnych i testowych. Każde użycie go poza środowiskiem testowym, bez wyraźnej zgody właściciela danych, jest **nielegalne i karalne**. Autor nie ponosi żadnej odpowiedzialności za nieuprawnione użycie tego narzędzia. Używaj **na własne ryzyko i tylko w kontrolowanym środowisku.**

---

## 📦 Zawartość projektu

Ten projekt to **parodia legendarnego WannaCry**, stworzona w celach edukacyjnych, badawczych oraz testowania zabezpieczeń. Składa się z kilku wariantów, z których każdy oferuje inne funkcje i poziomy wykrywalności.

### 🔐 `pelna_wersja/`
- Używa **szyfrowania AES** (symetrycznego, silnego).
- Nie posiada mechanizmu autostartu.
- **Nie jest wykrywana** przez większość antywirusów, w tym Windows Defendera (na moment testowania).
- Najbardziej "bezpieczna" w użyciu wersja — tylko ręczne uruchomienie.

### 🚨 `wersja_idealna_z_autostartem/`
- Również oparta o **szyfrowanie AES**.
- Posiada **mechanizm autostartu** w systemie Windows.
- Stylizowana na „idealną” wersję — bardziej automatyczna i nieinwazyjna dla operatora.
- Jest **wykrywana jako trojan** przez Windows Defendera oraz inne AV.

### 🔒 `zabezpieczanie_plikow/`
- Podfolder poświęcony **dodatkowej ochronie i/lub sabotażowi danych**.
- Wykorzystuje **algorytm XOR** z kluczem generowanym jako **hash z hasła**.
- Może być używany do selektywnego szyfrowania plików lub jako dodatkowa warstwa.

---

## 🎭 Stylizacja i cel projektu

Projekt został celowo wystylizowany jako **parodia WannaCry**:
- Zawiera komunikaty inspirowane oryginalnym atakiem.
- Estetyka i język przypominają kultowe ransomware z przymrużeniem oka.
- Edukacyjny twist: kod został napisany tak, aby **łatwo go analizować i modyfikować** (jeśli potrafisz 😈).

---

## 🧪 Użycie

1. **Uruchamiaj tylko w środowisku testowym!**
2. Przeczytaj kod przed uruchomieniem.
3. Upewnij się, że masz pełną kontrolę nad systemem.
4. Nie używaj w sieciach firmowych, instytucjonalnych, edukacyjnych ani domowych.

---

## 🛡️ Legalność i odpowiedzialność

- Projekt ten ma charakter **wyłącznie edukacyjny**.
- Nie jest przeznaczony do użycia w rzeczywistych atakach.
- Autor **nie odpowiada** za skutki jego niewłaściwego użycia.
- Narzędzia tego typu mogą zostać zakwalifikowane jako **malware** i ich dystrybucja oraz uruchamianie może być **niezgodne z prawem**.

---

## ✍️ Autor

Projekt stworzony przez [TwojeImięLubNick]  
Zainteresowany cyberbezpieczeństwem, inżynierią odwrotną i analizą zachowania zagrożeń.

---

## 🧯 Na zakończenie

> "Z wielką mocą przychodzi wielka odpowiedzialność."  
> — **Uncle Ben**

---

🧠 **Ucz się odpowiedzialnie. Testuj bezpiecznie. Nigdy nie atakuj bez zgody.**

