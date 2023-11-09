# dodanie usera i mail
# zapis w katalogu loklanym
git config --local user.name "FIRST_NAME LAST_NAME"
git config --local user.email "MY_NAME@example.com"
# zapis w katalog systemowym/globalnie
git config --global user.name "John Doe"
git config --global user.email johndoe@example.co

git config --global core.editor emacs

# ustawienie brancha default
git config --global init.defaultBranch main
git config --global init.defaultBranch master

# gdzie jest .gitconfig
git config --list --show-origin


# nowe repo
git init

# kolonowanie repo
git clone
tworzy nowy katalog  "pw-spi"
git clone https://github.com/blizni79/pw-spi.git

# kolon do aktualnego katalogu
git clone https://github.com/blizni79/pw-spi.git .

git clone https://github.com/blizni79/pw-spi.git /nowy-katalog

# dodanie pliku/plikow do staging
git add nazwa-pliku
git add .
git add *.py
git add Readme.md index.html

git add -h



# komitowanie zmian
git commit -m "zmiany"

# status zmian
git status
git status -s

# pobranie wszystkich zmian z repo
git fetch

# pobierz zmiany
git pull

# wypchnij zmiany 
git push

# utworz branch
git checkout -b nazwa-brancha
git branch nazwa-brancha

# lista branchy
git branch

# usuwanie brancha
git branch -d nazwa-brancha

ffff


