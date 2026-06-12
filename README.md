[README.md](https://github.com/user-attachments/files/28891903/README.md)
# 🎵 Meu Site de Música

## 📁 Estrutura dos arquivos

```
varrendo-a-lua/
├── index.html   ← o site
├── cover.jpg    ← SUA FOTO (coloque aqui com esse nome)
└── README.md    ← este arquivo
```

---

## 🖼️ Como trocar a foto

1. Pegue a imagem que você quer usar
2. Renomeie para `cover.jpg`
3. Coloque na mesma pasta que o `index.html`

Se quiser outro nome, abra o `index.html` e procure:
```
coverImage: "cover.jpg",
```
Troque `cover.jpg` pelo nome da sua imagem.

---

## ✏️ Como editar os textos

Abra o `index.html` num editor de texto (Bloco de Notas, VS Code, etc.)
e procure esse trecho perto do final:

```js
const CONFIG = {
  pageTitle:      "Varrendo a Lua",
  overlayListen:  "OUÇA O NOVO ÁLBUM",
  overlayAlbum:   '"COISAS DE VIVER"',
  kodakText:      "KODAK PORTRA 400",
  relatedTitle:   "Videoclipes relacionados",
  playerTrack:    "De Janeiro a Janeiro",
  playerArtist:   "Roberta Campos, Nando Reis",
  coverImage:     "cover.jpg",
  totalTime:      "3:10",
  totalSeconds:   190,
};
```

Troque os valores entre aspas pelo que você quiser. Salve o arquivo.

---

## 🌐 Como publicar no GitHub Pages (de graça)

### Passo a passo:

1. **Crie uma conta** em https://github.com (se ainda não tiver)

2. **Crie um repositório novo:**
   - Clique em `+` > `New repository`
   - Nome: qualquer um (ex: `meu-site-musica`)
   - Marque **Public**
   - Clique em `Create repository`

3. **Faça upload dos arquivos:**
   - Na página do repositório, clique em `uploading an existing file`
   - Arraste: `index.html` e `cover.jpg`
   - Clique em `Commit changes`

4. **Ative o GitHub Pages:**
   - Vá em `Settings` (engrenagem) > `Pages`
   - Em "Source", selecione `Deploy from a branch`
   - Branch: `main` / pasta: `/ (root)`
   - Clique em `Save`

5. **Aguarde ~2 minutos** e o link aparece em:
   ```
   https://SEU-USUARIO.github.io/meu-site-musica/
   ```

Esse link você pode mandar para qualquer pessoa! 🎉

---

## 💡 Dica

Se quiser trocar a **cor de fundo** (o verde-azulado), procure no CSS:
```css
background-color: #1a6b62;
```
E troque `#1a6b62` por qualquer cor hex. Use https://colorpicker.me para escolher.
