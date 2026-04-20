
Exercícios 

1. Defina Defesa em Profundidade e explique como ela evita que uma única falha derrube o sistema.
R: A Defesa em Profundidade é uma estratégia que utiliza múltiplas camadas de segurança. Ela evita que uma única falha derrube o sistema porque, se uma camada for comprometida, as outras camadas continuam protegendo.

2 .O que é o Princípio do Menor Privilégio e como ele é aplicado no acesso a bancos de dados?
R: É o princípio de fornecer apenas o acesso e as permissões necessárias para que um usuário ou processo realize sua tarefa específica. No acesso a bancos de dados, ele é aplicado restringindo permissões como um usuário comum excluir uma tabela ou algo do tipo

3. Explique o conceito de Superfície de Ataque e dê três exemplos de como reduzi-la.
R: A superfície de ataque representa todos os pontos de entrada onde um invasor pode tentar entrar ou extrair dados de um sistema. Desativar serviços e portas que não estão sendo utilizados, remover funcionalidades ou códigos desnecessários e limitar o acesso de usuários a interfaces críticas são exemplos de como reduzi-las.

4. Por que a Segurança por Obscuridade é considerada uma má prática isoladamente?
R: Porque ela baseia a segurança no fato de o invasor não conhecer o funcionamento interno do sistema. Se esse segredo for descoberto, o sistema perde toda a sua proteção, porque não possui controles de segurança robustos e visíveis para impedir o ataque.

5. O que são Fronteiras de Confiança e por que são cruciais no design de microsserviços?
R: Fronteiras de confiança são perímetros que separam diferentes níveis de confiança dentro de um sistema (ex: entre um usuário externo e o banco de dados interno). Em microsserviços, elas são cruciais para garantir que cada serviço valide rigorosamente as informações vindas de outros serviços ou fontes externas, impedindo o movimento lateral de ameaças.

6. Diferencie Fail-Safe de Fail-Open com um exemplo de firewall.
R: FS em caso de falha, o sistema prioriza a segurança. Exemplo: Um firewall que trava e bloqueia todo o tráfego de rede até ser reiniciado. e o FO em caso de falha, o sistema prioriza a disponibilidade. Exemplo: Um firewall que, ao falhar, permite a passagem de todo o tráfego para não interromper o serviço.

7. Como o Sandboxing auxilia na proteção contra vulnerabilidades de Dia Zero?
R: O Sandboxing isola a execução de processos em um ambiente restrito. Como vulnerabilidades do dia zero são desconhecidas, o sandbox garante que, mesmo que o invasor consiga explorar a falha, ele ficará confinado naquele ambiente isolado e não conseguirá afetar o sistema operacional principal ou outros dados.

8. Qual a relação entre o Princípio da Simplicidade e a segurança do código?
R: Quanto mais simples for o código, menor a probabilidade de erros humanos e vulnerabilidades ocultas. Códigos complexos são mais difíceis de auditar, testar e manter, o que facilita a existência de falhas de segurança que podem passar despercebidas.

9. O que é Egress Filtering e qual sua função em uma arquitetura de defesa?
R: É a filtragem do tráfego de rede que sai de uma rede privada em direção à internet. Sua função é impedir que um sistema já comprometido envie dados sensíveis para o invasor ou se comunique com servidores de comando maliciosos.

10. Descreva o modelo Zero Trust e sua principal mudança de paradigma.
R: O modelo Zero Trust assume que nenhuma tentativa de acesso deve ser confiada por padrão, mesmo que venha de dentro da rede interna. A mudança de paradigma é o fim do "perímetro de rede confiável"; agora, cada usuário e dispositivo deve ser verificado e autenticado continuamente para cada recurso que tentar acessar.
```
