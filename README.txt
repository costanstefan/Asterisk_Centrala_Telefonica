AsteriskNow-Centrala telefonica 
-functiile acestei centrale telefonice pentru utilizatorul SIP sunt:
	music on hold
	playback
	wait

-functiile acestei centrale telefonice pentru utilizatorul IAX sunt:
	music on hold
	playback
	wait
	mesaj de "hello word" in cazul in care se apasa tasta 1, iar mesajul invalid in cazul in care nu este apasata tasta 1

Observatii:
	-Pentru aceasta centrala telefonica sunt configurate doua tipuri de utilizatori: IAX si SIP. In cazul in care se doreste apelarea intre acesti doi utilizatori
	se va arunca un mesaj de invaliditate, explicatiile se gasesc in fisierul "Extensions".
	
	-Sunt configurate doua numere de telefon pentru fiecare dintre acesti doi utilizatori:
		SIP: 123 si 321
		IAX: 456 si 654
	
	-Conectarea la centrala se face cu adresa IP a centralei AsteriskNow ce ruleaza pe un anumit PC sau Laptop ce este conectat la cablu Ethernet (Nu WIFI).
	Se foloseste comanda "ifconfig"
	

	-Telefoanele gratis ce pot fi folosite sunt "Zoiper" si "BriaSolo" pentru a conecta utilizatorii SIP cat si IAX, iar "XLITE" doar pentru utilizatorii SIP.
	Acestea se pot descarca pe orice dispozitiv si trebuie configurate cu unul din numerele de telefon de mai sus si cu adresa IP a centralei.
	