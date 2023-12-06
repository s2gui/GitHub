# Py
### Detalhes do Codigo
Isso importa a biblioteca Pandas e a renomeia como pd para facilitar o uso.

```
import pandas as pd
```

Aqui, ele lê um arquivo Excel chamado "base_notas.xlsx" e o carrega em um DataFrame do Pandas chamado df.

```
df = pd.read_excel("base_notas.xlsx")
```

Essa linha calcula a média das colunas 'Nota1', 'Nota2', 'Nota3' e 'Nota4' para cada linha do DataFrame df. O resultado é armazenado em uma nova coluna chamada 'Media'.

```
df['Media'] = df[['Nota1', 'Nota2', 'Nota3', 'Nota4']].mean(axis=1)
```

Por fim, esse comando salva o DataFrame df, que agora contém a coluna de médias, de volta para um arquivo Excel chamado "nota_aluno.xlsx", sem incluir o índice das linhas no arquivo resultante.

```
df.to_excel('nota_aluno.xlsx', index=False
```

### Codigo

```
import pandas as pd

df = pd.read_excel("base_notas.xlsx")

df['Media'] = df[['Nota1', 'Nota2', 'Nota3', 'Nota4']].mean(axis=1)

df.to_excel('nota_aluno.xlsx', index=False)

```

### Como ira ficar
![Excel](nota_aluno.png)

### Porém
Antes de ficar assim, vai ter que criar um excel primeiro pra adicionar os componentes, ele adicionara a Media sozinho
![Excel](base_notas.png)

## Referencias:
[README](README.md)

[Comandos Git](ComandosGit.md)
