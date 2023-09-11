# nimbus_project
5W2H/Propósito
---

5W2H

•	**QUEM?**
  Qualquer tipo de empresa, instituição ou indivíduo que necessite de dados meteorológicos de alta precisão, como: empresas de construção civil, engenheiros, prefeituras, estaleiros, empresas de dragagem e terraplanagem, Incorporadoras e terminais portuários.
  
•	**COMO?**
  A plataforma absorve dados meteorológicos e dados de radar. Equipamentos que ficam monitorando as nuvens dentro de um raio (que aparece em tempo real) e apresentam:
- Dados de raio (descarga elétrica);
- Dados de estações meteorológicas; - Dados das próprias obras e localizações a serem monitoradas. 
  Utiliza um end-pointing de estações pré listadas. Eles escolhem o órgão e checam quais estações eles têm numa lista onde consta o nome da estação, latitude, longitude e a medida da estação que é usada para colocar no mapa, para o usuário ver.
  
•	**ONDE?**
 Em lugares de construção civil, mares, dentro de lagos e rios com o monitoramento marítimo, locais suscetíveis a deslizamentos de terra, com o intuito de minimizar danos em obras, cidades, lugares de construção e escritórios.
 
•	**QUANDO?** 
Através de equações físicas e matemáticas (usando IA) conseguem fazer previsões em um espaço de tempo de espaço de até 15 dias, semanalmente ou diariamente.
•	**O QUÊ?** (Quais dados)
Com variáreis pluviais, variáveis fluviais, variáveis oceânicas e outras menos usadas como a nuclear. A lista muda de estação para estação e muda o formato do Json.

•	**POR QUÊ?** 
Para o monitoramento de alterações climáticas (como chuva forte, alteração nas marés e nos lagos) desta forma os usuários poderão reorganizar seus cronogramas de obras, realocação de insumos e mudança no quadro de atividade. O monitoramento das chuvas ou alteração nas marés ajuda a detectar possíveis prejuízos que possam ser gerados na construção civil, em estaleiros, rodovias etc.

**PROPÓSITO**

  Remodelagem da Interface da página. Torná-la clara e interativa para o usuário correlacionando marcadores georreferenciados no mapa, gráfico (barra, vetores e linear) com interação simultânea das variáveis e as tabelas de dados, sem a necessidade de download prévio.
  Apresentar uma interface adaptável para uso Mobile que contenha todas as informações acima, apresentando uma visualização clara que compreenda os desafios de pinçamentos no uso Mobile e tamanho reduzido para visualização.
Botões para Exportação de CSV, PDF e PNG.

**ELICITAÇÃO**
---

**Elementos a serem identificados**

1. **Objetos manipulados pelo sistema:**
- Janela de escolha de estações metereológicas (com datas, localicalização e variáveis).
- Tabela de dados para exportação.
2. **Serviços prestados pelo sistema:**
  Página de dados de estações metereológicas (para previsões num raio de até 15 dias). Na mesma página, há um histórico de dados disponíveis para exportação e elaboração de laudos, que são armazenados no banco de dados e são recuperados através de uma API e exportados em formato de Tabela CSV.
3. **Restrições que devem ser obedecidas (regaras do negócio):**
A ser desenvolvido...

4. **Critérios de Desempenho:**
A ser desenvolvido...


**Resultados Esperados**

**Narrativa em línguagem natural dos requisitos do sistema:**
  Uma página que permita que o usuário interaja simultaneamente com o mapa georreferenciado (com a alteração de cor de acordo com a mudaça metereológica), tabelas e gráfico, quando o usuário escolher as variáveis das estações a serem verificadas.
   Formulário de busca com uma série de critérios com filtros, tabela ser exibida no site com um layout mais organizado para melhorar visualização do usuário.
  O sistema deverá oferecer as mesmas funcinalidades para uso mobile  se adequando a restrição do tamanho da tela, sem perder as caracteríticas que a página oferce no monitor.
  O sistema deverá permitir o download de todas as informações em formato PDF, CSV e PDF.

**Lista de requisitos do sistema:**
- Tabela
- Gráfico
- Mapa
- Botão para download
- Adaptação Mobile
  



