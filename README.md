# A Mente do Milhão — versão estática

Esta é a versão convencional da landing page, sem React, Vite, TypeScript ou servidor Node. Ela usa HTML semântico, CSS responsivo, JavaScript vanilla e Tailwind via CDN para manter compatibilidade com o design original e permitir abertura direta no navegador.

## Como abrir no Windows

Extraia esta pasta para um local do computador e dê duplo clique no arquivo `index.html`. O navegador deve abrir a página normalmente. É necessário estar conectado à internet para carregar as fontes Google e o Tailwind CDN; os assets principais da página já estão incluídos na pasta `assets`.

Se o navegador bloquear alguma interação ao abrir via `file://`, abra a página com Chrome, Edge ou Firefox atualizado. Para uma experiência local com servidor opcional, a pasta também pode ser aberta pelo VS Code com a extensão Live Server, mas isso não é obrigatório.

## Arquivos principais

| Arquivo | Função |
|---|---|
| `index.html` | Estrutura semântica, conteúdo, SEO e Open Graph |
| `styles.css` | Sistema visual, layout responsivo, microanimações e acessibilidade |
| `script.js` | Menu mobile, FAQ, scroll suave, reveal por rolagem e feedback do CTA |
| `assets/` | Capa, logo, textura e colagem editorial |

## Antes de publicar

O botão de compra ainda mostra um aviso de configuração porque o link real de checkout não foi fornecido. No `script.js`, substitua o `window.alert(...)` do elemento `[data-checkout]` pelo redirecionamento para o seu checkout. Também substitua os links de termos, privacidade, Instagram e WhatsApp pelos endereços oficiais.

A página não contém depoimentos, avaliações ou estatísticas de clientes inventadas. A prova de credibilidade utiliza somente a história e as condições presentes no conteúdo original fornecido.
