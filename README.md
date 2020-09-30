# Fargate-ECSCluster-Cloudformation
############################### GITHUB ###############################
1º Subir Tudo para o GitHub;
2º - Subir o Cloudformation/CodePipeline.yml via AWS CLI (Cloudformation);
3º - Criar Route53 na mão "domain.com" e vincular ao seu dominio público (NS); 
4º - Criar ACM "*.domain.com";
5º - Atualizar a ImageURI da ECR (Copiar), Domain e Certificado no arquivo Fargate-Cluster.yml;
6º - Subir Cloudformation/Fargate-Cluster.yml atualizado para o GitHub

git init
git add Cloudformation/Fargate-Cluster.yml
git commit -m "Atualização - ACM, IMAGE and ROUTE53"
git branch -M master
git push -u origin master 7º Veja no CodePipeline e Cloudformation as atualizações se sobem e se der erro qual é o erro.

############################ CODE COMMIT ############################

1º Crie o repositório do CodeCommit;
2º Prepare um diretório no seu PC e clone seu CodeCommit:
  git init
  git clone https://repositorio-codecommit
3ºCole no repositório clonado na sua máquina, todos os arquivos que desejas [não pode conter pastas Cloudformation/...]
4º Dê os seguintes comandos para subir esses arquivos para a nuvem:
  git init
  git add .
  git commit -m "meu primeiro commit"
  git push -u origin master