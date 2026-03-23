# Projeto Resorts - Tailwind CSS

Este projeto é uma landing page moderna para reserva de resorts, desenvolvida utilizando as melhores práticas do **Tailwind CSS**.

## 🛠️ Tecnologias Utilizadas
- **HTML5** (Semântico)
- **Tailwind CSS** (via CDN para desenvolvimento rápido)
- **Lucide Icons** (Simulados via Fontes SVG inline)

## 📐 Estrutura do Layout

O projeto foi dividido em seções modulares para facilitar a manutenção e garantir um design responsivo:

### 1. Banner Principal (Hero)
- **Fundo**: Utiliza `bg-cover` e `bg-center` para uma imagem de topo que preenche a tela.
- **Formulário**: Um formulário de busca com `bg-white/90` (transparência) e `shadow` para destaque.

### 2. Seção de Destaques
- **Flexbox**: Implementada com `flex flex-col md:flex-row`, permitindo que o conteúdo se empilhe em dispositivos móveis e fique lado a lado em desktops.
- **Espaçamento**: Uso de `gap-10` para manter um visual limpo entre texto e imagem.

### 3. Grid de Resorts (Bento Grid)
Esta é a parte tecnicamente mais avançada do layout:
- **Grid Responsivo**: `grid-cols-1 md:grid-cols-4`. No celular, as imagens ocupam a largura total. No desktop, dividem-se em 4 colunas.
- **Span de Linhas/Colunas**: O card principal utiliza `md:col-span-2 md:row-span-2`, criando um visual dinâmico estilo "Bento Grid".
- **Efeitos de Hover**: Adicionado `group` no container e `group-hover:scale-110 transition` nas imagens para um efeito de zoom premium ao passar o mouse.

### 4. Rodapé (Footer)
- **Flexbox**: `flex items-center justify-between` para separar o logo dos ícones sociais.
- **Ícones**: Implementados com **SVG inline**, garantindo que as imagens nunca quebrem e mantenham alta qualidade em qualquer resolução.

## 🚀 Como Executar
Basta abrir o arquivo `index.html` em qualquer navegador moderno. Todas as dependências (Tailwind) são carregadas via CDN.

---
*Desenvolvido como parte do aprendizado de Tailwind CSS.*
