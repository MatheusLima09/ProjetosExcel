# FerramentaInvestimentos

<p>Esta é uma ferramenta para auxiliar o investimento de fundos imobiliários (FIIs/REITs). Ela foi criada no Excel com base em 5 perguntas de negócio:</p>

<p>-Quanto investir por mês?<br>
-Por quantos anos investir?<br>	
-Qual é a taxa de rendimento mensal?<br>	
-Patrimônio acumulado no período?<br>	
-Quanto é o valor os dividendos mensais?</p>	

<p>Com isso, o workbook tem 2 worksheets:</p>

 <p>1. Aplicativo -> worksheet principal, possui 5 tabelas:</p>
   
  1.1. Configurações -> tem 2 campos em branco para digitar o rendimento da carteira e o salário, e um campo com um valor de sugestão de investimento calculado com os dois parâmetros anteriores;
  <br>1.2. Investimento mensal -> tem 3 campos em branco para digitar o investimento mensal, quantos anos investir e a taxa de rendimento mensal, com esses parâmetros, será calculado o patrimônio acumulado no período e o valor dos dividendos mensais;
  <br>1.3. Cenários -> mostra o patrimônio acumulado e os dividendos mensais em possíveis cenários de tempo de investimento com base no valor investido e na taxa de rendimento mensal;
  <br>1.4. Tabela com percentual sugrido de investimento (valor investido) -> mostra o percentual sugerido para os diversos tipos de FIIs/REITs e perfis de investidor. Calcula o percentual em dinheiro com base no valor investido;
  <br>1.5. Tabela com percentual sugrido de investimento (valor sugerido) -> o mesmo que a tabela anterior Calcula o percentual em dinheiro com base no valor sugerido para investir;
  
  1.6. Além das tabelas há um gráfico mostrando o percentual de investimento sugerido para cada tipo de FII e perfil de investidor<br>
  
 <p>2. Support_table -> worksheet secundária, possui uma tabela de apoio para auxiliar nos cálculos e formatações da worksheet principal. A tabela tem 4 colunas: coluna chave, que combina o tipo de FII e perfil de investidor; coluna do perfil de investidor; coluna com o tipo de FII; coluna valor sugerido para investimento. Além disso, o há um campo para selecionar o um valor da coluna chave, ao fazer isso, ele trará o valor sugerido de investimento logo à direita deste campo de seleção e destacará a linha da tabela que contém esse valor na coluna chave.
 </p>

<p>OBS: este projeto foi feito no Excel online, portanto, a formatação pode estar ligeiramente diferente do esperado no aplicativo do Excel. Para isso, confira as prints das worksheets na pasta /imagens</p>
