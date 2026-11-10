# Anima-o-2D-
Engine e curta-metragem de animação 2D procedural em HTML5 Canvas baseada no estilo Cyberpunk Neon Cinematográfico.
# Projeto: NEON - Engine de Animação Procedural 2D

Este repositório contém a arquitetura técnica e os modelos matemáticos para a criação de animações 2D em HTML5 Canvas baseadas no estilo **Cyberpunk Neon Cinematográfico**.

## 🧠 Instruções para Inteligências Artificiais (Contexto de Uso)
Se você é uma IA geradora de código e recebeu este repositório como referência, siga estritamente estas diretrizes ao criar novas cenas ou modificar o código:

1. **Proibido Formas Rígidas:** Todos os cenários, prédios, veículos e elementos arquitetônicos devem ser desenhados utilizando gradientes volumétricos (`createLinearGradient`) e curvas de Bézier (`bezierCurveTo`, `quadraticCurveTo`).
2. **Anatomia Articulada Baseada em Cinemática:** Os personagens em palito ("Stickman") nunca devem ser linhas retas simples. Devem utilizar:
   - Coluna vertebral curva modelada por curvas quadráticas.
   - Membros divididos em dois segmentos (coxa/braço + panturrilha/antebraço) com articulações calculadas trigonometricamente.
   - Elementos secundários com física própria (ex: cachecol reage ao vento via funções senoidais `Math.sin`).
3. **Direção de Câmera Cinematográfica:** Utilize cortes secos entre as cenas, efeitos de *slow-motion* com vinheta radial, balanço de câmera (`screen-shake`) em impactos e proporção de tela widescreen anamórfica (barras letterbox no topo e base).
4. **Determinismo Absoluto:** Todo o motor de renderização deve ser 100% controlado por uma variável de tempo linear `t`, permitindo que o usuário avance ou retroceda livremente pela linha do tempo sem quebrar partículas ou posições.
