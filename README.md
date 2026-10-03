# Churros Jampa — Landing page

Landing page de página única para captação de eventos (casamentos, aniversários e corporativos) em João Pessoa/PB.

## Stack
- HTML5 + Tailwind CSS (via CDN, para prototipagem)
- GSAP + ScrollTrigger (animações e micro-interações)
- Sem etapa de build: basta abrir `index.html` ou publicar a pasta em qualquer hospedagem estática

## Estrutura
```
index.html            página, estilos e scripts
assets/               fotos da Hero (desktop e mobile)
assets/eventos/       fotos do carrossel de eventos
```

## Seções
Hero com seletor de sabores e CTA dinâmico · Por que nós · Carrossel de eventos · Pacotes · Dúvidas · Instagram · Formulário de 4 etapas que abre o WhatsApp · Rodapé

## Como editar o conteúdo
Tudo fica no objeto `CONFIG`, no início do `<script type="module">` do `index.html`: WhatsApp, Instagram, horário, sabores, fotos do carrossel, pacotes e FAQ.

## Pendências antes de publicar
- Número do WhatsApp, preços dos pacotes, respostas do FAQ e horário de atendimento são **placeholders**
- As fotos do carrossel estão duplicadas apenas para demonstração
- Legendas das fotos são descritivas; trocar pelos dados reais dos eventos
- Em produção, compilar o Tailwind em vez de usar o CDN
