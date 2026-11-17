# 🔺 Piràmides Numèriques

Aplicació web interactiva en català per practicar el càlcul mental i el raonament lògic mitjançant **piràmides numèriques de suma**. Dissenyada tant per jugar directament al navegador com per generar i descarregar fitxes d'exercicis en format A4 llestes per imprimir a l'aula o a casa.

---

## ✨ Característiques principals

- **Regla única de suma:** Cada bloc és igual a la suma dels dos blocs que té just a sota ($C = A + B$).
- **4 nivells de dificultat:**
  - 🟢 **Fàcil:** Piràmide de 3 files (nombres naturals).
  - 🟡 **Mitjà:** Piràmide de 4 files.
  - 🟠 **Difícil:** Piràmide de 5 files.
  - 🔴 **Expert:** Piràmide de 6 files (amb opció d'incloure nombres enters negatius).
- **Generador amb solució única garantida:** L'algorisme comprova lògicament cada piràmide abans de mostrar-la per assegurar que es pot resoldre pas a pas sense haver d'endevinar cap casella.
- **Eines d'ajuda interactives:**
  - **Comprovació visual instantània** (verd per als encerts, vermell per als errors).
  - **Pistes intel·ligents:** Resol automàticament la següent casella deduïble i mostra l'explicació de l'operació aplicada (suma cap amunt o resta cap avall).
  - **Mostra de solució completa** i animació de confeti en completar el repte.
- **Generador de fitxes imprimibles (A4 / PDF):**
  - Personalització del títol de la fitxa i espai per al nom i la data de l'alumne/a.
  - Selecció de quantitat (2, 4 o 6 piràmides per pàgina) i nivell (fix o barrejat).
  - Opció d'afegir un segon full amb totes les solucions.
  - Impressió directa optimitzada (`@media print`) o descàrrega directa en `.pdf`.

---

## 🚀 Instal·lació i ús

Aquest projecte funciona íntegrament al navegador sense necessitat de servidor ni procés de compilació.

1. Clona el repositori o descarrega l'arxiu HTML:
   ```bash
   git clone [https://github.com/el-teu-usuari/piramides-numeriques.git](https://github.com/el-teu-usuari/piramides-numeriques.git)