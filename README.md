# Modelagem-banco-de-dados-seguradora

As entidades "Cliente (com os atributos 'Cpf, Cnh; Email; Nome; Endereço e Número de Telefone" e "Seguradora" ('Cnpj; Endereço; Email e Nome') fazem o primeiro relacionamento dando origem a "Apólice"('Coberturas Contratadas; Partes Envolvidas; Numero; Situação de Contrato'; 'Indenização-valor'; 'Prazo-final-de-pagamento'; '<strong>Condições Especiais, gerais e particulares</strong>'.

![BancodeDadosSeguradoraPtLógico drawio - diagrams net e mais 6 páginas - Pessoal — Microsoft​ Edge 14_05_2022 23_11_48](https://user-images.githubusercontent.com/99990295/168454385-dafd51ff-6a09-4066-a0a4-d9aec175bf10.png)


Mediante a pesquisa que fiz, vi que toda Apólice possui esses três termos, com o objetivo de formalizar o contrato em termos legais e descrever as condições do produto adquirido. Não existe contratação formal de um seguro sem que se tenha esse documento que comprova que a seguradora aceita os riscos cobertos e pagará indenização, em caso de sinistro.
Além disso, a apólice de seguro pode ser contratada para diferentes contextos e garante a proteção ao beneficiário em questão, conforme as cláusulas acordadas entre as partes interessadas.<br>
<br>
A partir da tabela "Apólice", temos mais três entidades, que são os grupos que a Seguradora trabalha, sendo eles "Residência, Tartaruga e Automóvel". Em suas respectivas tabelas, coleto os dados necessários para identificação do segurado, além de fazer outro relacionamento com a entidade "Acidentes". O mesmo irá detalhar e coletar dados sobre a eventualidade, cruzando informações da tabela "Apólice", com o intuito de ver as responsabilidades da Seguradora e direitos do Cliente.

Modelos Conceitual e Lógico completos no Repositório.

Fontes de Pesquisa: <br>
1 - https://www.mutuus.net/blog/apolice-de-seguro-descomplicando/;<br>
2 - https://www.minutoseguros.com.br/blog/apolice-de-seguro-tudo-o-que-voce-precisa-saber/
