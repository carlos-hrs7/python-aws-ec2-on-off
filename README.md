# python-aws-ec2-on-off
Script utilizando linguagem Python para automatizar Ligar e Desligar automaticamente instâncias EC2 na AWS

Escopo: 
AWS EC2/LAMBDA/AMAZON-EVENT-BRIDGE/IAM/CLOUDWATCH & PYTHON

1.Criar as funções Lambda de Start e Stop; 
2.Adicionar os scripts python nas funções Lambda; 
3.Criar a IAM Role copiando o contéudo do script JSON;
2.Criar agendamentos para ligar e desligar chamando as funções Lambda com o serviço do Amazon Event Bridge; 