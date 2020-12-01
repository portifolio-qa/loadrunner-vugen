# Teste de performance

Teste de performance/desempenho é um processo de teste de software,
utilizado para testar a velocidade, tempo de resposta, estabilidade,
confiabilidade, escabilidade e uso de recursos de um aplicativo de software
sob uma carga de trabalho específica.<br />
    O principal objetivo do teste de desempenho é identificar e eliminar os 
gargalhos de desempenho no aplicativo de software. <br />
<strong>- Velocidade:</strong> determina se o aplicativo responde rapidamente;<br />
<strong>- Escabilidade:</strong> determina a carga máxima do usuário que o aplicativo de software
pode suporte;<br />
<strong>- Estabilidade:</strong> determina se o apicativo é estável sob uma cargas variadas.<br />

# Por que fazer testes de desempenho?

Recursos e funcionalidade suportados por um sistema de software não são a única preocupação. 

O desempenho de um aplicativo de software, como seu tempo de resposta, confiabilidade, uso de recursos e escalabilidade, são importantes. O objetivo do Teste de Desempenho não é encontrar bugs, mas eliminar gargalos de desempenho.

* O Teste de Desempenho é feito para fornecer aos interessados ​​informações sobre seus aplicativos em relação à velocidade, estabilidade e escalabilidade.

* Sem o teste de desempenho, é provável que o software sofra de problemas como: execução lenta enquanto vários usuários o utilizam simultaneamente, inconsistências em diferentes sistemas operacionais e baixa usabilidade.

* O teste de desempenho determinará se o software atende aos requisitos de velocidade, escalabilidade e estabilidade sob as cargas de trabalho esperadas.

* Os aplicativos enviados ao mercado com métricas de desempenho insatisfatórias devido a testes de desempenho insatisfatórios ou inexistentes provavelmente ganharão uma reputação ruim e não atenderão às metas de vendas esperadas.

* Aplicativos de missão crítica, como programas de lançamento espacial ou equipamentos médicos que salvam vidas, devem ter seu desempenho testado para garantir que sejam executados por um longo período sem desvios.

# Tipos de teste de desempenho

## Teste de carga 

- verifica a capacidade do aplicativo de funcionar sob cargas de usuário previstas. O objetivo é identificar gargalos de desempenho antes que o aplicativo de software entre no ar.

## Teste de estresse 

- envolve testar um aplicativo sob cargas de trabalho extremas para ver como ele lida com alto tráfego ou processamento de dados. O objetivo é identificar o ponto de ruptura de um aplicativo.

## Teste de resistência 

- é feito para garantir que o software possa lidar com a carga esperada por um longo período de tempo.

## Teste de pico 

- testa a reação do software a grandes picos repentinos na carga gerada pelos usuários.

## Teste de volume 

- Em Teste de volume grande no. do. Os dados são preenchidos em um banco de dados e o comportamento geral do sistema de software é monitorado. O objetivo é verificar o desempenho do aplicativo de software em vários volumes de banco de dados.

## Teste de escalabilidade 

- O objetivo do teste de escalabilidade é determinar a eficácia do aplicativo de software na "ampliação" para suportar um aumento na carga do usuário. Ajuda a planejar a adição de capacidade ao seu sistema de software.


# Problemas comuns de desempenho

- A maioria dos problemas de desempenho gira em torno de velocidade, tempo de resposta, tempo de carregamento e baixa escalabilidade.

- A velocidade costuma ser um dos atributos mais importantes de um aplicativo.

- Um aplicativo de execução lenta perderá usuários em potencial.

- O teste de desempenho é feito para garantir que um aplicativo seja executado com rapidez suficiente para manter a atenção e o interesse do usuário. 

## Tempo de carregamento longo 

- o tempo de carregamento é normalmente o tempo inicial que leva para um aplicativo iniciar. Geralmente, isso deve ser mínimo. Enquanto alguns aplicativos são impossíveis de carregar em menos de um minuto, o tempo de carregamento deve ser mantido em alguns segundos, se possível.

