# Aurora

Você manda uma prévia do seu trabalho em particular. Dias depois, o arquivo está rodando num grupo que você nem conhece. Você denuncia, a plataforma tira do ar, e na semana seguinte alguém sobe o mesmo arquivo de novo.

A Aurora é o jeito de pensar segurança do **Lynkyz**, uma rede social para criadores e para quem acompanha o trabalho deles. Ela está em desenvolvimento dentro do Lynkyz, com recursos já implementados e testes escritos no backend.

## O que já existe

**A primeira decisão vale para as próximas.** Quando a moderação restringe um arquivo depois de uma denúncia, o Lynkyz reconhece uma cópia idêntica pela impressão digital e barra o reenvio. Quem foi afetado não precisa denunciar tudo de novo quando o arquivo reaparece.

A restrição é sobre o arquivo, não sobre a conta. Quem tenta subir uma cópia pode ser a própria vítima documentando o caso, e punir isso automaticamente seria errar justamente contra ela.

**Cada cópia tem a sua marca.** Cópias entregues recebem uma marcação individual, que ajuda a investigar de onde saiu um vazamento sem expor dados de quem recebeu.

**Contato indesejado tem bloqueio.** Bloqueios de interação já funcionam para quem não quer mais ser procurado por alguém.

## O que ainda falta

- O reconhecimento cobre cópias idênticas. Um arquivo recortado ou recomprimido ainda passa.
- A remoção de metadados de localização precisa ser validada em todos os formatos.
- A marcação invisível de conteúdo ainda está em validação.
- Uma integração com o [StopNCII](https://stopncii.org/) é uma possibilidade em estudo.

## Para quem cria

O sistema já calcula ganhos líquidos, vendas por dia e valores por tipo de transação.

A ambição é usar esse histórico para responder perguntas concretas. Em quais horários vale abrir vagas para chamadas? Cabe mais um pedido personalizado antes das férias? As recomendações com aprendizado de máquina são uma próxima etapa.

## Onde está o código

No repositório privado do Lynkyz. Este repositório existe para contar o que a Aurora faz e o que ainda não faz. No futuro ela pode virar um produto próprio, uma IA interna ou um conjunto de regras de cibersegurança para quem cria.

Feito por [Stanley Brandão](https://github.com/SeedetY).
