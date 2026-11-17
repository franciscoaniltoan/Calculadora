# Calculadora PWA de Perdas Técnicas

Aplicativo HTML/CSS/JavaScript sem dependências, para simular perdas por paradas operacionais nas áreas de Esteiras, Termoplástica / Sorter Bulky, ASM | Linhas e ASM | Induções.

**Cálculo:** arredondar (meta por hora × minutos de parada × quantidade / 60). Nas Esteiras e Termoplástica a quantidade é 1.

## Recursos
- Cálculo em tempo real e soma geral
- Histórico salvo no próprio navegador
- Exportação CSV e compartilhamento
- Suporte offline via service worker
- Manifesto PWA para instalação no navegador

## Publicação
Ative GitHub Pages nas configurações do repositório: **Settings → Pages → Deploy from a branch → main → /(root)**. Em seguida abra o endereço Pages gerado e instale pelo menu do navegador.

## Valores de exemplo
Esteira 01: 700; Esteira 02: 1.001; Termoplástica: 55; Sorter Bulky: 433; ASM Linhas: 2.246; ASM Induções: 1.740. **Total: 6.175 pacotes.**
