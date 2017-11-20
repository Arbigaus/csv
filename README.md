## Classe para enviar arquivo CSV.

Esta classe funciona com a estrutura MVC, para o funcionamento, basta chamar a function enviando o caminho do arquivo:

```
$file = "assets/files/claro.csv";
Csv::UpdateFatura($file);
```

O mesmo irá ler o arquivo e já enviar os dados para o BD.
Lembre-se de verificar os nomes das colunas em seu BD conforme sua necessidade.
