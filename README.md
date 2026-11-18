# Calculadora PWA de Perdas Técnicas

Calculadora de perdas operacionais em HTML, CSS e JavaScript, sem bibliotecas externas. Publicada no GitHub Pages, instalável como PWA e disponível offline após o primeiro acesso.

## Metas fixas

| Equipamento | Meta por hora |
| --- | ---: |
| Esteira 01 | 2.000 |
| Esteira 02 | 4.620 |
| Termoplástica | 1.664 |
| Sorter Bulky | 5.200 |
| ASM — Linhas | 9.625 |
| ASM — Induções | 1.864 |

Perda = arredondar(meta/hora × minutos de parada × quantidade ÷ 60). Para esteiras, termoplástica e sorter bulky, quantidade = 1. Para ASM, quantidade representa linhas ou induções afetadas.

## Funcionalidades
- Quatro setores com cabeçalhos coloridos compactos em uma linha, corpo branco e perdas em vermelho
- Campos editáveis para minutos e quantidades de ASM; metas configuráveis em pop-up pelo botão **Atualizar metas** (persistidas no dispositivo)
- Setores minimizáveis com total visível e estado persistente
- Nova contagem salva o registro anterior e reinicia minutos e quantidades
- Limpar tudo zera minutos e quantidades de todos os setores com um único pop-up; preserva metas e histórico
- Relatório com cópia, compartilhamento e exportação CSV
- Dashboard com composição das perdas por setor e evolução de até oito contagens salvas
- Armazenamento local: sem sincronização automática entre dispositivos

## Exemplo de cálculo
Esteira 01: 700; Esteira 02: 1.001; Termoplástica: 55; Sorter Bulky: 433; ASM Linhas: 2.246; ASM Induções: 1.740. **Total: 6.175 pacotes.**

## Publicação
GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root).
