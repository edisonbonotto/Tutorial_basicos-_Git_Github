<!DOCTYPE html>
<html>

<body>

<h2> Tutorial com comandos básicos para usar Git / Github </h2>

<h3>GIT</h3>

1) No gerenciador de arquivos, botão direito e Git Bash Here
2) Git Bash, digitar git init (criar um repositório Git)
3) Na primeira vez: (como é global, serve para todos os repositórios):
    * git config --global user.email "edisonbonotto@gmail.com"
    * git config -- global user.name "edisonbonotto"
4) git add * (adicionar os arquivos incluidos, modificados, etc ao repositório)
5) git commit (salvar as alterações)

<h3>GITHUB</h3>
  
1) Criar repositório no github (https://github.com/edisonbonotto)
2) git remote add origin git@github.com:edisonbonotto/<nome_do_repositório>.git (No git bash, associar os repositórios )
3) git branch -M main
4) git push -u origin main (faz o upload para o servidor remoto)

<h3>Resolver conflitos - Codigo alterado no github e no git (como fazer?)</h3>

1) git commit -m (resolve conflitos)
2) git pull origin main
   
<h3>Baixar repositório do Github para a máquina local (como repositório, não somente pastas)</h3>

1) No repositório git@github.com:<nome_do _dono>/<nome_do_repositório>:
   * Clica no botão verde (CODE)
   * copia o endereço do repositório
   * no Git Bash, git clone git@github.com:<nome_do _dono>/<nome_do_repositório>

</body>
</html>


