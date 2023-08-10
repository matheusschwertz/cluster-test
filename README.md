# Lab Kubernetes com KinD

Este projeto consiste em criar e gerenciar um cluster Kubernetes local usando o KinD (Kubernetes in Docker). Ele fornece um ambiente de laboratório para testar configurações e recursos do Kubernetes.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

- Docker
- KinD

## Configuração do Cluster

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-projeto.git

```bash
2. Navegue até o diretório do projeto:
cd seu-projeto

3. Crie o cluster KinD com o nome "lab" usando o arquivo de configuração config.yaml:
kind create cluster --config config.yaml --name lab --kubeconfig config

4. Uso
Após criar o cluster, você pode interagir com ele usando o arquivo de configuração config gerado:
kubectl get pod -A --kubeconfig config          
