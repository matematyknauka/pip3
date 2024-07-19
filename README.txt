pip3 służy do instalacji bibliotek Pythona. żeby to pip3 zainstalować na Linux wpisz w terminalu lub wklej to:


# Zaktualizuj listę pakietów
sudo apt update

# Zainstaluj pip3
sudo apt install python3-pip -y

# Sprawdź, czy pip3 został zainstalowany pomyślnie
if command -v pip3 &> /dev/null
then
    echo "pip3 został zainstalowany pomyślnie."
else
    echo "Instalacja pip3 nie powiodła się."
fi
