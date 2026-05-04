# Galaxia

Simulacao 3D interativa de um buraco negro galactico feita com HTML, CSS, JavaScript e Three.js.

## Recursos

- Buraco negro com disco de acrecao animado.
- Campo de estrelas em profundidade.
- Efeito visual "Disk Echo" ao clicar no nucleo ou no botao.
- Rotacao manual com o mouse.
- Alternancia de rotacao automatica.
- Temas de cores: Inferno, Ruby, Plasma e Void.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Three.js via CDN

## Como Executar

Abra o arquivo `index.html` no navegador.

Como o projeto usa importacao ES Module via CDN, se o navegador bloquear o carregamento local, execute um servidor simples dentro da pasta do projeto:

```bash
python3 -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Estrutura

```text
.
├── index.html
├── style.css
├── script.js
└── README.md
```
