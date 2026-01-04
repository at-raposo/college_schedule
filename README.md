# COLLEGE_SCHEDULE
# 🎓 Matemática Aplicada Computacional -  Habilitação em Estatística Econômica

> Uma ferramenta web interativa para acompanhamento de progresso acadêmico no curso de Matemática Aplicada e Computacional (Habilitação em Estatística Econômica).

![Status](https://img.shields.io/badge/Status-Funcional-brightgreen)
![Language](https://img.shields.io/badge/Linguagem-HTML%2FJS-orange)
![License](https://img.shields.io/badge/Licença-MIT-blue)

## 📖 Sobre o Projeto

Este é um **Single Page Application (SPA)** leve, desenvolvido para ajudar estudantes a visualizarem seu progresso na graduação. A ferramenta permite marcar matérias concluídas, calcular automaticamente os créditos acumulados e verificar o percentual de conclusão para disciplinas Obrigatórias, Eletivas e Livres.

O sistema utiliza **LocalStorage** para persistência de dados, ou seja, suas informações ficam salvas no seu navegador e não são perdidas ao fechar a aba.

## ✨ Funcionalidades

* **📊 Monitoramento de Progresso:** Barras visuais que indicam a porcentagem de conclusão de cada categoria (Obrigatórias, Eletivas MAP, Optativas Livres).
* **💾 Salvamento Automático:** O progresso é salvo instantaneamente no navegador do usuário.
* **🔍 Busca em Tempo Real:** Filtre matérias por nome, código ou semestre.
* **🌓 Interface Moderna:** Design escuro (Dark Mode) responsivo, adaptável para Desktop e Mobile.
* **🧮 Cálculo de Créditos:** Soma automática de créditos-aula e créditos-trabalho.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web nativas, sem necessidade de frameworks pesados ou processos de build.

* **HTML5:** Estrutura semântica.
* **CSS3:** Variáveis CSS (`:root`), Flexbox e CSS Grid para layout responsivo.
* **JavaScript (Vanilla):** Lógica de manipulação do DOM e LocalStorage.

## 🚀 Como Usar

Não é necessário instalação de servidores ou dependências (npm/yarn).

1.  **Baixe o arquivo** `.html` deste repositório.
2.  Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3.  Comece a marcar as caixas de seleção das matérias que você já cursou.

## ⚙️ Configuração da Grade

A grade curricular está definida dentro do código JavaScript na constante `curriculumData`. O sistema está configurado com as seguintes metas de créditos (baseado na grade oficial):

* **Obrigatórias:** 154 créditos
* **Eletivas (MAP):** 10 créditos
* **Livres:** 44 créditos

Caso deseje alterar a grade para outro curso, basta editar o objeto `TARGETS` e o array `curriculumData` dentro da tag `<script>`.

## 📱 Responsividade

O layout possui um painel lateral de estatísticas ("Sticky") em telas grandes. Em dispositivos móveis, este painel se transforma em uma barra fixa no rodapé da tela, garantindo que o aluno possa ver seu progresso enquanto rola a lista de matérias.

## 🤝 Contribuição

Contribuições são bem-vindas! Se você quiser adicionar novas matérias, corrigir pré-requisitos ou melhorar o estilo:

1.  Faça um Fork do projeto.
2.  Crie uma Branch para sua Feature (`git checkout -b feature/NovaFeature`).
3.  Faça o Commit (`git commit -m 'Adicionando nova feature'`).
4.  Faça o Push (`git push origin feature/NovaFeature`).
5.  Abra um Pull Request.

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo para suas necessidades acadêmicas.

---
Feito com 💙 para estudantes de Exatas.
