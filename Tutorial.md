# 📖 Script de Injeção de Texto

Automatize a inserção de textos em campos de resposta de páginas web. Este script remove quebras de linha e espaços extras, deixando o texto limpo antes de preenchê-lo automaticamente em um campo de resposta.

---

## ✨ Funcionalidades

- 🧹 Remove espaços em branco duplicados.
- 📄 Remove quebras de linha desnecessárias.
- ⚡ Preenche automaticamente o campo de resposta.
- 🔄 Compatível com aplicações web que utilizam React.
- 🚀 Fácil execução diretamente pelo Console do navegador.

---

## 📦 Pré-requisitos

Antes de utilizar o script, você precisa:

- Ter acesso a uma página que possua um campo de resposta com o placeholder **"Responder"**.
- Utilizar um navegador moderno (Chrome, Edge, Firefox ou similares).
- Ter permissão para utilizar o Console do navegador.

---

## 🚀 Tutorial de Uso

### 1️⃣ Adicione seu texto

Localize a variável `textoBruto` e substitua o conteúdo entre as crases (` `) pelo texto que deseja enviar.

**Exemplo:**

```javascript
const textoBruto = `
Seu texto entra aqui!
`;
```

> 💡 Dica: Você pode colar textos com várias linhas. O script fará a limpeza automaticamente.

---

### 2️⃣ Abra o Console do Navegador

Na página onde deseja inserir o texto:

| Sistema Operacional | Atalho |
|---------------------|---------|
| Windows | `F12` ou `Ctrl + Shift + I` |
| Linux | `F12` ou `Ctrl + Shift + I` |
| macOS | `Cmd + Option + I` |

Após abrir as Ferramentas do Desenvolvedor, selecione a aba **Console**.

---

### 3️⃣ Execute o Script

1. Copie todo o código do script.
2. Cole no Console do navegador.
3. Pressione **Enter**.

> ⚠️ Alguns navegadores exibem um aviso de segurança ao colar código pela primeira vez.

Se solicitado, digite:

```text
allow pasting
```

ou

```text
permitir colar
```

e pressione **Enter**.

---

### 4️⃣ Verifique o Resultado

Se tudo ocorrer corretamente, você verá a seguinte mensagem no Console:

```text
Texto limpo e injetado!
```

O texto processado será inserido automaticamente no campo de resposta da página.

---

## 🔄 Como o Script Funciona

```text
Texto Original
      ↓
Remoção de quebras de linha
      ↓
Remoção de espaços extras
      ↓
Localização do campo de resposta
      ↓
Preenchimento automático
      ↓
Pronto ✅
```

---

## ⚠️ Avisos Importantes

- Utilize este script apenas em páginas onde você tenha autorização para interagir.
- O funcionamento depende da estrutura da página e pode deixar de funcionar caso ela seja atualizada.
- Verifique sempre o conteúdo antes de enviá-lo.
- O script foi criado para automatizar tarefas repetitivas de preenchimento de texto.

---

## 📄 Licença

Este projeto é disponibilizado para fins educacionais e de aprendizado. Sinta-se à vontade para estudar, modificar e adaptar o código às suas necessidades.

---
