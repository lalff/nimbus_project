![image](https://github.com/lalff/nimbus_project/assets/142255965/392566f4-b21c-45e3-9647-88598b87733b)
---

🌩️***Projeto Nimbus***
---

[Sobre a Nimbus](https://github.com/lalff/nimbus_project/blob/main/Sobre%20a%20Nimbus.md)


📚 ***5W2H***
---

-	**QUEM?**

 Qualquer tipo de empresa, instituição ou indivíduo que necessite de dados meteorológicos de alta precisão, como: empresas de construção civil, engenheiros, prefeituras, estaleiros, empresas de dragagem e terraplanagem, Incorporadoras e terminais portuários.
   

- **COMO?**
  
O sistema absorve dados meteorológicos e dados de radar. Equipamentos que ficam monitorando as nuvens dentro de um raio (que aparece em tempo real) e apresentam:
      
    - Dados de raio (descarga elétrica);
    - Dados de estações meteorológicas;
    - Dados das próprias obras e localizações a serem monitoradas. 
 
Utiliza um end-pointing de estações pré-listadas. Eles escolhem o órgão e checam quais estações eles têm numa lista onde consta latitude, longitude e a medida da estação que é usada para colocar no mapa, para visualização do usuário.
  
-	**ONDE?**

O sistema fornecerá para os usuários a utilização da página de histórico de dados por dispositivos móveis e web. Facilitando o uso tanto na rua quanto em escritótio.

-	**QUANDO?** 

Os usuários farão uso do sistema, quando houver a necessidade de busca por dados meteorológicos, tanto para planejamento de obras ou acompanhamento delas, como para monitoramento de cidades ou qualquer outra necessidade do usuário. 

- **O QUÊ? (Quais dados)**

Com variáreis pluviais, variáveis fluviais, variáveis oceânicas e outras menos usadas como a nuclear. A lista muda de estação para estação e muda o formato do Json. 

O sistema deverá apresentar as váriaveis manipuladas pela Nimbus de forma intuitiva e objetiva para os usuários.

- 	**POR QUÊ?** 

A renovação no sistema vem para suprir a necessidade de transformar os dados fornecidos pela Nimbus de forma mais intuitiva para o usuário, além de melhorar o desempenho visual e trazer responsividade aos objetos manipulados pelo sistema. Permitindo também exportações CSV, PDF e PNG.

🔨 ***PROPÓSITO***
---

- **Propósito do Projeto:**

O propósito do projeto é reformular a interface da página de histórico de dados, tornando-a mais clara, interativa e adaptável para uso em dispositivos móveis e web. O objetivo é proporcionar aos usuários uma experiência mais eficiente e informativa ao visualizar e analisar dados georreferenciados. Isso inclui a correlação de marcadores georreferenciados no mapa, gráficos de diferentes tipos (barra, vetores e linear) e tabelas de dados, tudo sem a necessidade de download prévio. Além disso, o projeto visa facilitar a exportação de dados em formatos como CSV, PDF e PNG.

- **Propósito do Sistema:**

O propósito do sistema é fornecer aos usuários uma plataforma intuitiva para acesso e analise de dados georreferenciados de forma eficaz. Isso implica em:

1. Visualização de Dados Georreferenciados: O sistema deve permitir que os usuários visualizem marcadores georreferenciados em um mapa interativo, com um polígono que altere sua cor de acordo com as variáveis.

2. Correlação de Dados: Os usuários devem ser capazes de correlacionar dados na tabela, mapa e gráficos (barra, vetores e linear). Essa correlação deve ser intuitiva e permitir a análise simultânea das variáveis.

3. Visualização em Dispositivos Móveis: O sistema deve ser adaptável para diferentes formatos de tela e dispositivos.
   
4. Exportação de Dados: Deve haver um botão de exportação de dados em formatos: CSV, PDF e PNG.

5. Clareza e Usabilidade: A interface deve ser projetada para ser clara e intuitiva, garantindo que os usuário possa compreender os dados facilmente e realizar análises de maneira eficiente.

🗒️ ***ELICITAÇÃO***
---


|    |      **Requisitos Funcionais do Sistema**                                          |
| --- | ----------------------------------------------------------- |
| RF1 | O sistema deverá exportar dados em formato: CSV, PDF e PNG.             |
| RF2 | O sistema deverá apresentar um mapa contendo um polígono de localização, que altera a cor de acordo com as alterações das variáveis meteorológicas. |
| RF3 | O sistema deverá oferecer um filtro de dados integrado ao mapa, tabela e gráfico com alteração sincrônica. |
| RF4 | O sistema deverá fornecer um gráfico (linear, de barras e de vetores) ajustável, em escala de amplitude e tempo. |
| RF5 | O sistema deverá apresentar uma tabela de dados visualmente clara.       |
| RF6 | O sistema deverá apresentar um formulário de busca com filtros (data inicial e final, tipo de variável, ponto de monitoramento, frequência e operação matemática utilizada). |


|    |      **Requisitos Não-Funcionais do Sistema**                                           |
| --- | ----------------------------------------------------------------- |
| RNF1 | O sistema deverá oferecer adaptação para uso Mobile             |
| RNF2 | O sistema deverá ser responsivo.                                 |
| RNF3 | O sistema deverá ser desenvolvido com React.                                                                          |
| RNF4 | O sistema deverá tratar o Json com os dados.                                                         |
| RNF5 | O sistema deverá apresentar uma experiência intuitiva para o usuário.       |
| RNF6 | O sistema deverá estar disponível 24h por dia.                                      |      


👨‍💻 ***CASOS DE USO:***
---
**Caso de uso: Visualizar dados**
- **Ator:** Usuário.
- **Pré condições:** O usuário precisará estar logado no sistema e ter acesso a página de dados.
- **Fluxo Básico:**

1- O usuário seleciona a página de histórico de dados.

2- O sistema fornece as opções de visualização: mapa, tabela ou gráfico.

3- O usuário seleciona o tipo de visualização de sua preferência.

4- O usuário seleciona a data de início e final.

5- O usuário define a preferência entre as seguintes variáveis:

- Precipitação 10min
- Nível do rio 15 min 
- Direção do vento
- Temp. ponto de orvalho
- Umidade relativa, 
- Precipitação 15min
- Cota de transbordamento
- Rajada de vento
- Visibilidade
- Precipitação 1h
- Velocidade do vento
- Temperatura 
- Descrição do tempo

6- O usuário escolhe a estação meteorológica (a localizão mais próxima).

7- O sistema retona as informações selecionadas pelo usuário.
  
- **Pós-condições:**

1-  O usuário tem acesso aos dados.

2-  O usuário pode manipular e fazer alterações nas váriaveis, data e localização para nova analise.

**Caso de uso: Emitir relatório**
- **Ator:** Usuário.
- **Pré condições:** O usuário precisará estar logado no sistema e ter acesso a página de dados.
- **Fluxo Básico:**

1- O usuário escolhe a localização.

2- O usuário seleciona o intervalo de tempo desejado (início e fim) a ser analisado.

3- O usuário seleciona a preferência entre as seguintes váriaveis:
- Precipitação 10min
- Nível do rio 15 min 
- Direção do vento
- Temp. ponto de orvalho
- Umidade relativa, 
- Precipitação 15min
- Cota de transbordamento
- Rajada de vento
- Visibilidade
- Precipitação 1h
- Velocidade do vento
- Temperatura 
- Descrição do tempo

4- O usuário escolhe o formato de arquivo desejado para download (CSV, PDF ou PNG).

5- O usuário clica na opção de exportar.

- **Pós-condições:**

1- O usuário obterá um relatório exportado para o seu disponsitivo no formato desejado.

**Caso de uso: Interação com o mapa**

- **Ator:** Usuário.
- **Pré condições:** O usuário precisará estar logado no sistema e ter acesso a página de dados.
- **Fluxo Básico:**

1- O usuário seleciona a localização que deseja, usando um polígono no mapa.

2- O usuário a partir da região selecionada no mapa, poderá especificar uma determinada área de uma estação próxima.

3- O usuário seleciona o intervalo de tempo.

4- O usuário seleciona as váriaveis a serem manipuladas.

- **Pós-condições:**

1- O usuário obtém as informações do ponto selecionado para análise.

🔎***Layout***
---
📱**Mobile**
<br>
[Protótipo](https://www.figma.com/file/T2ll7aay22ZZSgBbSu3GKz/Nimbus-mobile?type=design&node-id=0-1&mode=design&t=VURFEupoBCaZrToO-0)
<br>
💻**Desktop**
<br>
[Protótipo](https://www.figma.com/file/D1dlNDwEn62nU8cJljysIG/NIMBUS-WEB?type=design&node-id=0-1&mode=design&t=Mms0bXSbvowGHmgN-0)

🔒**Código do Aplicativo**
---
[Código](https://github.com/fffcamacho/nreact)

💎 ***GRUPO LALFF***
---

Fernanda Camacho
<br>Luã Macedo
<br>Luiza Conrado 
<br>Fabiano Amorim
<br>Anna Flores
