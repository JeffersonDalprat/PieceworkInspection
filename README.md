# piecework_inspection

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

---

## 🚀 Deploy automático com GitHub Actions (Flutter Web)

Este projeto está configurado com CI/CD usando GitHub Actions para fazer build e deploy automático da aplicação Flutter Web para o GitHub Pages.

### 📁 Estrutura configurada:
- `README.md` com instruções do projeto.
- `LICENSE` com a licença MIT.
- `.github/workflows/flutter-web.yml` com o pipeline de build e deploy.

### ⚙️ Como funciona:
- Toda vez que um `git push` é feito na branch `main`, o GitHub Actions executa o workflow.
- O Flutter realiza o build web (`flutter build web`).
- O conteúdo da pasta `build/web` é publicado automaticamente na branch `gh-pages`.

### 🌐 Como ativar o GitHub Pages:
1. Acesse o repositório no GitHub.
2. Vá até **Settings > Pages**.
3. Em **Source**, selecione a branch `gh-pages`.
4. Clique em **Save**.

O seu app estará disponível em:  
`https://<seu-usuario>.github.io/<nome-do-repositorio>/`

---

## ✅ Comandos úteis no terminal

```bash
git add .
git commit -m "Projeto Flutter configurado com CI/CD"
git push -u origin main
