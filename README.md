# Hei, jeg er Kamal 👋

Student og sikkerhetsentusiast som bygger små, ryddige labber og tydelige README-er.  
Jeg liker å forklare **hva jeg gjorde, hvorfor jeg gjorde det, og hva man kan lære av det**.

---

## Om meg
- 🎓 Student med fokus på **IT-sikkerhet** og **programmering**
- 🔍 Interessert i **offensiv sikkerhet** (pentesting) og **blue-team** (logging, nettverksspor)
- 🧰 Jobber praktisk: lager **fiktive labmiljøer**, dokumenterer steg og legger ved sladdede skjermbilder
- ✍️ Skriver på norsk/engelsk – prioriterer **lesbarhet** og **etikklinjer** i alle repoer

## Hva jeg jobber med nå
- Publiserer utvalgte **pentest-labber** (XSS/BeEF, vsftpd-backdoor, Mimikatz/NTLM, MS17-010 + nettverksspor)
- Rydder opp i skoleprosjekter (f.eks. **ArtifactManager** i Java) og gir dem gode README-er
- Bygger en fast struktur for bevis (`images/`), eksempelfiler og “Lab only”-disclaimer

## Teknologi jeg bruker
- **Sikkerhet:** Nmap, Metasploit, BeEF, Mimikatz, John the Ripper, Wireshark  
- **Plattformer:** Kali Linux, Windows (Server/Client)  
- **Dev:** C, Java, GCC/Make, JDBC/MySQL, IntelliJ, Git/GitHub

---

## Utvalgte prosjekter
- **vsftpd 2.3.4 backdoor → shell**  
  Nmap + Metasploit; opprettet lab-bruker og verifiserte innlogging.  
  <https://github.com/Masoudikamal/vsftpd-234-backdoor-lab>

- **BeEF hook via XSS (DVWA)**  
  Injiserte `hook.js`; offer dukker opp i BeEF; *Details* viser origin/cookies/hostname (sladdet).  
  <https://github.com/Masoudikamal/beef-xss-dvwa-lab>

- **Splunk trusseljakt (Botsv1)**  
  Jeg undersøker Botsv1 i Splunk: kartlegger indekser og protokoller, avdekker HTTP-angrep mot ireallynotbatman.com, identifiserer servere (IIS/porter), og viser POST-skjemaer med username/passwd. Alt i et     fiktivt, isolert labmiljø.
  <https://github.com/Masoudikamal/ThreatHunting-Splunk-Botsv1>

- **Mimikatz NTLM → John the Ripper**  
  Hentet NTLM for lab-bruker og bekreftet passord ved cracking.  
  <https://github.com/Masoudikamal/mimikatz-ntlm-crack-lab>

- **MS17-010 (EternalBlue) + nettverksspor**  
  Påviste sårbarhet, samlet `netsh trace` og viste HTTP-innlogging i Wireshark.  
  <https://github.com/Masoudikamal/ms17-010-eternalblue-trace-lab>

- **WZDU35.exe — nettverk → fil → minne (triage-lab)**  
    Triage av wzdu35.exe fra PCAP → statisk analyse → ClamAV/YARA → minne (Volatility 3).  
    <https://github.com/Masoudikamal/wzdu35-malware-analysis>

- **Algoritmer & datastrukturer — sortering (Java)**  
  Implementerte Bubble, Insertion, Merge og Quick i Java; rapport + kjøreinstruksjoner.  
  <https://github.com/Masoudikamal/algorithms-and-datastructures>

- **ArtifactManager (Java OOP)**  
  Konsollapp som lagrer/leser historiske gjenstander via JDBC/MySQL.  
  <https://github.com/Masoudikamal/ArtifactManager>

- **C Programming Labs**  
  Portefølje med C-labber (metadata, flights, threads, SMTP-liknende server, TEA klient/dekryptering) m/ CI-build.  
  <https://github.com/Masoudikamal/c-programming-labs>

---

## Hvordan navigere repoene mine
- Hvert repo har en **kort prosjektpresentasjon** øverst og en **Evidens**-seksjon med bilder i `images/`.  
- Jeg legger ofte til en liten **“Hvorfor dette fungerer”**-del og **forsvarstiltak** (blue-team notater).

## Kontakt
- Åpne gjerne en **Issue** i repoet som er relevant, så svarer jeg der.  
- E-post / LinkedIn:  
  <mailto:kamal.a.masoudi@gmail.com> • <https://www.linkedin.com/in/kamal-al-masoudi>

---

Takk for at du er innom! 🚀
