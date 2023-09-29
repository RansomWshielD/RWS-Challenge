# RWS #

Esse Projeto consiste no desenvolvimento de uma Solução Anti-Ransomware. Desenvolvido pela Equipe RansomWShield\
Fique a vontade para ajudar na evolução dos programas para a proteção de sistemas Windows

## Sumário
* [Descrição](#Descrição)
* [Tecnologias Utilizadas](#Tecnologia)
* [Back-end e Funcionamento](#Back-end)

## Descrição

Esse projeto consiste em um programa que cria um backup que permite ao usuário criar, gerenciar e restaurar backups das pastas do seu computador. O outro programa é responsável por proteger os arquivos do backup contra escrita de ransomwares nos arquivos, e além disso oculta os seus arquivos do diretório backup do usuário.\
\
O próximo programa foi desenvolvido com a inteção de detectar ações de ransomwares a partir de armadilha que chamamos de honeypot. Com ele é possível identificar as alterações de arquivos em que o usuário não deveria alterar, mas um ransomware com foco em criptograr todos os arquivos acaba caindo nas "traps" e alertando a ferramenta. A partir disso, a ferramenta analisa um arquivo chamado LISTA que armazena todos os novos PIDs executados do sistema windows - esse arquivo é gerado pelo programa "get-pid.exe" que é responsável por monitorar os novos PIDs gerados. Usando uma relação, se torna possivel identificar os PIDs responsáveis pelas modificações dos arquivos honeyfile do sistema, permitindo encerrar as ações do ransomware antes que prejudique mais o ambiente. \
\
Para instalar nossas ferramentas, acesse https://github.com/RansomWshielD/RWS-Challenge/tree/main/RWS-setup e leia o arquivo LEIA-ME.txt. Após isso instale os programas contidos na pasta Honeypot e Backup do link https://github.com/RansomWshielD/RWS-Challenge/tree/main/RWS-setup .\
\
Caso queria consultar nosso código fonte acesse as pastas Honeypot e Backup do link https://github.com/RansomWshielD/RWS-Challenge/. E para saber mais consulte ##Back-end e Funcionamento

## Tecnologias
* Pyhton
* Visual Studio 2022
* Visual Studio Code
* Inno Setup

## Back-end
Honeypot (dTrapRWS.py e get-pid.py)

* get-pid.py:


* dTrapRWS.py:

Backup (bckpRWS.py e seguranca-Backup.py)

* bckpRWS.py:

* seguranca-Backup.py: 
