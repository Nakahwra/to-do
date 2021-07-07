# Desafio 01 - Conceitos do React


## 💻 Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

## O que devo editar na aplicação?

Com o template já clonado, as depêndencias instaladas, você deve completar onde não possui código com o código para atingir os objetivos de cada teste. Nesse desafio, você deve editar apenas o seguinte arquivo para completar as funcionalidades da aplicação:

- [src/components/TaskList.tsx;](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react/blob/main/src/components/TaskList.tsx)

### components/TaskList.tsx

Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde botaremos em prática várias partes da manipulação do estado.

Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.

## Como deve ficar a aplicação ao final?

Está com dúvidas (ou curioso 👀) para ver como deve ficar a aplicação ao final do desafio? Deixamos abaixo um vídeo mostrando as principais funcionalidades que você deve implementar para te ajudar (ou matar sua curiosidade 👀). Clique na imagem para assistir.

[![Imagem demonstração](https://github.com/nakahwra/to-do/blob/main/01-reactjs-challenge.png?raw=true)](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/04e38cba-e14d-4512-a4fa-ee24152ab75f/challenge2.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210706%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210706T234541Z&X-Amz-Expires=86400&X-Amz-Signature=8e6e0e69e56691103337b4b2d37ab994a05808d45adc2da95d544683a35d0fa5&X-Amz-SignedHeaders=host)

Feito com 💜 por Rocketseat 👋 Participe da nossa [comunidade aberta](https://discord.gg/pUU3CG4Z)!

---
*<sub> Adaptação das instruções originais para fins de contextualização. </sub>*
