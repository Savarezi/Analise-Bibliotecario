# Análise de Empréstimos de Biblioteca
# Objetivo:
O objetivo desta análise é entender o uso das bibliotecas por meio dos empréstimos realizados, identificar padrões e fazer recomendações para a melhoria da infraestrutura, recursos e processos das bibliotecas. A análise inclui o acompanhamento de empréstimos ao longo dos anos, a identificação de temas mais e menos emprestados, e a exploração de dados relacionados a horários e meses com maior demanda.
##
# Estrutura dos Dados
Os dados analisados incluem informações sobre:

* Empréstimos de livros
* Classificação dos livros segundo a CDU (Classificação Decimal Universal)
* Tipo de vínculo dos usuários
* Coleções e bibliotecas
##
# Análise Realizada
# 1. Classificação dos Livros

# Objetivo:

 Criar uma nova coluna que reflete a classe geral na CDU com base no código de localização dos livros.
 
Ações:

* Excluímos a coluna registro_sistema que não era relevante para a análise.

* Transformamos a coluna matricula_ou_siape para o formato string para melhor legibilidade.
##
# 2. Análise de Empréstimos ao Longo dos Anos
   
* Objetivo: Determinar se a quantidade total de exemplares emprestados está aumentando ou diminuindo ao longo dos anos.

* Método: Calculamos a quantidade total de exemplares emprestados por ano e plotamos um gráfico de linhas.
##
# 3. Análise Mensal dos Empréstimos

* Objetivo: Identificar quais meses têm a maior quantidade de exemplares emprestados para otimizar a programação de recursos e atividades.
  
* Método: Geramos uma tabela com a quantidade total de exemplares emprestados por mês e plotamos um gráfico de linhas.
##
# 4. Análise Diária dos Empréstimos

* Objetivo: Verificar os horários com maior quantidade de empréstimos para alocar atividades não relacionadas ao atendimento ao usuário.

* Método: Plotamos um gráfico de barras para visualizar os horários com maior número de empréstimos.
##
# 5. Exploração das Variáveis Categóricas

* Objetivo: Explorar e analisar as variáveis categóricas como Tipo de Vínculo, Coleção, Biblioteca e Classificação Geral da CDU.

* Método: Geramos tabelas de frequência e percentuais para essas variáveis.
##
# 6. Boxplots de Empréstimos Mensais por Ano

*Objetivo: Analisar a distribuição dos empréstimos de exemplares mensais entre 2010 e 2020 para diferentes tipos de usuários.

* Método: Criamos boxplots para cada ano e tipo de usuário.
##
# 7. Diferença Percentual de Empréstimos por Curso
   
* Objetivo: Comparar a diferença percentual de empréstimos realizados entre os anos de 2017-2018, 2018-2019, 2019-2022.
  
* Método: Criamos uma tabela com as diferenças percentuais e formatamos o HTML com as seguintes características:
  
    * Sem numeração de índice
      
    *  Números percentuais com símbolo “%” e cores diferenciadas para valores positivos e negativos (verde para positivos, vermelho para negativos).
 
![Captura de tela 2024-09-06 132340](https://github.com/user-attachments/assets/309c34f3-1ec5-4533-8265-da598b9fce17)

  ##
  # Como Usar o Código
  
# Preparação dos Dados

* Certifique-se de que os dados estejam organizados conforme descrito acima.

* Execute os scripts de pré-processamento para limpar e formatar os dados.
  Análise e Visualização

* Utilize as funções e scripts fornecidos para realizar a análise e gerar os gráficos e tabelas.
  Geração de HTML

* O HTML para a tabela com diferenças percentuais pode ser gerado usando o script fornecido, garantindo que ele atenda aos requisitos de formatação especificados.
#########

# Conclusão 🎯

* A análise revelou tendências significativas nos empréstimos ao longo dos anos 📈, meses 📅 e horários ⏰. Identificamos os períodos de maior e menor demanda, possibilitando um planejamento mais eficaz para a gestão de recursos e programação das atividades 📊. Essas informações fornecerão à diretoria insights valiosos para aprimorar a infraestrutura e estratégias da biblioteca 📚.















