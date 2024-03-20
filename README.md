# Projeto ada-cloudservices

O sistema verifica se alguma transação seguida foi realizada em alguma outra unidade federativa(estado) a partir da última unidade utilizada.

Execute o arquivo deploy.sh para subir os containers e instalar dependencias:

`bash deploy.sh`

Após isso, ativar o consumer:

`python consumer.py`

Ativar o producer que gerará as mensagens:

`python producer.py`

As transções geradas pelo producer estão no arquivo `transactions.json`.

O arquivo/link com número da conta passível de fraude vai estar disponível para download no minio e no console.