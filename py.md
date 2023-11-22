# Py
# Codigo
`pandas é uma inteligencia artificial que fornece ferramentas para manipular e analise de dados`

```
import pandas as pd
```

`base_notas.xlsx é o nome do seu excel`

`pd`

```
import pandas as pd

df = pd.read_excel("base_notas.xlsx")

df['Media'] = df[['Nota1', 'Nota2', 'Nota3', 'Nota4']].mean(axis=1)

df.to_excel('nota_aluno.xlsx', index=False)

```









## Referencias:
[README](README.md)

[Comandos Git](ComandosGit.md)
