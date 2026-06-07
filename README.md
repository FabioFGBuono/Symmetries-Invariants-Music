# 🎵  Scale a Toni Interi e il Circolo delle Quinte

L'osservazione che troverete in queste pagine, almeno usando la struttura a "zig zag" (interleaving) che vado a spiegare, è nuova, o almeno non l'ho trovata da nessuna parte, ho cercato nel web e sui libri, ma sembra assente. Se qualcuno dovesse averla scritta prima di me è pregato di farmelo sapere, così posso correggere questo testo.


---

## Una Simmetria Nascosta

Per secoli i musicisti hanno usato il circolo delle quinte per comprendere l'armonia tonale occidentale, ma la ragione per cui questa struttura emerge così naturalmente può essere spiegata in termini algebrici, infatti il circolo delle quinte si può ricreare dall'interazione tra le due scale a toni interi e la struttura di $\mathbb{Z}_{12}$. Questo lavoro nasce da una casualità, stavo spiegando a un'amica le scale a toni interi e le ho scritte in verticale una di fronte all'altra, e mentre le spiegavo i miei occhi hanno iniziato ad andare a zig zag tra le due liste di note. Sapete cosa stavo osservando? Il circolo delle quinte che appariva tra le due scale. Ho deciso di scriverci due righe a riguardo.

## Le due scale a toni interi

Una scala a toni interi (whole-tone scale) è una sequenza di note in cui ogni grado dista dal successivo un tono, è una scala particolare, la mancanza di semitoni elimina la classica sensazione di risoluzione, infatti è spesso usata per creare per effetti sospesi. Nel sistema temperato a 12 semitoni possiamo rappresentare le note con il gruppo ciclico $\mathbb{Z}_{12}$, dove $0=C,\,1=C\#,\,2=D$ e così via. L'insieme ottenuto aggiungendo ripetutamente 2 modulo 12 è il sottogruppo $W=\langle 2\rangle=\{0,2,4,6,8,10\}\pmod{12}$, che corrisponde a una delle due scale a toni interi $C,D,E,F\#,G\#,A\#$. Trasponendo $W$ di un semitono otteniamo l'altro coset $W+1=\{1,3,5,7,9,11\}\pmod{12}$, corrispondente alla scala $C\#,D\#,F,G,A,B$. I due insiemi $W$ e $W+1$ partizionano $\mathbb{Z}_{12}$: 

$$
\mathbb{Z}_{12}=W\sqcup(W+1).
$$

Non esistono altre scale a toni interi distinte modulo trasposizione e come chiunque abbia studiato armonia sa, queste due coprono tutte le possibilità nel modello a 12 semitoni.

