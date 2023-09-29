# RWS #

Solução Anti-Ransomware desenvolvido pela equipe Ransomwshield.\
Projeto em desenvolvimento...\
Fique a vontade para ajudar na construção e proteção dos softwares\

## Sumário
* [Descrição](#Descrição)
* [Como surgiu?](#Como-surgiu?)
* [Tecnologias](#Tecnologia)
* [Back-end](#Back-end)

## Descrição

Esse projeto consiste em criar um backup que permite ao cliente criar, gerenciar e restaurar backups de pastas no seu computador. Ele também oferece a opção de abrir a pasta de destino após a restauração, facilitando o acesso aos arquivos restaurados . Essa abordagem protege guarda uma cópia dos arquivos do usuário e os arquivos protege contra escrita de ransomwares nos arquivos.\
\
Outro programa desenvolvido é a detecção de ações de ransomwares. Utilizando uma abordagem de Armadilha é possível identificar alterações em arquivos onde um usuário não deveria alterar, mas um ransomware com foco em criptograr todos os arquivos acaba caindo na armadilha e alertando a ferramenta. Com isso e uma abordagem de capturar os novos PIDs iniciados no sistema é tomada a atitude de interromper o Ransomware o quanto antes para evitar um estrago maior, e eliminá-lo do sistema.\
\
Esse software é somente para sistemas Windows. Mas sua estrutura pode ser utilizada para desenvolvimentos para sistemas Linux.

## Como surgiu?

Durante um Desafio na Faculdade, 5 jovens se juntaram para desenvolver uma solução que detectasse um ransomware no sistema, com objetivo de encerrar o processo antes que faça muitos estragos.

## Tecnologias
* Tecnologias usadas
  - Inno Setup (utilizado como instalaor do software para sistemas Windows)
  - Python
  - PIP install wmi, watchdog

## Back-end
* Programas
  - Backup e Proteção

  - Armadilha
