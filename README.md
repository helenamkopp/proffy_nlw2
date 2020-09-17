#  Proffy 

## Descrição
O Proffy foi desenvolvido juntamente com o pessoal da Rocketseat na segunda edição do evento Next Level Week. Ele é uma plataforma de professores online, onde os alunos podem pesquisar os profissionais de acordo com seus horários disponíveis e sua especialização (disciplinas) e os professores podem se cadastrar deixando seus dados disponíveis. 

A aplicação foi desenvolvida em React.js, onde temos seu front e backend, e também foi utilizado o banco de dados postgress.

## Índice
- [Requisitos](#Requisitos)
- [Instalação](#Instalação)
- [Uso](#Uso)
- [Imagens](#Imagens)
- [Erros](#Erros)


## Requisitos
- Siga os passos de instalação abaixo. 


## Instalação
- Utilizar o comando
  - No terminal, utilizar o comando: 

  ``` 
  sudo apt update && sudo apt install yarn 
  ```
Obs: Ele é responsável por instalar todas as dependências de desenvolvimento utilizadas no projeto. Elas serão responsáveis pelo seu funcionamento correto.  


## Uso
Para rodar a aplicação:
- No terminal, utilize o comando:
```
yarn start
```

## Imagens:

Veja abaixo um breve gif com o funcionamento do projeto

<p align="center">
  <img src="./images/proffy.gif" title="Página Instrutores">
</p>


## Erros
Como a aplicação ainda está em desenvolvimento e terá novas versões, é possível encontrar alguns bugs. 

Caso haja muita lentidão entre as funcionalidades, sugiro que você pare o servidor (ctrl + c) e o inicie novamente com npm start - uma nova aba abrirá.

Caso você não queira reiniciar o servidor, um ctrl + r atualizará a página e pode resolver o problema de lentidão.

Você pode acompanhar as alterações que esta fazendo no arquivo 

```
data.json
``` 
na pasta raíz, ele mostrará o array com membros e instrutores. Ali você pode ver também os perfis deletados e as edições realizadas.
