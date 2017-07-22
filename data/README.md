Convert to matricies and remove any sites with missing data

```
plink --bfile H938_Euro.LDprune --geno 0.0 --recode A-transpose --out H938_Euro.LDprune
plink --bfile Sardinia.1577.unrelated.pruned --geno 0.0 --recode A-transpose --out Sardinia.1577.unrelated.pruned
```
