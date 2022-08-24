# DESCRIÇÃO
Programa que lê os dados de N contribuintes (N fornecido pelo usuário), os quais</br>
podem ser pessoa física ou pessoa jurídica, em seguida mostra o valor do imposto pago por cada um,</br>
bem como o total de imposto arrecadado.</br>
Os dados de pessoa física são: nome, renda anual e gastos com saúde. Os dados de pessoa jurídica</br>
são nome, renda anual e número de funcionários. As regras para cálculo de imposto são as</br>
seguintes:</br>
Pessoa física: pessoas cuja renda foi abaixo de 20000.00 pagam 15% de imposto. Pessoas com</br>
renda de 20000.00 em diante pagam 25% de imposto. Se a pessoa teve gastos com saúde, 50%</br>
destes gastos são abatidos no imposto.</br>
Exemplo: uma pessoa cuja renda foi 50000.00 e teve 2000.00 em gastos com saúde, o imposto</br>
fica: (50000 * 25%) - (2000 * 50%) = 11500.00</br>
Pessoa jurídica: pessoas jurídicas pagam 16% de imposto. Porém, se a empresa possuir mais de 10</br>
funcionários, ela paga 14% de imposto.</br>
Exemplo: uma empresa cuja renda foi 400000.00 e possui 25 funcionários, o imposto fica:</br>
400000 * 14% = 56000.00</br>
# INPUTS
-Inputs estão entre asteriscos (em itálico no github)<br/> 
Enter the number of tax payers: *3*<br/>
Tax payer #1 data:<br/>
Individual or company (i/c)? *i*<br/>
Name: *Alex*<br/>
Anual income: *50000.00*<br/>
Health expenditures: *2000.00*<br/>
Tax payer #2 data:<br/>
Individual or company (i/c)? *c*<br/>
Name: *SoftTech*<br/>
Anual income: *400000.00*<br/>
Number of employees: *25*<br/>
Tax payer #3 data:<br/>
Individual or company (i/c)? *i*<br/>
Name: *Bob*<br/>
Anual income: *120000.00*<br/>
Health expenditures: *1000.00*<br/>
# OUTPUTS
TAXES PAID:
Alex: $ 11500.00
SoftTech: $ 56000.00
Bob: $ 29500.00
TOTAL TAXES: $ 97000.00