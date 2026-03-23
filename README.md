<<<<<<< HEAD
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
=======
# 🎨 Aprendendo Tailwind CSS

## 🚀 Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de estudar e aplicar os conceitos fundamentais do **Tailwind CSS**, explorando a criação de interfaces modernas, responsivas e eficientes utilizando classes utilitárias.

A proposta é evoluir o conhecimento em estilização front-end sem depender de CSS tradicional extenso.

---

## 🧠 Objetivos de Aprendizado
- Compreender o funcionamento do Tailwind CSS  
- Aplicar estilização diretamente no HTML  
- Criar layouts responsivos  
- Melhorar a produtividade no desenvolvimento front-end  

---

## 🛠️ Tecnologias Utilizadas
- HTML5  
- Tailwind CSS  
- Antigravity

---

## 📚 Conceitos Aplicados

### 🎯 Classes Utilitárias
Uso de classes prontas para estilização rápida:
```html
<button class="bg-blue-500 text-white px-4 py-2 rounded">
  Botão
</button>
📐 Espaçamento

Controle de margin e padding:

<div class="m-4 p-4">
  Conteúdo
</div>
🎨 Cores

Uso de paleta padrão do Tailwind:

<div class="bg-green-500 text-white">
  Exemplo
</div>
🔤 Tipografia

Estilização de textos:

<p class="text-lg font-bold text-gray-700">
  Texto estilizado
</p>
📦 Flexbox

Alinhamento de elementos:

<div class="flex justify-center items-center h-screen">
  <p>Centralizado</p>
</div>
📱 Responsividade

Design adaptável a diferentes telas:

<p class="text-sm md:text-lg lg:text-xl">
  Texto responsivo
</p>
🌟 Interações (Hover)
<button class="bg-blue-500 hover:bg-blue-700 text-white px-4 py-2">
  Hover
</button>

📁 Estrutura do Projeto
📦 aprendendo-tailwind
 ┣ 📂 src
 ┃ ┗ 📄 index.html
 ┣ 📄 README.md
 ┗ 📄 tailwind.config.js
⚙️ Como Executar o Projeto
🔹 Opção 1: CDN (rápido para testes)

Adicione no seu HTML:

<script src="https://cdn.tailwindcss.com"></script>
🔹 Opção 2: Instalação Local
npm install -D tailwindcss
npx tailwindcss init

Depois, adicione no seu CSS:

@tailwind base;
@tailwind components;
@tailwind utilities;

💡 Melhorias Futuras
 Criar layout completo (landing page)
 Implementar Grid
 Customizar tema no Tailwind
 Adicionar componentes reutilizáveis
>>>>>>> 0e55c612d0c58b6a745fda179cbfd78854ed58db
