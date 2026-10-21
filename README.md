# Imortal — Grêmio em dados

Dashboard responsivo sobre o Grêmio, desenvolvido em HTML, CSS e JavaScript.

**Site:** https://gianluccawb.github.io/o-imortal/

**Repositório:** https://github.com/gianluccawb/o-imortal

Publicado com GitHub Pages. Não há domínio próprio contratado para este projeto.

## Recursos

- Resultados com mandante primeiro e visitante depois, acompanhados dos respectivos escudos.
- Indicadores por temporada e competição, calendário, artilharia e elenco.
- Perfis dos atletas e última escalação disponível.
- Escudo original do Grêmio no menu e no destaque principal.
- Página de fontes e situação de atualização dos dados.

## Executar localmente

Sirva a pasta do projeto com um servidor HTTP estático. Por exemplo, com Python instalado:

```sh
python -m http.server 8000
```

Abra http://localhost:8000. O projeto não requer compilação.

## Arquivos

| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | Estrutura das páginas |
| `style.css` | Estilos e responsividade |
| `app.js` | Navegação, consultas e estatísticas |
| `gremio.png` | Escudo original fornecido pela ESPN |
| `snapshot.json` | Cópia inicial de dados, usada quando necessário |
| `bios.json` | Complemento biográfico consultado em 21/10/2026 |

## Dados e atualização

O painel consulta a ESPN ao abrir, ao voltar à aba, pelo botão de atualização e a cada cinco minutos enquanto a página está visível. A disponibilidade e a atualização dos registros dependem da fonte. O site identifica quando utiliza uma cópia salva. As biografias complementares são estáticas e têm data de consulta própria.

Fontes: [ESPN](https://www.espn.com.br/futebol/time/_/id/6273/gremio) e [Grêmio FBPA](https://gremio.net/).

Projeto independente, sem vínculo oficial com Grêmio ou ESPN. Marcas, escudos e dados de terceiros pertencem aos respectivos titulares.