## Tempo de resposta insatisfatório 
- o tempo de resposta é o tempo que leva desde o momento em que um usuário insere dados no aplicativo até que o aplicativo emita uma resposta a essa entrada. Geralmente, isso deve ser muito rápido. Novamente, se um usuário tiver que esperar muito tempo, ele perderá o interesse.

## Escalabilidade ruim 
- Um produto de software sofre de escalabilidade ruim quando não pode lidar com o número esperado de usuários ou quando não acomoda uma gama ampla de usuários. O teste de carga deve ser feito para ter certeza de que o aplicativo pode lidar com o número previsto de usuários.

## Gargalo
- Gargalos são obstruções em um sistema que degradam o desempenho geral do sistema. O afunilamento ocorre quando erros de codificação ou problemas de hardware causam uma diminuição da taxa de transferência sob certas cargas. Freqüentemente, o gargalo é causado por uma seção defeituosa do código. A chave para corrigir um problema de gargalo é encontrar a seção do código que está causando a lentidão e tentar consertá-la lá. O gargalo geralmente é corrigido corrigindo processos de execução inadequada ou adicionando hardware. Alguns gargalos de desempenho comuns são:
Utilização da CPU
Utilização de memória
Utilização da rede
Limitações do sistema operacional
Uso de disco


# Processo de teste de desempenho

A metodologia adotada para o teste de desempenho pode variar amplamente, mas o objetivo dos testes de desempenho permanece o mesmo.  Isso pode ajudar a demonstrar que seu sistema de software atende a certos critérios de desempenho predefinidos. Ou pode ajudar a comparar o desempenho de dois sistemas de software. Também pode ajudar a identificar partes do sistema de software que degradam seu desempenho.<br />

## Processo genérico sobre como realizar testes de desempenho

1. <strong> Identifique seu ambiente de teste</strong> - Conheça seu ambiente de teste físico, ambiente de produção e quais ferramentas de teste estão disponíveis. Compreenda os detalhes das configurações de hardware, software e rede usados ​​durante o teste antes de iniciar o processo de teste. Isso ajudará os testadores a criar testes mais eficientes. Também ajudará a identificar possíveis desafios que os testadores podem encontrar durante os procedimentos de teste de desempenho.<br />

2. <strong> Identifique os critérios de aceitação de desempenho</strong> - Isso inclui metas e restrições de rendimento, tempos de resposta e alocação de recursos. Também é necessário identificar os critérios de sucesso do projeto fora desses objetivos e restrições. Os testadores devem ter autonomia para definir critérios e objetivos de desempenho, porque muitas vezes as especificações do projeto não incluem uma variedade suficientemente ampla de benchmarks de desempenho. Às vezes, pode não haver nenhum. Sempre que possível, encontrar um aplicativo semelhante para comparar é uma boa maneira de definir metas de desempenho.<br />

3. <strong> Planejar e projetar testes de desempenho </strong> - Determine como o uso provavelmente variará entre os usuários finais e identifique os principais cenários para testar todos os casos de uso possíveis. É necessário simular uma variedade de usuários finais, planejar dados de teste de desempenho e delinear quais métricas serão coletadas.<br />
Configurando o ambiente de teste - Prepare o ambiente de teste antes da execução. Além disso, organize ferramentas e outros recursos.<br />

4. <strong> Implementar design de teste </strong> - crie os testes de desempenho de acordo com seu design de teste.
Execute os testes - execute e monitore os testes.<br />
Analise, ajuste e teste novamente - consolide, analise e compartilhe os resultados do teste. Em seguida, ajuste e teste novamente para ver se há uma melhoria ou diminuição no desempenho. Como as melhorias geralmente ficam menores a cada novo teste, pare quando o gargalo for causado pela CPU. Então você pode considerar a opção de aumentar a potência da CPU.<br />

# Métricas de teste de desempenho: parâmetros monitorados

Os parâmetros básicos monitorados durante o teste de desempenho incluem:<br />

