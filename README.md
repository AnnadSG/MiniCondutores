# MiniCondutores 🚦

Jogo educativo para crianças dos 3 aos 12 anos sobre as **regras e os sinais da estrada em Portugal**.

Baseado no Código da Estrada e no Regulamento de Sinalização do Trânsito (RST).

## Funcionalidades

- **Perfis das crianças:** nome, avatar, cor e idade. A idade desbloqueia o nível adequado.
- **5 níveis:** Pequeno Peão, Explorador, Ciclista Júnior, Condutor Júnior e Mestre da Estrada, cada um com o seu diploma.
- **Minijogos:**
  - Semáforo mágico
  - Jogo da memória
  - Constrói o sinal
  - Detetive da estrada
  - Aventura de bicicleta
  - Conduz pela cidade
  - Quem passa primeiro?
  - Desafio relâmpago
  - Grande exame
- **Recompensas:** estrelas, moedas, caderneta com 36 cromos e garagem de veículos.
- **Biblioteca com 29 sinais portugueses**, com narração por voz.
- **Sons sintetizados com Web Audio**, sem ficheiros externos, e música de fundo opcional.
- **Narração em português de Portugal** (Web Speech API), quando o aparelho tem essa voz.
- **Painel parental:** mostra o progresso, os sinais a treinar e a aprendizagem adaptativa.

## Como usar

É uma página única (`index.html`), sem dependências nem instalação.
Basta abrir o ficheiro num navegador.

### Publicar com GitHub Pages

1. Envia os ficheiros para um repositório no GitHub.
2. Vai a **Settings → Pages**.
3. Em **Branch**, escolhe `main` e a pasta `/ (root)`, e depois **Save**.
4. Ao fim de um ou dois minutos, o jogo fica disponível em `https://<utilizador>.github.io/<repositorio>/`.

## Notas

- Os perfis são guardados no `localStorage` do navegador. Ficam apenas nesse aparelho e nesse navegador.
- O som começa depois do primeiro toque no ecrã, por regra dos navegadores.
- No iPhone, confirma que o botão de silêncio está desligado.
- Os desenhos dos sinais são versões simplificadas para crianças. Antes de publicar a aplicação, devem ser verificados face ao RST em vigor.
