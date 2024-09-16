# pragmatic-programmer
This is a repository to share my thoughts on the book The Pragmatic Programmer

## Capítulo 01 - Uma Filosofia Pragmática

- Podemos ter orgulho de nossas habilidades, mas devemos ser honestos sobre nossas falhas, nossa ignorância e nossos erros.
- Não tolere janelas quuebradas.
- Não se esqueça do cenário mais abrangente.
- Refatoração e Requisitos.
- Envolver o usuário para garantir que o nível de satisfação seja atingido e tornar a qualidade parte dos requisitos.
- Projeteis Luminosos.
- Não deixar o código muito detalhado, deixar que o código fale por si próprio.
- Tenha uma carteira de conhecimentos.
- Não arrisque todas as suas apostas técnicas na mesma direção.
- Análise criticamente o que você lê e ouve.
- Saiba o que quer perguntar a algum especialista e seja tão especifico quanto puder
- Formule sua pergunta cuidadosa e polidamente.
- Comunique-se.
- Saiba o que você quer dizer.
- Conheça seu publico alvo.
- Escolha o momento certo
- Se adapte ao estilo de pergunta (formal, informal, tecnica...)
- Dê uma boa aparência a suas ideias caso elas sejam apresentadas, elas são importantes... Utilize editores de textos para isso.
- Conhecendo um publico alvo: O acróstico ASTUTO.
- É o que você diz e a maneira como diz.

## Capítulo 02 - Uma Abordagem Pragmática
- Como surge a duplicação?
- Duplicação imposta. Os desenvolvedores acham que não tem escolha - o ambiente parece pedir a duplicasção
- Duplicação indvertida. Os desenvolvedor não percebem que estão duplicando informações.
- Duplicação impaciente. Os desenvolvedor ficam com preguiça e duplicam porque parece mais fáci.
- Princípio NSR (Não se repita).
- Cada bloco de informações deve ter uma representação oficial, exclusiva e sem ambiguidades dentro de um sistema.
- Facilite a reutilização de código, o que tentamos fazer é cultivar um ambiente em que seja mais fácil encontrar e reutilizar coisas existentes em vez de criá-las novamente.
- "Ortogonalidade" vem da geometria. A analogia com a matemática refere-se em que os eixos X e Y de um gráfico são independentes. Se você altera o valor de X, isso não deveria alterar o valor de Y.
- Da mesma forma um sistema ortogonal de software, mexer em um módulo não deveria interferir no funcionamento de outro módulo.
- Ortogonalidade no software refere-se ao princípio de indepÇendencia entre componentes. Facilitanto a escalabilidade e manutenção do sistema.
- Elimine efeitos entre elementos não relacionados.
- Ganho de produtividade pg 56-57.
- Seções de código danificadas ficam isoladas.
- Mantenha o código desvinculado. Escreva módulos que não revelem nada desnecessário para outros módulos e que não dependam de implementação de outros módulos
- Lei de Deméter pg 160.
- Evitar dados globais.
- Evite funções semelhantes e examine o padrão Strategy de Design Paterns
- Teste de unidade não deveria envolver grande parte do sistema.
- A documentação também é favorecida em sistemas ortogonais, se você alterar o código da documentação isso não deveria infringir na explicação da documentação.
- Se o sistema for bem ortogonal, as mudanças no código não devem automaticamente invalidar a documentação, e a documentação pode ser ajustada de forma independente sem afetar a funcionalidade do sistema.