* <strong>Uso do processador</strong> - uma quantidade de tempo que o processador gasta executando threads não ociosos.<br />

* <strong> Uso de memória</strong> - quantidade de memória física disponível para processos em um computador.<br />

* <strong>Tempo do disco </strong>- quantidade de tempo que o disco fica ocupado executando uma solicitação de leitura ou gravação.
Largura de banda - mostra os bits por segundo usados ​​por uma interface de rede.<br />

* <strong>Bytes privados </strong>- número de bytes que um processo alocou que não pode ser compartilhado entre outros processos. Eles são usados ​​para medir o uso e vazamentos de memória.<br />

* <strong>Memória comprometida </strong>- quantidade de memória virtual usada.<br />

* <strong>Páginas de memória / segundo </strong>- número de páginas gravadas ou lidas no disco para resolver falhas de página física. As falhas de página física ocorrem quando o código que não pertence ao conjunto de trabalho atual é chamado de outro lugar e recuperado de um disco.<br />

* <strong>Falhas de página / segundo </strong>- a taxa geral em que as páginas de falha são processadas pelo processador. Isso ocorre novamente quando um processo requer código de fora de seu conjunto de trabalho.<br />

* <strong>Interrupções de CPU por segundo </strong>- é o avg. número de interrupções de hardware que um processador está recebendo e processando a cada segundo.<br />

* <strong>Comprimento da fila de disco </strong>- é o valor médio não. de solicitações de leitura e gravação enfileiradas para o disco selecionado durante um intervalo de amostra.<br />

* <strong>Comprimento da fila de saída de rede </strong>- comprimento da fila de pacotes de saída em pacotes. Qualquer coisa acima de dois significa que um atraso e gargalos precisam ser interrompidos.
Total de bytes de rede por segundo - classifica quais bytes são enviados e recebidos na interface, incluindo caracteres de enquadramento.<br />

* <strong>Tempo de resposta </strong>- tempo a partir do momento em que um usuário insere uma solicitação até o primeiro caractere da resposta ser recebido.<br />

* <strong>Taxa de transferência</strong> - taxa em que um computador ou rede recebe solicitações por segundo.
Quantidade de pool de conexão - o número de solicitações do usuário que são atendidas por conexões em pool. Quanto mais solicitações atendidas por conexões no pool, melhor será o desempenho.<br />

* <strong>Máximo de sessões ativas</strong> - o número máximo de sessões que podem estar ativas de uma vez.<br />

* <strong>Taxas de acerto </strong>- Isso tem a ver com o número de instruções SQL que são tratadas por dados em cache em vez de operações caras de E / S. Este é um bom lugar para começar a resolver problemas de gargalo.<br />

* <strong>Acessos por segundo </strong>- o não. de ocorrências em um servidor da web durante cada segundo de um teste de carga.<br />

* <strong>Segmento de rollback </strong>- a quantidade de dados que podem ser revertidos a qualquer momento.
Bloqueios de banco de dados - o bloqueio de tabelas e bancos de dados precisa ser monitorado e cuidadosamente ajustado.<br />

* <strong>Principais esperas</strong> - são monitoradas para determinar quais tempos de espera podem ser reduzidos ao lidar com a rapidez com que os dados são recuperados da memória

* <strong>Contagens de threads</strong> - a integridade de um aplicativo pode ser medida pelo número. de threads que estão em execução e atualmente ativos.<br />

* <strong>Coleta de lixo </strong>- tem a ver com o retorno de memória não utilizada ao sistema. A coleta de lixo precisa ser monitorada quanto à eficiência.<br />

# Casos de teste de desempenho de exemplo

- Verifique se o tempo de resposta não é superior a 4 segundos quando 1000 usuários acessam o site simultaneamente.
Verifique se o tempo de resposta do aplicativo sob carga está dentro de uma faixa aceitável quando a conectividade de rede é lenta<br />
- Verifique o número máximo de usuários que o aplicativo pode controlar antes de travar.<br />
- Verifique o tempo de execução do banco de dados quando 500 registros são lidos / gravados simultaneamente.<br />
- Verifique o uso de CPU e memória do aplicativo e do servidor de banco de dados em condições de pico de carga<br />
- Verifique o tempo de resposta da aplicação em condições de carga baixa, normal, moderada e pesada.<br />

