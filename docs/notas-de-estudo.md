# 📒 Notas de Estudo | Study Notes

## 📌 Resumo Técnico | Technical Summary

Este projeto foca na criação de uma landing page de alta performance para o Zingen, utilizando uma arquitetura moderna e escalável de CSS. A estrutura foi desenvolvida priorizando a organização modular e a experiência do utilizador através da metodologia Mobile-First.

### 🏗️ Arquitetura e Organização | Architecture and Organization
* **CSS Modular:** O código é fragmentado em arquivos específicos (```buttons.css```, ```social.css```, ```global.css```) importados via ```@import```, facilitando a manutenção e escala do projeto.
* **Design Tokens:** Uso extensivo de variáveis CSS para centralizar a gestão de cores, pesos de fonte (```--fw-bold: 800```) e escalas de espaçamento.
* **Suavização de Fontes:** Aplicação de propriedades de motor de renderização como ```-webkit-font-smoothing: antialiased``` para garantir uma tipografia nítida.

### 📱 Estratégias de Responsividade | Responsiveness Strategies
* **Mobile-First:** A estilização começa focada em dispositivos móveis, utilizando media queries para expandir e reorganizar o layout para ecrãs maiores (```80em```).
* **Container Flexível:** Implementação de um container inteligente que utiliza ```width: min(var(--max-width), 100% - padding)```, garantindo que o conteúdo nunca encoste nas bordas.
* **Even Columns:** Sistema de grid que alterna entre colunas empilhadas no mobile e colunas distribuídas igualmente no desktop via ```grid-auto-flow: column```.

### 🛠️ Ajustes de Comportamento e UI | UI & Behavior Adjustments
* **Scroll Suave:** Configuração de ```scroll-behavior: smooth``` para garantir uma navegação fluida entre as secções da página.
* **Efeitos de Hover:** Uso de ```background-clip: text``` e ```color: transparent``` para criar degradês dinâmicos nos textos e botões durante a interação.
* **Alinhamento de Rodapé:** Aplicação de ```flex-wrap: wrap``` e margens automáticas para garantir a correta distribuição dos elementos legais e sociais.

> [!NOTE]
> Estas notas são um resumo técnico. O processo detalhado com todos os desafios resolvidos está documentado nos meus arquivos pessoais de estudo.
> [Veja as anotações de estudo deste projeto aqui](https://docs.google.com/document/d/1Ra2HyndVwU3wDUuxJOL8C9kumJdMlEnVPswmuId5CX0/edit?usp=sharing)
