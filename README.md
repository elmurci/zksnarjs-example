```
circom multiplier.circom -o multiplier.json

snarkjs printconstraints -c multiplier.json

snarkjs setup -c multiplier.json

snarkjs proof

snarkjs verify
```