# **Desafio semi-final - Hiring Coders #3**  

Maria tem uma loja e quer implementar um modelo de recompensa. A cada R$1,00 gasto deve gerar 1 ponto de recompensa. Todo consumidor precisa saber quantos pontos tem em sua carteira virtual, logo um contador deve estar visível para validação do saldo. Maria não está preocupada com o uso dos pontos após a geração, pois ela já possui um sistema no qual o usuário final pode utilizar os pontos gerados, mas esse sistema demanda uma API para consultar o saldo e outra para debitar um valor.

[Desafio em pdf]([Chocolatey](https://chocolatey.org/install))

## Pré-requisitos  

[VTEX IO & VTEX Toolbelt](https://cdn.allbound.com/vtex-ab/2021/11/26210724/Inicializando-VTEX-IO-VTEX-Toolbelt-101-1.pdf)

## Configuração de ambiente de desenvolvimento
  
**Para ajudar na instalacão dos programas vamos usar o [Chocolatey](https://chocolatey.org/install)**

Execute no powershell como administrador o seguinte comando para instalar o chocolatey  

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`  

Após esse comando você pode usar o comando *choco install* para instalar programas.  

### **Git**  

Execute o comando abaixo para instalar o cliente do git  

`choco install git -y`  

### **Node**

Para facilitar o desenvolvimento, utilizaremos o NVM que instala o node na versão selecionada.  

#### Instalar **[NVM](https://nodejs.org/en/download/package-manager/#nvm)**  

O windows tem uma versao de nvm  
`choco install nvm -y`  
 **Importante:**
O comando a seguir serve para dizer para o terminal que um novo programa foi instalado no windows , a outra alternativa seria abrir e fechar o terminal.  
`./RefreshEnv.cmd`  

#### Instalar nodejs 16  

`nvm install 16`  

Listar a versão do node que o nvm instalou:  

`nvm list`

Em seguida selecionar o nodejs instalado.  
`nvm use 16.16.0`  

### **YARN**

Instalação do [YARN](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)  

`npm install --global yarn`  

### **VTEX CLI**

Instalar o VTEX CLI no Windows -  [download](https://vtex.io/vtexcli/install/win-x64)

