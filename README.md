# URNA ARACI

Simulação escolar da urna eletrônica. **Não é uma eleição oficial.**

## Estrutura
- `index.html` = urna
- `resultados.html` = painel de resultados
- `api/vote.js` = registro dos votos
- `api/results.js` = leitura dos resultados
- `assets/` = fotos/logotipo

## Vercel
1. Importe esta pasta/repositório na Vercel.
2. Conecte um Redis compatível com Upstash pelo Marketplace da Vercel.
3. Configure `UPSTASH_REDIS_REST_URL` e `UPSTASH_REDIS_REST_TOKEN`.
4. Faça o deploy.
5. Compartilhe a URL da urna com os celulares.
6. Abra `/resultados.html` para acompanhar os votos.

Sem o Redis configurado, a API informa que o banco não está configurado. Isso evita fingir que votos persistentes existem em funções serverless.

## Fotos
Coloque na pasta `assets/`:
- `AnaVitoria.png`
- `JuditeSouza.png`
- `Igor.png`
- `Regio.png`
- `Tiago.png`
- `Josiana.png`
- `ARACILOGO.png`

Para Eredina e Andreia, a urna mostra `NÃO ACHADO FOTO` por padrão.

## Candidatos cadastrados
6º ano:
- 002 Ana Vitoria — Matemática
- 020 Judite Souza — Português
- 063 Eredina — História
- 010 Igor — Educação Física
- 137 Regio — Ciências
- 004 Tiago — Inglês
- 026 Andreia — Geografia
- 031 Josiana — Artes

7º, 8º e 9º estão preparados, mas ainda sem candidatos cadastrados.
