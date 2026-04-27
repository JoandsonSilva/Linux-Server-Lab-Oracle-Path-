#Linux Server Lab (Oracle Path)

## Objetivo
Criar um laboratorio Linux local para praticar fundamentos de infraestrutura, suporte técnico, monitoramento e troubleshooting, com foco em preparação para ambientes de Data Center e Oracle Cloud


---
#Ambiente utilizado
-Macbook
-UTM
-Ubuntu Server ARM64
-Terminal Linux
-Git e Github via SSH

## Etapas realizadas

-Instalação do Ubuntu Server (arm64) em máquina virtual
-Configuração inicial do sistema
-Criacao de usuario
-Ativação do OpenSSH Server
-Correcão de problema de boot apos instalacao
-Configuração de Git
-Geracão de chave SSH
-Conexão autenticada com GitHub
Publicacão do projeto no repositório remoto

---

## Problema enfrentado
Boot retornandndo para o intalador apos afinalizar a intalação, a VM voltou para a tela inicial do instalador.

##Diagnostico
O Sistema ainda estava inicializando pela midia de instalação ISO

## Solucao aaplicada
Foi acessado o Boot Manager e selecionada manualmente a opção 'Ubuntu', permitindo a inicialização

##Monitoramento básico do sistema

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

##Próximos passos

-Acesso via SSH
-Simulação de falhas
-Monitoramento

##Evidências

###Uso de CPU (top)

###Processo identificado

<<<<<<< HEAD
###Checagem de memória
=======
###Checagem de memoria
Joandson Oliveira

