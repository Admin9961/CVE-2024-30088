# CVE-2024-30088
Questa repository contiene un Proof of Concept (PoC) scritto in Python per la vulnerabilità CVE-2024-30088. Questo codice è un tentativo di replicare la vulnerabilità come esercizio tecnico, con scopi puramente educativi e dimostrativi, di come Python in qualche modo "arranca" anche in questo campo. Utilizzo la libreria ctypes per definire strutture di dati a basso livello in Python.

CVE-2024-30088 è una vulnerabilità di Elevation of Privilege (LPE) che colpisce il kernel di Windows. L'exploit richiede operazioni a basso livello che normalmente non sono ben supportate in Python, un linguaggio di alto livello noto per la sua astrazione e gestione automatica della memoria tramite Garbage Collection (GC).

Questa "prova di concetto" mostra come, nonostante le limitazioni del linguaggio, sia possibile interagire con il kernel di Windows e manipolare processi a basso livello utilizzando Python. Va notato che l'uso di tecniche come la manipolazione diretta della memoria e la gestione dei processi a livello di kernel sono intrinsecamente complessi e possono comportare rischi per la stabilità del sistema.

Nota: **Il codice originale dell'exploit è scritto in C++. Per ottenere LPE si raccomanda di usare quello, questa variante può causare un BSOD, crash ecc. per i motivi sopra elencati.**

PoC originale: https://github.com/tykawaii98/CVE-2024-30088
