# projeto-integrador-cyber
Projeto para a disciplina eEDB-015/2023-2: Projeto Integrado do curso de Engenharia de Dados &amp; Big Data da PECE-Poli USP.

Grupo:
Daniel Baraldi
Tiago Marquesi
Matheus Pena

Obejtivo:
Criação de um pipeline de dados para extração, transformação e carga (ETL) da base publica A Realistic Cyber Defense Dataset (CSE-CIC-IDS2018) e treino de modelo classificador (Regressão Logistica). 

Base: https://aws.amazon.com/marketplace/pp/prodview-qkyroawpr2aw6?sr=0-60&ref_=beagle&applicationId=AWSMPContessa

Arquitetura:
![arquitetura_projeto_integrador_cyberdefense_vf](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/ed66b809-c25b-4620-8823-bdc689a35aa0)

1° Camada Raw:
S3:
![projeto-integrador-grupo-b-raw](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/42fce20c-8452-43a9-ab2d-69a6307f83d7)

Glue:
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/de5504cf-ab31-4577-b8b7-07d922bfd756)
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/103192a6-ee19-4d01-a1b1-aedc3d0c81e5)

2° Camada Trusted:
S3:
![projeto-integrador-grupo-b-trusted](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/d2f03d42-9363-47e9-9e7d-0e00abb39202)

Glue:

3° Camada Refined:
S3:
![projeto-integrador-grupo-b-refined](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/740d8122-bb4d-4a13-a285-f044c6cc6130)

Glue:


Glue:


4° Analise Exploratório:

6° Treino e Validação modelo Classificador (Regressão Logistica)

