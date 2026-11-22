| Arm | ASR | Refusal rate | Over-refusal | Benign F1 | Uninformative | ASR: multi-turn | ASR: encoding |
|---|---|---|---|---|---|---|---|
| No defence (prompt only) | 0.537 | 0.325 | 0.083 | 0.323 | 0.458 | 0.300 | 0.400 |
| SFT defender | 0.000 | 0.963 | 0.000 | 0.580 | 0.000 | 0.000 | 0.000 |
| MAPPO v1 (buggy ratio) | 0.050 | 0.863 | 0.250 | 0.146 | 0.625 | 0.000 | 0.200 |
| MAPPO v2 (fixed) | 0.100 | 0.613 | 0.042 | 0.358 | 0.250 | 0.000 | 0.000 |

### MAPPO v2 seed variance

| Run | ASR | Over-refusal |
|---|---|---|
| mappo | 0.100 | 0.042 |
| mappo_s1 | 0.338 | 0.000 |
