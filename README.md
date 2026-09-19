# Modo Aula

![Status](https://img.shields.io/badge/status-prot%C3%B3tipo-yellow)
![Hackathon](https://img.shields.io/badge/HACKTUDO%202026-2%C2%BA%20lugar-brightgreen)
![Team](https://img.shields.io/badge/time-Nexus-blueviolet)
![Made with](https://img.shields.io/badge/feito%20com-HTML%20%7C%20CSS%20%7C%20JS-informational)

**🏆 2º lugar — HACKTUDO 2026**

Protótipo ao vivo: [aredesog.github.io/Hacktown](https://aredesog.github.io/Hacktown)

🎥 Pitch final ao vivo: [assista no YouTube (a partir de 42:18)](https://www.youtube.com/watch?v=4bd3hxJWSvE&t=2538s)

---

## Sumário

- [O problema](#o-problema)
- [A solução](#a-solução)
- [Foco Feed](#foco-feed)
- [Gamificação](#gamificação)
- [Pitch](#pitch)
- [Time — Nexus](#time--nexus)
- [Stack do protótipo](#stack-do-protótipo)
- [Linha do tempo — HACKTUDO 2026](#linha-do-tempo--hacktudo-2026)
- [Premiação](#premiação)

---

## O problema

O uso de smartphones em sala de aula é hoje tratado quase sempre de duas formas: proibição total (que gera resistência e não resolve o problema quando o aluno sai da escola) ou tolerância sem estrutura (que compromete o foco). Faltava uma alternativa que **medisse e recompensasse o uso consciente**, sem vigiar o conteúdo do que é acessado.

## A solução

**Modo Aula** transforma tempo de tela em crédito. O app classifica o uso do celular em quatro categorias — educacional, comunicação, entretenimento e neutro — usando as APIs nativas de tempo de tela do Android e iOS, sem nunca ler o conteúdo acessado ("medimos categorias de tempo, nunca conteúdo").

Um motor de pontos converte esse uso em créditos, e três painéis diferentes recebem o resultado:

- **Aluno**: pontos do dia, meta diária, categorias de uso, sessões ativas de atividades abertas pelo professor (ex: quiz)
- **Professor**: visão em tempo real de quem está conectado e engajado, sem precisar mudar nada na forma de dar aula — o benefício de uma turma mais focada vem mesmo que ele não use o app ativamente
- **Família**: relatório semanal do uso do filho/filha na escola

As regras de classificação (o que conta como educacional, o que conta como distração) são configuráveis pela própria escola — por exemplo, YouTube pode contar como aula em uma disciplina e como distração em outra.

### Foco Feed

Um feed de vídeos curtos publicados pelos próprios professores — sem curtidas, sem métricas sociais, sem scroll infinito (cerca de 5 vídeos por dia, "quando acaba, acabou — é de propósito"). Vídeos extras funcionam como recompensa por metas de foco atingidas.

### Gamificação

Tempo de foco vira créditos/badges resgatáveis em bonificações definidas pela escola. Identidade visual inspirada no Duolingo, cores do HACKTUDO, mascote: um tatu-bola ("se fecha para focar").

## Pitch

Apresentação final ao vivo do time Nexus no HACKTUDO 2026 (5 minutos):

▶️ [assistir no YouTube — começa em 42:18](https://www.youtube.com/watch?v=4bd3hxJWSvE&t=2538s)

## Time — Nexus

Curso de Ciência da Computação, UNIFAL-MG (Universidade Federal de Alfenas):

- Guilherme de Oliveira Aredes — [LinkedIn](https://www.linkedin.com/in/guilhermearedesg/)
- Pedro Ferreira Prado — [LinkedIn](https://www.linkedin.com/in/pedro-ferreira-prado-694251273/)

## Stack do protótipo

- HTML/CSS/JS estático, hospedado no GitHub Pages
- Navegação condicional por papel de usuário (Aluno / Professor / Família), via blocos `sc-if`
- Painel de log ("O que foi registrado") simulando eventos de interação em tempo real
- Layout responsivo: navegação horizontal no desktop, vertical (scroll para baixo) no mobile, com padding lateral simétrico

## Linha do tempo — HACKTUDO 2026

| Etapa | Data |
|---|---|
| Início do hackathon (100% online) | 11/09/2026 |
| Entrega da 1ª etapa (PDF + vídeo + protótipo) | 13/09/2026 |
| Classificação entre os 10 finalistas | 13/09/2026 |
| Mentoria de pitching | 16/09/2026 |
| [Pitch final ao vivo (5 min)](https://www.youtube.com/watch?v=4bd3hxJWSvE&t=2538s) | 19/09/2026 |
| **Resultado: 2º lugar** | 19/09/2026 |

## Premiação

Premiação total do hackathon: R$ 16.000 (1º lugar R$ 10.000, 2º lugar R$ 4.000, 3º lugar R$ 2.000).
