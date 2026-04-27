#Linux Server Lab (Oracle Path)
## Objetivo
Criar um laboratorio Linux local para praticar fundamentos de infraestrutura, suporte t'ection, monitoramento e troubleshooting, com foco em preparacao para ambientes de Data Center e Oracle Cloud


---
#Ambiente utilizado
-Macbook
-UTM
-Ubuntu Server ARM64
-Terminal Linux
-Git e Github via SSH

## Etapas realizadas

-Instalação do Ubuntu Server (arm64) em maquina virtual
-Configuração inicial do sistema
-Criacao de usuario
-Ativacao do OpenSSH Server
-Correcao de problema de boot apos instalacao
-Configuracao de Git
-Geracao de chave SSH
-Conexao autenticada com GitHub
Publicacao do projeto no repositorio remoto

---

## Problema enfrentado
Boot retornandndo para o intalador apos afinalizar a intalacao, a VM voltou para a tela inicial do instalador.

##Diagnostico
O Sistema ainda estava inicializando pela midia de instalacao ISO

## Solucao aaplicada
Foi acessado o Boot Manager e selecionada manualmente a opcao 'Ubuntu', permitindo a inicializacao

##Monitoramento basico do sistema

---
##Comandos utilizados


-top
-free -m
who
is
pwd
w
last
ps aux
ps -fp PID


---
##Observações
Sistema leve  (~300MB de mem'oria em uso)
---

##Proximos passos

-Acesso via SSH
-Simulação de falhas
-Monitoramento

##Evidencias

###Uso de CPU (top)

###Processo identificado

###Checagem de memoria
