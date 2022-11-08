# Kan_AMLTS2022_Long

LaTeX codes for the AMLTS2022 paper.

## Convertion to CEUR-WS style

Their is a un-synced symbol link `fig` under folder `CEUR-WS-Proceeding`, so that the `Kan_CEURWS2022.tex` file use the same figure files tree as `main-sigconf.tex` does.

To generate this symbol link under Windows:

```bat
mklink /J .\AMLTS-CEUR-WS\fig .\Kan_AMLTS2022_Long\fig
```

Under linux:

```bash
cd AMLTS-CEUR-WS
ln -s ../Kan_AMLTS2022_Long/fig fig
```

## References

- [1] CEUR-ART style files for papers, http://ceur-ws.org/HOWTOSUBMIT.html#PREPARE
