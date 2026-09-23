# Cartola de Várzea

Recriação original, jogável no navegador, inspirada na simplicidade dos managers de futebol do início dos anos 2000. Não usa código, arte, textos ou marca do Elifoot.

## Rodar localmente

```bash
cd /home/hari/elifoot-brasil
python -m http.server 4173
```

Abra http://127.0.0.1:4173/.

## Incluído nesta primeira versão

- Brasileirão Série A 2026 com 20 clubes.
- Escolha de qualquer clube como treinador.
- Elenco gerado com posição, idade, força e moral.
- Avanço de rodadas com simulação de placar e pontuação.
- Classificação, calendário, caixa e painel de temporada.
- Salvamento no `localStorage` do navegador.
- Layout responsivo para computador e celular.
- Motor de jogo separado e testes automatizados.

A lista da Série A 2026 foi conferida em fontes públicas consultadas em 22/09/2026; dados de jogadores são fictícios para evitar depender de licenças ou de uma base externa.
