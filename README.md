# Exercício - Introdução ao CSS3

Esse é um exercício de sobre o conteúdo da aula de CSS3 de Tecnologias Web da Faculdade Impacta de Tecnologia.

## Como fazer

**TL;DR: Edite os arquivos CSS. Não edite os arquivos HTML**

Existem 4 exercícios aqui, em ordem progressiva de dificuldade (ou seja, o 1 deve ser o mais fácil e o 4 o mais difícil, embora dificuldade seja algo subjetivo). Cada exercício contém um arquivo HTML, um arquivo CSS e um arquivo PNG como referência. O arquivo `Simpsonfont.otf` também é usado pelo exercício 4. Para realizar a entrega, o arquivo `membros.json` será necessário.

Cada HTML importa o CSS correspondente contendo os detalhes do que deve ser implementado. Edite os arquivos CSS de forma a deixar o layout dos HTMLs correspondentes conforme as instruções neles dadas. Não edite os arquivos HTML.

Observe que no enunciado dentro de cada CSS, existem números entre colchetes para cada regrinha definida. Com pouquíssimas exceções, cada uma dessas regrinhas do enuniado vai virar uma regra no CSS. Além disso, cada uma delas corretamente implementada vale 0,1 pontos na nota.

Não há testes para esse exercício. Para ajudar você a se certificar de que o CSS que você fez está correto, para cada arquivo HTML há também um arquivo PNG mostrando o resultado esperado. Compare o HTML que o navegador te exibe com o PNG para ver se o que você fez parece estar certo ou não.

## Como rodar

Para testar este exercício, basta os arquivos HTML em um navegador moderno (Chrome ou Firefox) e ver o se o que aparece na tela está similar às imagens providas como resultados desejados.

Obviamente, os HTMLs dados aqui se apresentarão bem diferentes do que o desejado por não terem os seletores e regras CSSs necessárias. O seu objetivo é editar os arquivos CSS e acrescentar neles esses seletores e regras.

## Como fazer a entrega

1. Edite o arquivo `membros.json` com as informações dos membros do grupo (até 3 e no mínimo 1). Por exemplo, se forem dois membros:

```json
[
  {
    "nome": "João da Silva",
    "ra": 123456
  },
  {
    "nome": "Maria da Silva",
    "ra": 654321
  }
]
```

2. Coloque os arquivos `exe1.css`, `exe2.css`, `exe3.css`, `exe4.css` e `membros.json` dentro de um arquivo ZIP. Não coloque dentro dele nada mais do que esses arquivos.

3. Entregue o arquivo ZIP pelo formulário na AC 2 do classroom.

Observe que voê não deve entregar os HTMLs e nem os PNGs dentro do seu ZIP.

## Como fica a nota

Caso múltiplas entregas sejam feitas por um mesmo grupo de alunos, apenas a última será considerada, mesmo se entregues por alunos diferentes do mesmo grupo.

A correção é realizada pelo professor por meio visual (a.k.a. "olhômetro") e pela análise manual do código-fonte dos arquivos CSS entregues.

Observe que cada arquivo tem várias regrinhas numeradas entre colchetes. Cada uma delas vale 0,1 pontos:
- O arquivo `exe1.css` tem 14 regrinhas.
- O arquivo `exe2.css` tem 23 regrinhas.
- O arquivo `exe3.css` tem 20 regrinhas.
- O arquivo `exe4.css` tem 38 regrinhas.

Isso totaliza 95 regrinhas perfazendo uma nota de 9,5.

Arquivos CSS que estejam em branco, que sejam idênticos aos dados no enunciado, que não sejam legíveis ou que não produzam nenhum dos efeitos desejados serão considerados com nota zero para todas as regras dele esperadas.

Os outros 0,5 pontos (podendo então totalizar 10) serão dados para quem conseguir cumprir TODOS essas requisitos corretamente:

- Preencher o JSON corretamente.
- Ter todos os CSSs bem formados e o JSON bem formado.
- Ter os arquivos corretos dentro do ZIP, com os nomes corretos e nada mais além do que esses arquivos.
- Fizer a entrega corretamente pelo formulário.
- Não trocar, confundir ou misturar os diferentes arquivos CSS.

## Dicas

- Em linhas gerais, se duas regras estiverem aparentemente em conflito, vale a que é aplicada ao seletor mais específico e se isso ainda não resolver, vale a última definida. No entanto, há vários casos especiais.
- Apesar da dica acima, evite ter que confiar em solução de possíveis conflitos de regras exceto se absolutamente necessário. Aliás, evite criar regras que precisem ser sobrescritas ou redefinas.
- Cuidado com regras CSS definidas por padrão pelo navegador. Por vezes será necessário sobrescrevê-las.
- Teste no Chrome e no Firefox para evitar possíveis diferenças entre navegadores.
- Não altere os arquivos HTML. Qualquer alteração nos arquivos HTML será totalmente desconsiderada na entrega. A correção será feita com os arquivos HTML originais.
- Em geral, com pouquíssimas exceções, existe uma relação de um-para-um entre as regras numeradas no enunciado e as regras CSS que vocês vão definir.
- Sempre tenha em mente que devido a pequenas diferenças entre navegadores, é possível que mesmo que o que você fez esteja correto, pode ainda haver alguma pequena divergência entre o que o navegador te mostra e o PNG com o resultado esperado. No entanto, só considere essa hipótese depois que eliminar outras hipóteses de que talvez você tenha cometido algum equívoco no seu CSS ou de que tenha esquecido ou confundido algum detalhe do enunciado.
- Mesmo que a página que o navegador tenha te mostrado esteja perfeitamente idêntica aos PNGs de referência, ainda assim é possível ter erros no CSS (por exemplo: regras inúteis ou elementos invisíveis) e o professor vai procurar por isso. Logo, não é só porque o resultado ficou igual ao PNG que isso significa que você tirou 10.
