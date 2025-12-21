Tworzenie strony statycznej na GitHub Pages<!-- omit in toc -->
=
# Wprowadzenie
Przy pomocy GitHub Pages można utworzyć statyczną stronę internetową, której źródłem będą pliki znajdujące się w repozytorium na GitHubie. Do tego celu można skorzystać z popularnego szablonu Just The Docs.
# Warunki wstępne
 - Publiczne repozytorium na GitHubie<br>Repozytorium musi być publiczne, aby mogła zostać utworzona strona na GitHub Pages.
 - Plik `index.md`<br>Plik ten jest niezbędny jako strona główna naszej strony GitHub Pages.
# Tworzenie strony statycznej na GitHub Pages
## Ustawienie publicznego repozytorium
1. Wejdź na stronę główną repozytorium, które ma być źródłem strony internetowej.
2. Kliknij zakładkę *Settings*.
3. W sekcji **Danger Zone** u dołu ekranu kliknij przycisk *Change visibility*.
    > Pojawi się przycisk *Change to public*.
4. Kliknij przycisk *Change to public*.
## Uruchomienie GitHub Pages
1. Wejdź na stronę główną repozytorium, które ma być źródłem strony internetowej.
2. Kliknij zakładkę *Settings*.
3. W lewym menu bocznym kliknij pozycję *Pages*.
4. W sekcji **Source** kliknij przycisk *Deploy from a branch* i wybierz opcję *GitHub Actions*.
5. W sekcji **Branch** kliknij przycisk *None* i wybierz **brancha**, który ma być źródłem strony statycznej.
   > Najczęściej będzie to `main`.
6. 
## Tworzenie pliku `index.md`
Plik `index.md` można utworzyć w Visual Studio Code lub bezpośrednio w repozytorium na GitHubie. Po utworzeniu pliku należy wprowadzić do niego zawartość w odpowiednim formacie.
1. 
## Personalizowanie pliku `_config.yml`
## Tworzenie repozytorium z szablonem Just The Docs
Dla ułatwienia można skorzystać z gotowego i powszechnie znanego szablonu Just The Docs. Repozytorium utworzone przy pomocy tego szablonu można później spersonalizować. Plik `index.md` tworzy się automatycznie i należy go wyłącznie spersonalizować.   
Informacje na temat możliwości personalizacji, a także objaśnienie różnych opcji znajdują się w pliku [Readme.md](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md).  
Dokumentacja online znajduje się [tutaj](https://just-the-docs.github.io/just-the-docs/).
1. Wejdź na stronę [Just The Docs](https://just-the-docs.github.io/just-the-docs/).
2. W sekcji **Getting started** kliknij link [use the template](https://github.com/just-the-docs/just-the-docs-template/generate).
   > Otworzy się strona **Create a new repository**, na której już wybrany został szablon Just The Docs.
3. Uzupełnij opcje zgodnie z opisem w Obsługa narzędzia GitHub i kliknij przycisk *Create repository*
   
