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
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/5e8a631e-4d46-444b-b776-45e6fa50ab6c)

3° Camada Refined:

S3:
![projeto-integrador-grupo-b-refined](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/740d8122-bb4d-4a13-a285-f044c6cc6130)

Glue:
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/0d674c30-0799-4009-8609-eaa5dd1cbbaa)


4° Analise Exploratório:

![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/0e4fbf48-9f5c-4491-b2ad-ec8aff620c0a)
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/571b0929-a08d-4a05-a1cd-fda7ce2c4559)


5° Treino e Validação modelo Classificador (Regressão Logistica):

![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/cf56158f-74a1-47af-a9ec-56cea316fc2c)
![image](https://github.com/matheusnpena/projeto-integrador-cyber/assets/60858939/47d1f68e-641c-4911-958d-9af6ac1b6893)




