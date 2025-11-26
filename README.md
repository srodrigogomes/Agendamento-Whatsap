
# 🤖 Agendamento IA por WhatsApp - Landing Page

Uma Landing Page de alta conversão projetada para vender serviços de agendamento automático via Inteligência Artificial. O layout utiliza um design moderno em **Dark Mode** e apresenta uma simulação animada de chat para demonstrar o valor do produto instantaneamente.

 

## 🎯 Funcionalidades

  * **⚡ Carregamento Instantâneo:** Arquivo único, sem necessidade de instalação ou build.
  * **📱 Design Responsivo:** Otimizado para celulares e desktops (Mobile-First).
  * **💬 Simulação de Chat Animada:** Uma demonstração visual de como a IA conversa com o cliente, criada inteiramente com CSS e Keyframes (sem JavaScript complexo).
  * **🎨 Estilização Moderna:** Utiliza **Tailwind CSS** (via CDN) para um visual limpo, com tipografia 'Inter' e paleta de cores focada em conversão (Roxo + Verde WhatsApp).
  * **🔗 CTA Direto:** Botão de "Testar Agora" com link profundo para o WhatsApp.

## 🚀 Tecnologias Utilizadas

  * **HTML5:** Estrutura semântica.
  * **Tailwind CSS (CDN):** Framework de utilitários para estilização rápida.
  * **Ionicons:** Biblioteca de ícones para a seção de benefícios.
  * **CSS Puro:** Animações de `fade-in`, digitação (`typing-indicator`) e balões de fala.

## 📦 Como Usar

1.  Baixe o código e salve como `index.html`.
2.  Abra o arquivo diretamente no seu navegador.
3.  Para colocar no ar, basta fazer upload deste único arquivo em qualquer hospedagem estática (Netlify, Vercel, GitHub Pages ou hospedagem compartilhada).

## 🛠️ Guia de Personalização

Como o código é estático, você pode editar tudo diretamente no arquivo HTML. Aqui estão os pontos principais para alterar:

### 1\. Alterar o Número do WhatsApp (CTA)

Procure pela tag `<a>` dentro da primeira coluna e altere o número no atributo `href`:

```html
<a href="https://wa.me/5543991501148?text=gostaria%20de%20fazer%20um%20agendamento" ... >

```

### 2\. Personalizar a Simulação do Chat

Você pode mudar o diálogo para se adaptar ao nicho (ex: Barbearia, Clínica, Consultório). Procure pelos elementos com a classe `chat-bubble`:

```html
<div class="chat-bubble client-bubble delay-1">
   Olá! Tem horário para corte na sexta à tarde? </div>

<div class="chat-bubble ia-bubble delay-3">
   🤖 Olá! Claro! Tenho horários disponíveis... </div>
```

### 3\. Alterar Cores

O projeto usa Tailwind. Para mudar as cores principais:

  * **Botão Verde:** Busque por `bg-emerald-500` e troque por outra cor (ex: `bg-blue-600`).
  * **Texto Roxo:** Busque por `text-purple-400` e troque (ex: `text-yellow-400`).
  * **Balão da IA:** No bloco `<style>`, procure pela classe `.ia-bubble` e altere o `background-color`.

## 📂 Estrutura do Arquivo

O código é mantido em um único arquivo para simplicidade:

  * **`<head>`:** Importação do Tailwind, Fontes e Ícones.
  * **`<style>`:** CSS customizado para as animações do chat (que o Tailwind padrão não cobre).
  * **`<body>`:**
      * **Hero Section:** Título, Subtítulo e Botão CTA.
      * **Chat Demo:** Container branco com a animação da conversa.
      * **Features:** Grid com 3 colunas listando os benefícios.

## 📄 Licença

Este template é de código aberto. Sinta-se à vontade para usá-lo em projetos pessoais ou comerciais.

