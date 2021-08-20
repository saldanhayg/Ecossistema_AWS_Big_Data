#  Projeto - Criando seu Ecossistema de Big Data na Nuvem

<h1>
   <img src="https://i.ibb.co/yBWWYDd/Criando-seu-Ecossistema-de-Big-Data-na-Nuvem.jpg" alt="Criando-seu-Ecossistema-de-Big-Data-na-Nuvem" border="0">
</h1>
<br>

Repositório de cógido do Dio Live Coding com AWS EMR e Python
<h2>
   <img src="https://i.ibb.co/KGCYx0h/1.png" alt="1" border="0">
</h2>
<br>
<h2>
   <img src="https://i.ibb.co/rxfWbJg/4.png" alt="4" border="0">  
</h2>
<br>
<h2>
  <img src="https://i.ibb.co/X41pY79/5.png" alt="5" border="0">
</h2>

## Pratica

<h2>
   <img src="https://i.ibb.co/RvqfMYj/3.png" alt="3" border="0">  
</h2>
<br>

## Passo a Passo 
* Acessar S3: https://s3.console.aws.amazon.com/s3/ 
  * Criar estrutura de data lake : _dio-datalake
  * Criar estrutura de pastas
    * _data_
    * _output_
    * _temp_
* Acessar EMR: https://console.aws.amazon.com/elasticmapreduce/
    * O cluster será criado pelo MrJob e não pelo console
    * Infraestrutura como código   
* Criar chave SSH
    * Acessar  Console do EC2: https://console.aws.amazon.com/ec2/ -> Key Pairs -> Create Key Pair	
    * Download .pem file
* Obter Id e chave secreta AWS para configurar MrJob
   * Profile
   * My Security Credentials: https://console.aws.amazon.com/iam/home?region={region}#/security_credentials
   * Access Keys - Create new access key
   * Fazer download - única chance de visualizar
* Ambiente linux
   * Criar ambiente virtual python: _virtualenv --python=python3.6 venv_diolive_
   * Acessar com o vs code
* Instalar vscode no Ubuntu
   *  code .
* Criar algoritmo de análise de palavras
   * dio-wordcount.py
   * map-reduce-count : contar
   * Instalar boto3: _pip install boto3_
   * Instalar mrjob: _pip install mrjob_
* Acessar S3
   * Upload de arquivo para o bucket
* Ambiente virtual python: source venv_teste/bin/activate
  * _nano ~/.mrjob.conf_
  * _python3 dio-wordcount.py -r emr s3://{your_s3_bucket_name}/data/SherlockHolmes.txt --output-dir=s3://{your_s3_bucket_name}/output/logs1 --cloud-tmp-dir=s3://{your_s3_bucket_name}/temp/_


## Me siga nas redes sociais

🧑🏼‍💻👩🏼‍💻 https://linktr.ee/ygtecnologia 
<br>
<br> 
Investir em conhecimento rende sempre os melhores juros. Benjamim Franklin
<br>
<br> 
🙏 Oração ! Foco ! Ação ! Yeshua Hamashia