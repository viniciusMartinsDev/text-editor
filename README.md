**Text-editor - Editor de Texto de Terminal em Rust**

![text-editor Logo](rust.svg)

---

**Descrição:**

Text-editor é um simples editor de texto de terminal escrito em Rust, projetado para oferecer uma experiência de edição de texto eficiente e fácil de usar, diretamente da linha de comando. Este editor é voltado para usuários que preferem trabalhar em ambientes de terminal e desejam uma ferramenta leve, rápida e personalizável para editar arquivos de texto.

---

**Instalação:**

1. Certifique-se de ter o Rust e o Cargo instalados em seu sistema. Se não estiverem instalados, siga as instruções em [rust-lang.org](https://www.rust-lang.org/learn/get-started).
2. Clone o repositório text-editor do GitHub:
   ```
   git clone https://github.com/viniciusMartinsDev/text-editor.git
   ```
3. Navegue até o diretório clonado:
   ```
   cd text-editor
   ```
4. Compile o projeto usando Cargo:
   ```
   cargo build --release
   ```
5. Após a conclusão da compilação, você encontrará o executável `text-editor` na pasta `target/release`. Adicione esse diretório ao seu PATH, se desejar usar o text-editor globalmente.

---

**Utilização:**

Para iniciar o text-editor, basta executar o comando `./text-editor` no terminal seguido do nome do arquivo que deseja editar:

```
text-editor meu_arquivo.txt
```

Após abrir o arquivo, você poderá começar a editar imediatamente. Use as teclas de atalho configuradas ou consulte a documentação para obter uma lista completa de comandos disponíveis.

---

**Licença:**

Text-editor é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.
