main_salli \
branch_salli
python:
def kunden_datum():
    eingabe = (input("Bitte geben Sie das Datum ein:"))
    datei = open("C:\\Users\\Student\\Documents\\Suli\\Lernfeld 5\\Phyton\\Spiel.txt","a")
    datei.write("Datum:")
    datei.write(eingabe)
    datei.write(";")
    datei.close()
