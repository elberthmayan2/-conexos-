# Projeto Conexo 

**Rede social front-end** para conectar pessoas, compartilhar ideias e criar comunidades, com foco em interatividade e ambiente acolhedor.

---

## ✨ Funcionalidades Principais

* **Feed Interativo & Notificações:** compartilhe momentos e fique por dentro das novidades.
* **Chat em Tempo Real:** converse de forma privada e segura.
* **Perfis & Busca:** crie, personalize e encontre outros usuários.
* **Comunidades & Workshops:** participe de grupos e aprenda online.
* **Salas de Chamada Temáticas:** conecte-se por voz em espaços segmentados.
* **Game Center Integrado:** relaxe e jogue diretamente na plataforma.

---

## 🧠 Como Funciona

* **Gerenciamento de Estado:** a interação é controlada via JavaScript, manipulando o DOM para uma experiência dinâmica.
* **Navegação Estática:** múltiplos arquivos HTML simulam a navegação entre seções.
* **Tecnologia:** totalmente front-end, sem frameworks complexos ou backend obrigatório.

---

## 🛠️ Tecnologias

* HTML5
* CSS3
* JavaScript (ES6+)

---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
```

2. Entre na pasta do projeto:

```bash
cd conexo-main
```

3. Abra `index.html` no navegador.

💡 **Dica:** use o **Live Server** no VS Code para recarregar a página automaticamente durante o desenvolvimento.

---

## 🗂️ Estrutura do Projeto

```
conexo-main/
├── css/
│   └── style.css
├── js/
│   ├── main.js
│   ├── chat.js
│   ├── game.js
│   └── ...
├── images/
├── music/
├── index.html
├── feed.html
├── chat.html
├── profile.html
├── game.html
└── ...
```

* **index.html:** página de login/cadastro.
* **feed.html:** conteúdo principal após login.
* **chat.html:** mensagens diretas.
* **css/style.css:** estilos principais.
* **js/**: scripts de interatividade (main, chat, game).

---

## 🕹️ Navegação & Uso

* Abra `index.html` → simule login/cadastro.
* Navegue entre seções: Feed, Chat, Comunidades, Jogo, etc.
* Interaja com cada página via os scripts JavaScript.

---

## ❓ FAQ

**Preciso de servidor?**
Não, é 100% front-end. Basta abrir os arquivos HTML.

**Os chats, posts e perfis são persistentes?**
Não. Dados são temporários e se perdem ao recarregar a página.

**Posso integrar backend?**
Sim! Estrutura pronta para Node.js, Firebase, MongoDB, etc.

---

## 📌 Roadmap (Futuro)

* Backend para persistência de dados
* Autenticação real de usuários
* Notificações push
* Upload de imagens/arquivos
* Responsividade para mobile

---

## 🤝 Como Contribuir

1. Fork do projeto
2. Crie uma branch:

```bash
git checkout -b feature/NovaFuncionalidade
```

3. Faça commit:

```bash
git commit -m "Adiciona NovaFuncionalidade"
```

4. Push para a branch:

```bash
git push origin feature/NovaFuncionalidade
```

5. Abra um Pull Request
