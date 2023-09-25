
 ![image](https://github.com/lalff/nimbus_project/assets/142255965/c71b6d92-a7ac-4804-bb68-2d0b830bdcb7)

---
Formada no Rio de Janeiro no ano de 2020, a Nimbus é uma Construtech de pequeno porte, composta por 6 membros, focada na gestão de risco climático que realiza previsões do tempo em locais listados pelos clientes, é mais utilizada por empresas de construção civil e monitoramento em cidades. A Nimbus ajuda a gerar um aumento significativo de produtividade evitando prejuízos com perda de insumos, que poderia ser causado por mudanças climáticas. 


📚 ***5W2H***
---

-	**QUEM?**

    - Qualquer tipo de empresa, instituição ou indivíduo que necessite de dados meteorológicos de alta precisão, como: empresas de construção civil, engenheiros, prefeituras, estaleiros, empresas de dragagem e terraplanagem, Incorporadoras e terminais portuários.
    - O projeto tem como principal objetivo entregar dados meteorológicos de alta precisão para qualquer tipo de empresa e indivíduo.

- **COMO?**

    - O projeto deverá oferecer todos os tipos de dados disponibilizados pelo software.
    - A plataforma absorve dados meteorológicos e dados de radar. Equipamentos que ficam monitorando as nuvens dentro de um raio (que aparece em tempo real) e apresentam:
      - Dados de raio (descarga elétrica);
      - Dados de estações meteorológicas;
      - Dados das próprias obras e localizações a serem monitoradas. 
 
 Utiliza um end-pointing de estações pré-listadas. Eles escolhem o órgão e checam quais estações eles têm numa lista onde consta latitude, longitude e a medida da estação que é usada para colocar no mapa, para visualização do usuário.
  
-	**ONDE?**

    - O projeto deverá ser desenvolvido pelos individuos do grupo, que farão reuniões semanais via chamadas de video.
    - Em lugares de construção civil, dentro de lagos, rios com o monitoramento marítimo, locais suscetíveis a deslizamentos de terra.

O sistema é usado em lugares de contrução e escritórios.

-	**QUANDO?** 

    - O projeto deverá ser realizado e apresentado semanalmente.
    - Através de equações físicas e matemáticas (usando IA) conseguem fazer previsões em um espaço de tempo de espaço de até 15 dias, semanalmente ou diariamente.

- **O QUÊ? (Quais dados)**

    - O projeto deverá importar uma série de variáveis, de acordo com a necessidade do usuário.
    - Com variáreis pluviais, variáveis fluviais, variáveis oceânicas e outras menos usadas como a nuclear. A lista muda de estação para estação e muda o formato do Json.

- 	**POR QUÊ?** 

    - O projeto deve ser desenvolvido para melhorar e solucionar os problemas e soluções da Nimbus.
    - Para o monitoramento de alterações climáticas (como chuva forte, alteração nas marés e nos lagos) desta forma os usuários poderão reorganizar seus cronogramas de obras, realocação de insumos e mudança no quadro de atividade. O monitoramento das chuvas ou alteração nas marés ajuda a detectar possíveis prejuízos que possam ser gerados na construção civil, em estaleiros, cidades e rodovias.

🔨 ***PROPÓSITO***
---

- **Propósito do Projeto:**

O propósito do projeto é melhorar a interface da página de histórico de dados, tornando-a mais clara, interativa e adaptável para uso em dispositivos móveis. O objetivo é proporcionar aos usuários uma experiência mais eficiente e informativa ao visualizar e analisar dados georreferenciados. Isso inclui a correlação de marcadores georreferenciados no mapa, gráficos de diferentes tipos (barra, vetores e linear) e tabelas de dados, tudo sem a necessidade de download prévio. Além disso, o projeto visa facilitar a exportação de dados em formatos como CSV, PDF e PNG.

- **Propósito do Sistema:**

O propósito do sistema é fornecer aos usuários uma plataforma robusta e intuitiva para acessar e analisar dados georreferenciados de forma eficaz. Isso implica em:

1. Visualização de Dados Georreferenciados: O sistema deve permitir que os usuários visualizem marcadores georreferenciados em um mapa interativo, facilitando a compreensão da distribuição geográfica dos dados.

1. Correlação de Dados: Os usuários devem ser capazes de correlacionar dados no mapa com gráficos (barra, vetores e linear) que mostram informações relacionadas. Essa correlação deve ser intuitiva e permitir a análise simultânea das variáveis.

1. Visualização em Dispositivos Móveis: O sistema deve ser adaptável para uso em dispositivos móveis, levando em consideração restrições de espaço e a necessidade de proporcionar uma experiência de usuário eficiente em telas menores.

1. Exportação de Dados: Deve haver botões de exportação que permitam aos usuários salvar os dados em formatos úteis, como CSV, PDF e PNG, para fins de análise ou compartilhamento.

1. Interação Simultânea: Os usuários devem ser capazes de interagir simultaneamente com o mapa, gráficos e tabelas de dados, sem a necessidade de alternar entre diferentes telas ou janelas.

1. Clareza e Usabilidade: A interface deve ser projetada para ser clara e intuitiva, garantindo que os usuários possam compreender os dados facilmente e realizar análises de maneira eficiente.

1. Recursos de Pinçamento para Dispositivos Móveis: A interface móvel deve incluir recursos de pinçamento (zoom in/out) para facilitar a visualização e a navegação em telas menores.

1. Adaptação a Tamanhos Reduzidos: A interface deve ser projetada para funcionar de maneira eficaz mesmo em dispositivos com telas pequenas, garantindo que todos os elementos importantes sejam acessíveis.

1. Botões para Exportação de CSV, PDF e PNG.

🗒️ ***ELICITAÇÃO***
---


|    |      **Requisitos Funcionais do Sistema**                                          |
| --- | ----------------------------------------------------------- |
| RF1 | O sistema deverá exportar dados em formato: CSV, PDF e PNG.             |
| RF2 | O sistema deverá apresentar um mapa contendo um polígono de localização, que altera a cor de acordo com as alterações climáticas. |
| RF3 | O sistema deverá oferecer um filtro de dados integrado ao mapa, tabela e gráfico com alteração sincrônica. |
| RF4 | O sistema deverá fornecer um gráfico (linear, de barras e de vetores) ajustável, em escala de amplitude e tempo. |
| RF5 | O sistema deverá apresentar uma tabela de dados visualmente clara.       |
| RF6 | O sistema deverá apresentar um formulário de busca com filtros (data inicial e final, tipo de variável, ponto de monitoramento, frequência e operação matemática utilizada). |


|    |      **Requisitos Não-Funcionais do Sistema**                                           |
| --- | ----------------------------------------------------------- |
| RNF1 | O sistema deverá oferecer adaptação para uso Mobile             |
| RNF2 | O sistema deverá ser responsivo.          |
| RNF3 | O sistema deverá ser desenvolvido com React.                                                                          |
| RNF4 | O sistema deverá tratar o Json com os dados. |
| RNF5 | O sistema deverá apresentar uma experiência intuitiva para o usuário.       |

👨‍💻 ***CASOS DE USO***
---

- Nome: O Sistema da Nimbus é pensada para solucionar problemas meteorológicos.
- Ator: 
- Pré condições: O sistema deve estar com suas tabelas, historico de dados e mapas funcionando perfeitamente.
- Fluxo Básico:
1. O cliente faz login na plataforma Nimbus.
1. Na página inicial, o cliente seleciona a opção "Contato".
1. O cliente especifica os seguintes parâmetros:
   1. Localização: O cliente escolhe um ou vários locais onde seus projetos estão em andamento.
   1. Período de Previsão: Define o período de tempo para o qual deseja obter a previsão climática (por exemplo, próximos 7 dias).
1. O sistema Nimbus processa a solicitação do cliente e gera previsões detalhadas para os locais especificados durante o período selecionado.
1.  O cliente recebe as previsões climáticas por meio da plataforma Nimbus e pode acessá-las em tempo real.
- Pós-condições:
1. O cliente utiliza as previsões climáticas fornecidas pela Nimbus para tomar decisões informadas em seus projetos de construção ou operações de monitoramento.
1. O cliente melhora a eficiência operacional, evitando prejuízos causados por mudanças climáticas imprevistas, como atrasos na construção, danos aos equipamentos ou interrupções nos serviços de monitoramento.


💎 ***GRUPO LALFF***
---

Fernanda Camacho
<br>Luã Macedo
<br>Luiza Conrado 
<br>Fabiano Amorim
<br>Anna Flores
  



