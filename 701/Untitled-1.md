SELECT nome_razao, cpf_cnpj, dia_fechamento, valor_hora_avulsa, horas_contratadas, otrs_customer_id, valor_contrato, iss_retido_fonte, dia_vencimento from clientes  where possui_contrato = 'S' and nome_razao like '%Tce%' order by nome_razao asc;



```
SELECT nome_razao, cpf_cnpj, dia_fechamento, valor_hora_avulsa, horas_contratadas, otrs_customer_id, valor_contrato, iss_retido_fonte, dia_vencimento from clientes  where possui_contrato = 'S' and nome_razao like '%Tce%' order by nome_razao asc;
 nome_razao |    cpf_cnpj    | dia_fechamento | valor_hora_avulsa | horas_contratadas | otrs_customer_id | valor_contrato | iss_retido_fonte | dia_vencimento 
------------+----------------+----------------+-------------------+-------------------+------------------+----------------+------------------+----------------
 Tce        | 09499757000146 |             30 |              0.00 |                60 | TCE              |       14000.00 | S                |              0
(1 registro)
```

