# hero Section Dark Mode UI com React + Tailwind CSS v4

Este projeto faz parte da minha sequência de estudos em **React** e **Tailwind CSS**.  
A aplicação é uma Hero section que demonstra a implementação de **Dark Mode** com persistência no `localStorage`, elementos de **design responsivo** e integração com **URLs de perfis gerados pela Random User Generator API**.


##  Funcionalidades

- Alternância entre Dark Mode e Light Mode 
- Interface moderna utilizando Tailwind CSS v4
- Layout 100% responsivo
- Avatares de usuários utilizando **Random User Generator API**
- Avaliação e estatísticas visuais fictícias
- Botões de ação estilizados e interativos
- Efeitos visuais com gradientes, blur e animações


## Tecnologias Utilizadas

- **React** 
- **Tailwind CSS v4**
- **Boxicons** (ícones)
- **Random User Generator API** (para URLs de perfis)
- **localStorage** (persistência de tema)


## Estrutura do Projeto

src/
├── components/
│ └── Hero.jsx # Seção principal da aplicação
├── App.jsx # Componente raiz e lógica de Dark Mode
├── index.css # Estilos globais
└── main.jsx # Ponto de entrada do React

public/
├── images/
│ ├── code-light.png # Imagem exemplo para light mode
│ └── code-dark.png # Imagem exemplo para dark mode

## Como Executar Localmente

## **Clonar o repositório**
   
git clone https://github.com/seu-usuario/nome-do-repo.git
cd nome-do-repo

Instale as dependências com:
npm install

Execute o projeto com:
npm run dev

E Abra no navegador

http://localhost:5173


## Conceitos Praticados
Uso de React Hooks (useState, useEffect)

Persistência de estado no localStorage

Responsive Design com Tailwind CSS

Consumo de URLs da Random User Generator API

Criação de componentes reutilizáveis

Estilização avançada com gradientes e blur

