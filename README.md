# LUNARBIT 🌕

**Protótipo educativo 2D em pixel art sobre a gestão de uma base lunar fictícia.**

**NASA International Space Apps Challenge 2026** — desafio [Build a Junior Astronaut Mission Trainer](https://www.spaceappschallenge.org/2026/challenges/junior-astronaut-mission-trainer/).

> **Status:** demonstração / protótipo de hackathon. Este projeto não representa uma base lunar já construída nem constitui software ou procedimento operacional aprovado pela NASA.

## A ideia

LUNARBIT coloca estudantes no papel de um astronauta que explora a superfície da Lua e um habitat com três andares. A proposta é transformar sistemas espaciais interdependentes — energia, água, oxigênio, manutenção, alimentação e bem-estar — em decisões compreensíveis dentro de um jogo. A ambientação se inspira em referências da NASA, principalmente experiências da Estação Espacial Internacional, mas a arquitetura da base e as mecânicas foram adaptadas para o jogo.

## O que há neste protótipo

- **Exterior lunar:** cenário em pixel art, habitat e estruturas técnicas.
- **Microastro:** personagem com sprites de caminhada e salto.
- **Nível 1 — Operações e manutenção:** eclusa, sistemas de suporte à vida, estoque, bancada, geologia, preparação EVA e energia.
- **Nível 2 — Suporte à vida:** higiene, tratamento de água, resíduos, exercícios e cultivo experimental.
- **Nível 3 — Habitação e comando:** dormitórios, refeições, comunicações, atendimento médico e pesquisa.
- **HUD:** barras de sede, fome e sanidade, com atualização ao longo do tempo.
- **Inventário:** interface e lógica para itens como ferramentas e suprimentos.
- **Transições:** cenas de acesso ao habitat e entre andares em estágio de desenvolvimento.

**Limitações conhecidas:** o sistema de posicionamento ao retornar entre cenas/andares ainda precisa de ajustes; nem todos os equipamentos possuem interações ou missões completas. Algumas cenas experimentais em `ScenesExtras/` contêm referências a recursos ausentes do ZIP original ou ao cache do Godot. A demonstração deve ser apresentada como protótipo, não como um produto finalizado. Não há versão jogável no navegador incluída neste repositório.

## Como executar no Godot

1. Instale o [Godot Engine 4](https://godotengine.org/) — o arquivo `project.godot` foi salvo com a configuração de recursos do Godot 4.7.
2. Faça o download/clone do repositório.
3. Abra o Godot e importe a pasta que contém `project.godot`.
4. Aguarde a importação inicial dos recursos e pressione **F5**.
5. A cena principal configurada é **`res://Scenes/main.tscn`**.

O Godot recria automaticamente a pasta `.godot/` e os arquivos de importação locais excluídos do repositório.

## Organização

```text
Assets/                 # Cenários, personagens e estruturas
Scenes/                 # Exterior e interiores dos três andares
ScenesExtras/           # Experimentos e cenas auxiliares
Scripts/                # Transições e lógica de cenário
HUD_Astronautico/        # Interface de sede, fome e sanidade
LUNARBIT_Inventario/     # Inventário e ícones de itens
LUNARBIT_Global/         # Sistema global persistente
ExemplosSalto/          # Microastro e demonstrações de movimento
project.godot           # Configuração do Godot
```

## Visuais

### Exterior lunar
![Exterior lunar](Assets/Cenarios/Setor_A1/solo_lunar_a1.png)

### Nível 1 — Operações
![Nível 1](Assets/Interiores/Andar1/1%20andar.png)

### Nível 2 — Suporte à vida
![Nível 2](Assets/Interiores/Andar2/2%20andar.png)

### Nível 3 — Habitação
![Nível 3](Assets/Interiores/Andar3/3%20andar.png)

## Referências científicas

- [NASA Space Apps 2026 — desafio Junior Astronaut Mission Trainer](https://www.spaceappschallenge.org/2026/challenges/junior-astronaut-mission-trainer/)
- [NASA — Environmental Control and Life Support Systems (ECLSS)](https://www.nasa.gov/reference/environmental-control-and-life-support-systems-eclss/)
- [NASA — Quest Airlock](https://www.nasa.gov/international-space-station/quest-airlock/)
- [NASA — Moon Base Renderings](https://www.nasa.gov/gallery/moon-base-renderings/)

**Observação científica:** as tecnologias são referências educativas. Características dos equipamentos e valores de consumo usados no jogo devem ser tratados como simulações, não como especificações oficiais da NASA.

## Direitos e créditos

Este repositório contém artes e código do protótipo enviado pela equipe. Antes de redistribuir ou reutilizar os recursos fora deste projeto, confirme a autoria, a licença e as condições de uso dos arquivos e de eventuais materiais de terceiros. Não foi atribuída uma licença open source ao conjunto.

---

### English summary

**LUNARBIT** is a 2D pixel-art educational prototype for the NASA International Space Apps Challenge 2026. Students explore a fictional lunar habitat and learn how interconnected resources and operational systems affect life on the Moon. The prototype includes three interior floors, an exterior map, character animations, a survival HUD, and an inventory system. Some transitions and interactive mission mechanics are still in progress; the project is not affiliated with or endorsed by NASA.
