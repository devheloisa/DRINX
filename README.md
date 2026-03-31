DRINX - Aplicativo de Gerenciamento de Eventos e Cardápio
📌 Descrição do Projeto

O DRINX é um aplicativo mobile desenvolvido para a plataforma Android com o objetivo de gerenciar eventos, cardápios e itens relacionados a bebidas. O sistema permite visualizar eventos, filtrar informações e acessar um cardápio interativo.

O projeto foi desenvolvido utilizando a linguagem Kotlin e seguindo conceitos modernos de desenvolvimento Android, como Jetpack Compose para construção de interfaces.

🎯 Objetivo

O objetivo principal do projeto é oferecer uma solução prática para:

Gerenciamento de eventos
Visualização e organização de cardápios
Interação com listas de itens (bebidas e equipamentos)
Aplicação de filtros para melhor navegação

🛠️ Tecnologias Utilizadas
Kotlin
Android Studio
Jetpack Compose
Arquitetura MVVM (Model-View-ViewModel)

📂 Estrutura do Projeto
O projeto está organizado em pacotes, seguindo boas práticas de desenvolvimento:

🔹 Telas principais
LoginScreen – Tela de autenticação do usuário
MainActivity – Atividade principal do aplicativo
MainNavigation – Controle de navegação entre telas

🔹 Módulo de Eventos
ListaEventosScreen – Exibição de eventos
FiltroScreens – Filtros por data e status
MenuEventosScreen – Menu de navegação de eventos
EventoViewModel – Gerenciamento dos dados dos eventos

🔹 Módulo de Cardápio
CardapioScreen – Exibição do cardápio
DrinkItem – Representação de bebidas
IngredienteDrink – Ingredientes dos drinks

🔹 Módulo de Equipamentos
GrupoEquipamento
ItemGrupoEquip
GrupoEquipamentoScreen – Tela de exibição dos equipamentos

⚙️ Funcionalidades
✅ Login de usuário
✅ Navegação entre telas
✅ Listagem de eventos
✅ Filtro de eventos por critérios (data/status)
✅ Visualização de cardápio
✅ Organização de bebidas e ingredientes
✅ Exibição de grupos de equipamentos

🧠 Arquitetura

O projeto segue o padrão MVVM (Model-View-ViewModel):

Model: Representação dos dados (ex: DrinkItem, Evento)
View: Telas construídas com Jetpack Compose
ViewModel: Controle da lógica e estado da aplicação

▶️ Como Executar o Projeto
Abrir o projeto no Android Studio
Aguardar o download das dependências (Gradle)
Conectar um dispositivo ou iniciar um emulador
Executar o projeto (Run)
