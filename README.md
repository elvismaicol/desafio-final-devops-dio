### Olá!!! 

</br> 
 Esse repositório contém os prints da execução do desafio final do bootcamp Cloud DevOps Experience - Banco Carrefour. Demonstrando que foi desenvolvido um pipeline de CI/CD com Cloud Build e Terraform.

</br> 

<div styLe="display:inline_block" >
<img align="center" alt="GCP" src="https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white" />
</div>

</br>

1- Criado o bucket "elvisterraform" para receber os arquivos dos estados

![](img/02-bucket-criado.PNG) 

</br>
2- incluido no script o bucket "elvisterraform" e auterado o nome na instancia para "cloudbuildterraform"

![](img/01-criando-bucket.PNG) 

</br>
3- Ativado o Cloud Source Repositories

![](img/03a-source_instrucoes.PNG) 

</br>
4- Iniciando o git e seguindo seguência de comandos para efetuar o push do repositório para o Cloud Source Repositories

![](img/03-source.PNG) 

![](img/05-push.PNG) 

![](img/06-source-projeto.PNG) 

</br>
5- Criando uma trigger no Cloud Build

![](img/07-trigger.PNG) 

![](img/07-trigger-2.PNG) 

![](img/07-trigger-3.PNG) 

![](img/07-trigger-4.PNG) 

</br>
6- Trigger "desafio-devops-dio" criada

![](img/07-trigger-5.PNG) 

</br>
07- Incluindo um arquivo README.md para efetuar um novo push e iniciar a trigger desafio-devops-dio

![](img/08-teste-readme.PNG) 

</br>
08- Estatus do processo no Build history

![](img/18-build_hst.png) 

![](img/15-Build-History-ok.PNG) 

</br>
09- Instancia VM cloudbuildterraform criada

![](img/16-VM-Criada.PNG) 

</br>
10- VPC Network "terraform-network" criada

![](img/17-network.PNG) 

</br>
10- State armazenado no bucket elvisterraform

![](img/10-bucket-states.PNG) 