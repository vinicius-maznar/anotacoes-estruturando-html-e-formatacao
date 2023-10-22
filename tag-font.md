# ß🖋 Tag `<font>` em HTML (Obsoleta)

- A tag `<font>` era usada para definir o estilo de fonte, como tipo, tamanho, cor e outros atributos de texto dentro de um documento HTML.
- Ela tinha atributos como `size`, `color`, `face` e outros para controlar a formatação do texto.
- Por exemplo, `<font size="3" color="blue">Este é um texto em azul de tamanho 3</font>` aplicaria uma fonte azul e tamanho 3 a esse texto.

## 🛑 **Problemas com a tag `<font>`:**

- A tag `<font>` foi descontinuada porque a formatação de estilo deve ser separada do conteúdo em HTML. O uso excessivo dessa tag levou a código desorganizado e de difícil manutenção.
- O HTML moderno recomenda o uso de CSS (Cascading Style Sheets) para controlar a aparência e o estilo do texto em uma página da web.

## ⚠ **Recomendação para Formatação de Texto:**

- Em vez de usar a tag `<font>`, é altamente recomendável usar CSS para controlar a formatação de texto. Você pode definir estilos em um arquivo CSS externo ou diretamente no documento HTML usando a tag `<style>`.

## 👩‍🏫 **Exemplo de CSS para Formatação de Texto:**

📌

```html
<style>
  p {
    font-family: Arial, sans-serif;
    font-size: 16px;
    color: #333;
  }
</style>
```

📌
