main_salli \
branch_salli
Python :
def skipassnummer():
    datei = open("C:\\Users\\Student\\Documents\\Suli\\Lernfeld 5\\übung\\LogSkipass 2.txt")
    file = csv.reader(datei, delimiter='|')
    x = 0
    zahl = input("Geben Sie den Scipassnummer ein:")
    for s in file:
        if zahl in s:
            int(s[5])
            x = x + int(s[5])
        else:
            pass
    print("Gesamt länge:", x)
