# dodanie usera i mail
git config --local user.name "FIRST_NAME LAST_NAME"
git config --local user.email "MY_NAME@example.com"

# nowe repo
git init

# kolonowanie repo
git clone
tworzy nowy katalog  "pw-spi"
git clone https://github.com/blizni79/pw-spi.git

# kolon do aktualnego katalogu
git clone https://github.com/blizni79/pw-spi.git .

git clone https://github.com/blizni79/pw-spi.git /nowy-katalog

#dodanie pliku/plikow do staging
git add nazwa-pliku
git add .

#komitowanie zmian
git commit -m "zmiany"

# status zmian
git status

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




