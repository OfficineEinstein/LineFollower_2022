# LineFollower_2022
Progetto per un Line Follower due ruote più ruotino

# Struttura del repository
Sono presenti 3 cartelle e rispettivamente

FC . contiene i file di progetto degli elementi meccanici e strutturali elaborati in FreeCad e salvati in STL (per le stampe in 3D) o in DXF (per il taglio laser). Per quanto riguarda le stampe sono presenti anche i file di stampa (GCODE) dove dal nome è possibile comprendere la stampante da utilizzare e il diametro dell'estrusore

KC - Contiene i file con il progetto elettrico sviluppati con KiCad. Possono essere presenti sotto cartelle con i file per la realizzazione dei PCB

PF - Contiene i file con il progetto software sviluppati con VSC PlatformIO. Il progetto contiene le librerie esterne e i file include interni se previsti. Pu; essere presente una cartella Doc contenente documentazione tecnica e documenti utili allo sviluppo del progetto

# Scopo del progetto
Il progetto è finalizzato alla realizzazione di un robot in grado di seguire una linea nera tracciata su fondo bianco.

Il roboto deve avere capacità di guida autonoma di livello 5.

Il progetto copre tutte le fasi di progettazione e realizzazione del robot includendo la progettazione estetica e funzionale, la progettazione meccanica, il progetto elettrico (elettronico) delle schede e dei circuiti utilizzati (permette di partire da una scheda Maker uno o Arduino e da driver per i motori e sensori reperibili sul mercato per arrivare sino a schede e sensori progettati e realizzati appositamente) e lo sviluppo del software di navigazione.
