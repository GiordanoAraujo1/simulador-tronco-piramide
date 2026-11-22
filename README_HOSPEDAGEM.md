# Tronco de Pirâmide — Simulador 3D interativo (PT-BR)

**Site de uma página só:** `index.html` é um arquivo independente, sem bibliotecas nem conexão de internet obrigatória. A interface é em português brasileiro, com explicações para estudantes iniciantes e fórmulas acadêmicas com referências.

## Como aprender com o simulador

1. **Escolha as medidas**: ajuste as barras de baixo `b`, cima `a` e altura `h`. Todas avançam de **1 em 1** (de 0 a 100, com altura mínima 1).
2. **Agora deixe tudo gigante**: *logo abaixo*, as três barras de **potências de dez** estão sempre visíveis, uma por dimensão, de `×10⁰` a `×10¹²`. Não há botão que esconda o outro tipo de controle. As dimensões finais são `medida inicial × 10^k`; o máximo é 100 × 10¹² = 10¹⁴ unidades por dimensão.
3. Observe o **volume em tempo real** e veja o modelo 3D mudar. No celular, há uma **miniatura fixa** que continua visível enquanto você mexe nas barras.
4. Toque em experimentos rápidos (prisma, pirâmide, só altura gigante, tudo gigante).
5. Explore o laboratório de limites, as demonstrações e as fontes para aprofundar os conceitos.

**Importante:** o infinito não é uma posição literal da barra. Os controles fazem uma sequência de experimentos finitos com potências de dez; as tendências são explicadas analiticamente.

## Visualização 3D

- Arraste com o dedo ou mouse para girar em qualquer direção (inclusive de cabeça para baixo).
- Zoom com os botões **+**, **−** e **100%**, a roda do mouse, ou uma pinça com dois dedos.
- Transparência ajustável do sólido e das linhas de medida.
- Etiquetas fora da figura (padrão), arrastáveis dentro do desenho, ou ocultas.
- Botões de vista normal, de cima, de baixo e inverter 180°.
- As opções menos usadas (exibir ponta, seção, rotação automática, salvar imagem, grade, zoom detalhado) ficam sob **Mais opções de visualização**.
- Para ver a posição de uma fatia transversal, expanda **Quero ver uma fatia dentro da figura**.

## Publicar gratuitamente no GitHub Pages

1. Crie um repositório **público** no GitHub, por exemplo `simulador-piramide`.
2. Envie o arquivo `index.html` para a raiz da branch `main`.
3. Entre em **Settings → Pages → Build and deployment → Deploy from a branch**; selecione `main` e `/(root)`.
4. Após a implantação, compartilhe a URL `https://USUARIO.github.io/simulador-piramide/`.

No Android, o arquivo HTML baixado às vezes não abre corretamente a partir do gerenciador de downloads; o link HTTPS hospedado evita esse problema.

## Fórmula principal

`V = h(a² + ab + b²)/3`, onde `a` é o lado superior, `b` o inferior e `h` a altura perpendicular.

O HTML contém área lateral, área total, geratriz, aresta lateral, centroide, seção transversal, cálculo por integração, semelhança de pirâmides, teorema do prismatoide e bibliografia MathWorld e OpenStax. A figura usa escala visual normalizada para exibir números grandes.