Durante a execução do teste de desempenho real, termos vagos como faixa aceitável, carga pesada, etc. são substituídos por números concretos. Os engenheiros de desempenho definem esses números de acordo com os requisitos de negócios e o panorama técnico do aplicativo.<br />

# Ferramentas de teste de desempenho

Há uma grande variedade de ferramentas de teste de desempenho disponíveis no mercado. A ferramenta que você escolher para teste dependerá de muitos fatores, como tipos de protocolo com suporte, custo da licença, requisitos de hardware, suporte de plataforma, etc. Abaixo está uma lista de ferramentas de teste usadas popularmente.<br />


<strong>LoadNinja</strong> - está revolucionando a maneira como testamos o carregamento. Esta ferramenta de teste de carga baseada em nuvem capacita as equipes a gravar e reproduzir instantaneamente testes de carga abrangentes, sem correlação dinâmica complexa e executar esses testes de carga em navegadores reais em escala. As equipes podem aumentar a cobertura do teste. e reduzir o tempo de teste de carga em mais de 60%.<br />

<strong>NeoLoad</strong> - é a plataforma de teste de desempenho projetada para DevOps que se integra perfeitamente ao seu pipeline de Entrega Contínua existente. Com o NeoLoad, as equipes testam 10 vezes mais rápido do que com as ferramentas tradicionais para atender ao novo nível de requisitos em todo o ciclo de vida de desenvolvimento de software Agile - de componentes a testes de carga de todo o sistema.<br />

<strong>HP LoadRunner </strong>- é a ferramenta de teste de desempenho mais popular do mercado hoje. Essa ferramenta é capaz de simular centenas de milhares de usuários, colocando aplicativos sob cargas reais para determinar seu comportamento sob cargas esperadas. O Loadrunner apresenta um gerador de usuário virtual que simula as ações de usuários humanos ao vivo.<br />

<strong>Jmeter</strong> - uma das principais ferramentas usadas para testes de carga de servidores web e de aplicativos.<br />

# Quais aplicativos devemos testar de desempenho?

O teste de desempenho é sempre feito apenas para sistemas baseados em cliente-servidor. Isso significa que qualquer aplicativo que não seja uma arquitetura baseada em cliente-servidor não deve requerer Teste de Desempenho.<br />

Por exemplo, o Microsoft Calculator não é baseado em cliente-servidor nem executa vários usuários; portanto, não é um candidato para Teste de Desempenho.<br />


# Qual é a diferença entre: <br />Teste de Desempenho e Engenharia de Desempenho

- O Teste de Desempenho é uma disciplina preocupada em testar e relatar o desempenho atual de um aplicativo de software sob vários parâmetros.<br />

- Engenharia de desempenho é o processo pelo qual o software é testado e ajustado com a intenção de obter o desempenho necessário. Este processo visa otimizar o traço de desempenho do aplicativo mais importante, ou seja, a experiência do usuário.<br />

Historicamente, teste e ajuste têm sido domínios distintamente separados e frequentemente concorrentes. Nos últimos anos, entretanto, vários grupos de testadores e desenvolvedores têm colaborado de forma independente para criar equipes de ajuste. Como essas equipes tiveram um sucesso significativo, o conceito de acoplar testes de desempenho com ajuste de desempenho se popularizou, e agora chamamos isso de engenharia de desempenho.<br />

# Conclusão

Em Engenharia de Software, o teste de desempenho é necessário antes de comercializar qualquer produto de software. Ele garante a satisfação do cliente e protege o investimento do investidor contra falha do produto. Os custos dos testes de desempenho são geralmente mais do que compensados ​​com maior satisfação, fidelidade e retenção do cliente.

 