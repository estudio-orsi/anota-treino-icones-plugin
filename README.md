# Anota Treino — Ícones Material (Penpot)

Troca no lugar os 50 ícones da biblioteca "Anota Treino - Biblioteca Material 3" pelos Material Symbols Rounded (peso 400, sem preenchimento, grade de 24). Não apaga nem recria componentes: os ids continuam os mesmos, só o desenho e o nome mudam. As cópias mantêm a cor e o tamanho que tinham.

Como usar:
1. Abra o arquivo "Anota Treino - Biblioteca Material 3" no Penpot.
2. Aperte Ctrl+Alt+P e cole: https://estudio-orsi.github.io/anota-treino-icones-plugin/manifest.json
3. "Diagnóstico" (só lê) mostra quantos ícones e cópias achou. "Trocar ícones" aplica. "Baixar log" salva o .json.

O que "Trocar ícones" faz:
- Salva uma versão "Antes dos ícones Material".
- Cada ícone vira 1 caminho preenchido com o desenho Material (antes eram traços).
- Renomeia: Icon / chevron-left vira Icon / chevron_left, e assim por diante (lista no log).
- Cria 5 versões preenchidas (home_fill, fitness_center_fill, schedule_fill, group_fill, person_fill) e usa no item ativo da Navigation Bar, Rail e Drawer.
- No fim, confere tudo de novo e lista qualquer diferença no log.
Pode rodar de novo: o resultado é o mesmo.

Ícones: Material Symbols, Google, licença Apache 2.0 (github.com/google/material-design-icons).
