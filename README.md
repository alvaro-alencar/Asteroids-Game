# Asteroids-Game

Vortex Asteroids 🚀

Este projeto é uma implementação moderna do clássico jogo de arcade "Asteroids", desenvolvido inteiramente com HTML5 Canvas e JavaScript ES6, sem dependências externas.
O projeto demonstra a aplicação de conceitos fundamentais de desenvolvimento de jogos e matemática vetorial.

🎮 Como Joga

Você pode jogar a versão mais recente diretamente no seu navegador clicando no link abaixo:

👉 JOGAR AGORA

(Nota: Substitua "alvaroalencar" e "vortex-asteroids" pelo seu usuário e nome do repo corretos após criar)
Controles

| Ação | Teclado (PC) | Mobile |
|---|---|---|
| Acelerar | Seta para Cima | Botão ▲ |
| Girar | Setas Esquerda/Direita | Botões ◀ ▶ |
| Atirar | Espaço | Botão ⦿ |

🛠 Tecnologias e Conceitos Aplicados

Este software foi desenvolvido pela Vortex Development com foco em performance e código limpo.
 
 * Renderização: HTML5 Canvas API (2D Context).
 * Física: Implementação vetorial personalizada para inércia, atrito e propulsão.
 * Detecção de Colisão: Algoritmo baseado em distância euclidiana (hitbox circular).
 * Responsividade: Sistema de resize dinâmico que adapta o canvas para Desktop e Dispositivos Móveis.
 * Game Loop: Utilização de requestAnimationFrame para garantir fluidez a 60 FPS.

📂 Estrutura do Código

O projeto segue o padrão Monolithic Single File para facilitar a portabilidade e estudo:

 * Ship class: Gerencia estado, vetores de velocidade e renderização da nave.
 * Asteroid class: Gera polígonos irregulares procedurais para criar asteroides únicos a cada execução.
 * Particle System: Sistema de emissão de partículas para efeitos visuais de explosão.

Desenvolvido por Álvaro Alencar | Vortex Development
