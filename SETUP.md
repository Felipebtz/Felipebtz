# Como publicar o perfil

O perfil possui **três itens no pacote**. O README usa o GIF, que é a versão mais compatível com o GitHub:

```text
README.md
assets/
├── mobile-backend-transfer.gif
└── mobile-backend-transfer.svg
```

Se apenas o `README.md` for enviado, a imagem central ficará quebrada.

## Opção 1 — pelo PowerShell

Extraia o pacote e copie `README.md` e a pasta `assets` para a raiz do repositório `Felipebtz/Felipebtz`. Depois execute:

```powershell
git add README.md assets/mobile-backend-transfer.gif assets/mobile-backend-transfer.svg
git commit -m "feat: redesign do perfil GitHub"
git push origin main
```

## Opção 2 — pelo site do GitHub

1. Abra o repositório `Felipebtz/Felipebtz`.
2. Substitua o conteúdo do `README.md`.
3. Clique em **Add file → Upload files**.
4. Arraste a pasta `assets` completa para a área de upload.
5. Confirme se os caminhos exibidos são `assets/mobile-backend-transfer.gif` e `assets/mobile-backend-transfer.svg`.
6. Faça o commit.

## Antes de publicar

- Confirme se as métricas aproximadas podem ser divulgadas publicamente.
- A fotografia real está incorporada ao SVG. Antes do uso público, confirme o direito de uso da referência do Pinterest ou substitua por uma foto própria/licenciada.
- Não renomeie a pasta `assets` nem o arquivo `mobile-backend-transfer.gif`.
- O SVG fica no pacote como arquivo-fonte; o README exibe o GIF para evitar bloqueios de imagem e animação no GitHub.
- Verifique se `felipegitfoto.jpg` continua na raiz do repositório.
- No perfil, fixe projetos que representem mobile, backend, dados e arquitetura.

## Bio sugerida

`Engenheiro de Software | Mobile · Backend · Sistemas Distribuídos · Dados & IA`
