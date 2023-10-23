# 🖼 Tag `<iframe>` em HTML

## ⁉ Definição:

A tag `<iframe>` é usada para incorporar conteúdo de outra fonte ou documento em uma página da web. Ela é amplamente utilizada para incluir vídeos, mapas, formulários incorporados e outros elementos interativos.

## 🔌🛒 Incorporação de Conteúdo:

- A tag `<iframe>` permite incorporar conteúdo de terceiros, como vídeos do YouTube, mapas do Google, formulários de inscrição, etc.
- Isso permite que os desenvolvedores integrem recursos externos em suas páginas da web sem a necessidade de redirecionar os usuários para outros sites.

## 🧩 Atributos Principais:

- `src`: Especifica a URL do recurso externo que você deseja incorporar na página.
- `width` e `height`: Controlam as dimensões do iframe.
- `sandbox`: Define um ambiente isolado para o conteúdo incorporado, restringindo suas ações.
- `allow`: Especifica as permissões para funcionalidades como reprodução automática de áudio/vídeo e notificações.
- `seamless`: Remove as bordas e a barra de rolagem do iframe para um visual integrado.

## 🦑 Responsividade:

- É importante criar `<iframe>`s responsivos que se ajustem ao tamanho da tela do dispositivo do usuário. Isso é frequentemente alcançado por meio de CSS ou frameworks front-end.

## ⚠✔ Boas Práticas:

- Sempre verifique a origem do conteúdo incorporado usando o atributo `src` para evitar conteúdo malicioso.
- Use a política de segurança do conteúdo (CSP) para restringir o que pode ser carregado no iframe.
- Evite o uso excessivo de `<iframe>`s, pois muitos podem prejudicar o desempenho da página.
- Considere a acessibilidade ao incorporar conteúdo, fornecendo alternativas ou descrições de texto.

## 👩‍🏫 Exemplo de Uso:

📌

```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID" width="640" height="360" allow="autoplay"></iframe>
```

📌
