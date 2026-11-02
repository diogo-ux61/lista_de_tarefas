# Projeto Final - Aplicativo Lista de Tarefas (Android)

Nome do Aluno: Diogo assunção da silva

Data de Entrega: 02/11/2026

## Justificativa do Tema
A escolha do tema **Lista de Tarefas (To-Do List)** visa oferecer uma ferramenta intuitiva e funcional para organização pessoal e de rotina diária. O tema foi selecionado por demonstrar claramente o fluxo de entrada de dados, armazenamento local persistente e atualização de listas em tempo real

## Descrição do Funcionamento
O aplicativo foi desenvolvido em **Kotlin** seguindo o padrão de arquitetura moderna recomendada para Android:
- Interface (UI): Desenvolvida totalmente em **Jetpack Compose**, contando com telas dedicadas para visualização de tarefas e criação/edição de itens.
- Navegação: Implementada via **Navigation Compose**, permitindo a navegação fluida entre a lista principal e a tela de formulário.
- Persistência Local: Utiliza o **Room Database** com a entidade `ToDoTask` e padrões de DAO para salvar, consultar e remover dados localmente no dispositivo.
- Arquitetura: Organizado em camadas segundo o padrão **MVVM** (Model-View-ViewModel), separando responsabilidades entre interface visual, estados e acesso a dados.
