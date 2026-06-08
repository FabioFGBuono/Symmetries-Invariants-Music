# 🎵  Scale a Toni Interi e il Circolo delle Quinte

L'osservazione che troverete in queste pagine, almeno usando la struttura a "zig zag" (interleaving) che vado a spiegare, è nuova, o almeno non l'ho trovata da nessuna parte, ho cercato nel web e sui libri, ma sembra assente. Se qualcuno dovesse averla scritta prima di me è pregato di farmelo sapere, così posso correggere questo testo.


---

## Una Simmetria Nascosta

Per secoli i musicisti hanno usato il circolo delle quinte per comprendere l'armonia tonale occidentale, ma la ragione per cui questa struttura emerge così naturalmente può essere spiegata in termini algebrici, infatti il circolo delle quinte si può ricreare dall'interazione tra le due scale a toni interi e la struttura di $\mathbb{Z}_{12}$. Questo lavoro nasce da una casualità, stavo spiegando a un'amica le scale a toni interi e le ho scritte in verticale una di fronte all'altra, e mentre le spiegavo i miei occhi hanno iniziato ad andare a zig zag tra le due liste di note. Sapete cosa stavo osservando? Il circolo delle quinte che appariva tra le due scale. Ho deciso di scriverci due righe a riguardo. Non serve a niente in pratica ma è divertente!

Però forse c'è qualcosa in interessante al di fuori della strana osservazione sulla struttura a zig zag, le scale a toni interi per definizione non hanno semitoni, quindi niente movimento di sensibile, il circolo delle quinte invece è la struttura ceh genera la massima spinta dinamica nella musica (il ciclio delle cadenze dominante-tonica, le modulazioni, ...) e dal circolo si costruiscono le armature di chiave delle scale tonali. E' strano che da due strutture completamente statiche come le due scale a toni interi nasca il movimento tonale assoluto.


```
                     CIRCOLO DELLE QUINTE
            ══════════════════════════════════════════

                 W₀ (Pari)          W₁ (Dispari)
                 ─────────          ────────────

                 0 (C)         →      7 (G)
                    ↑                    ↓
                 2 (D)         ←      9 (A)
                    ↑                    ↓
                 4 (E)         →     11 (B)
                    ↑                    ↓
                6 (F#)         ←     1 (C#)
                    ↑                    ↓
                8 (G#)         →     3 (D#)
                    ↑                    ↓
               10 (A#)         ←      5 (F)
                    └───────────────────┘
                         (torna a 0)
```


Trovate il resto qui: [Zig-Zag](https://htmlpreview.github.io/?https://github.com/FabioFGBuono/Symmetries-Invariants-Music/blob/main/Toni%20interi.html)


