# 📱 Projeto Mobile - Imersão Flutter Alura

Este repositório contém o projeto desenvolvido durante a **Imersão Mobile da Alura**, uma jornada prática e intensa com Flutter, realizada em abril de 2025.

Durante três aulas, criamos do zero um app completo de delivery com **interface moderna**, **gerenciamento de estado com Provider**, **navegação entre telas**, **estrutura modularizada** e **componentes reutilizáveis**.

---

## 🚀 Objetivo

Desenvolver uma aplicação mobile real com Flutter, passando pelas etapas de design, estrutura de dados, navegação e lógica de pedido. Tudo isso com boas práticas de arquitetura e foco em usabilidade.

![image](https://github.com/user-attachments/assets/fe8e4f82-04ec-4a03-96de-d7155c31e0d6)


---

## 🧠 Conhecimentos aplicados

- Estruturação de projeto Flutter
- Widgets fundamentais: `Scaffold`, `Stack`, `Column`, `Text`, `Image`, `ElevatedButton`
- Modularização e componentes reutilizáveis
- Navegação entre telas
- Leitura e exibição de dados em JSON
- Gerenciamento de estado com `Provider`
- Estilização com `AppTheme` e `AppColors`
- Badge de notificação na `AppBar`
- Tela de Checkout com totalização do pedido

---

## 🖥️ Tecnologias utilizadas

- Flutter
- Dart
- Firebase Studio (via Google IDX)
- Provider
- Figma (para o design do app)

---

## 🔎 Telas do App

- **Splash Screen**: tela inicial com a identidade visual
- **Home**: exibe categorias e lista de restaurantes
- **Detalhes do Restaurante**: mostra os pratos disponíveis e permite adicionar à sacola
- **Checkout**: tela final com a totalização do pedido e a conclusão da compra

---

## ✨ Agradecimentos

Agradecemos imensamente aos **instrutores Richart Lima** e **Giovanna Moeller** pela didática excepcional, dedicação e paciência durante todo o processo de aprendizado. Eles foram essenciais para transformar essa jornada de aprendizado em algo tão enriquecedor e divertido.

- **Richart Lima**: Instrutor na Alura, desenvolvedor de jogos educativos e criador de conteúdo com foco em Flutter e Unity.
- **Giovanna Moeller**: Desenvolvedora de Software premiada pela Apple, com experiência em Swift, Javascript/Typescript e Python.

Sem a orientação deles, não teríamos alcançado a qualidade e o sucesso deste projeto!

---

## 📂 Estrutura de pastas

```bash
lib/
├── data/
│   ├── categories_data.dart
│   └── restaurant_data.dart
├── model/
│   ├── dish.dart
│   └── restaurant.dart
├── ui/
│   ├── _core/
│   │   ├── app_colors.dart
│   │   ├── app_theme.dart
│   │   ├── bag_provider.dart
│   │   └── widgets/
│   │       ├── appbar.dart
│   ├── checkout/
│   │   └── checkout_screen.dart
│   ├── home/
│   │   └── home_screen.dart
│   ├── restaurant/
│   │   └── restaurant_screen.dart
│   └── splash/
│       └── splash_screen.dart

