# Aprenda+

Site demonstrativo de apoio à alfabetização, feito com HTML, CSS e JavaScript.

## Estrutura

- As páginas HTML ficam na raiz do projeto.
- `src/css/` contém os estilos.
- `src/js/` contém a lógica da interface, cadastro, login, jogos e ranking.
- `assets/images/` contém a logo e os brasões.

## Abrir no VS Code

Abra esta pasta no VS Code. Para testar cadastro, login e ranking, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Depois, abra `http://localhost:8000` no navegador. Use o servidor local para que as páginas compartilhem os dados salvos no navegador.

## Observação

Os cadastros, senhas e pontuações deste protótipo ficam apenas no navegador e dispositivo em que foram criados. Não há servidor nem sincronização entre dispositivos.
