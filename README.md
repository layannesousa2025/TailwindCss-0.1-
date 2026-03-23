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
- Visual Studio Code  

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
