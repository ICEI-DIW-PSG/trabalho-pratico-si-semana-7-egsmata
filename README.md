[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20883296&assignment_repo_type=AssignmentRepo)
# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Enrico Guilherme Silva da Mata
- Matricula: 902513
- Proposta de projeto escolhida: Lugares e Experiências
- Breve descrição sobre seu projeto: Breve descrição sobre seu projeto: Uma página web que exibe cidades capitais de estados do Brasil, com curiosidades e características de cada uma.

## Print da Home-Page

<<  COLOQUE A IMAGEM AQUI >>

## Print da página de detalhes do item

<<  COLOQUE A IMAGEM AQUI >>

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const capitais = [
    {
        "id": 1,
        "estado": "Acre",
        "nome": "Rio Branco",
        "anoFundacao": "1882",
        "pop": "143.000",
        "conteudo": "Rio Branco é a porta de entrada para a Amazônia e um ponto de encontro entre a natureza exuberante e o espírito acolhedor do norte."
    },
    {
        "id": 2,
        "estado": "Amazonas",
        "nome": "Manaus",
        "anoFundacao": "1669",
        "pop": "2.300.000",
        "conteudo": "Manaus, no coração da Amazônia, é a mistura perfeita de história, cultura e natureza selvagem, com a selva como cenário de sua vida urbana."
    },
    {
        "id": 3,
        "estado": "Bahia",
        "nome": "Salvador",
        "anoFundacao": "1549",
        "pop": "2.900.000",
        "conteudo": "Salvador é a cidade onde o passado e o presente se encontram, com um patrimônio cultural vibrante e um povo conhecido pela alegria contagiante."
    },
    {
        "id": 4,
        "estado": "Ceará",
        "nome": "Fortaleza",
        "anoFundacao": "1726",
        "pop": "2.800.000",
        "conteudo": "Fortaleza é a cidade do sol, com suas praias incríveis, clima quente e uma energia que nunca se apaga, sempre vibrante e cheia de vida."
    },
    {
        "id": 5,
        "estado": "Distrito Federal",
        "nome": "Brasília",
        "anoFundacao": "1960",
        "pop": "3.100.000",
        "conteudo": "Brasília, com sua arquitetura futurista e a simplicidade planejada, é o coração político do Brasil, simbolizando a modernidade e a inovação."
    },
    {
        "id": 6,
        "estado": "Goiás",
        "nome": "Goiânia",
        "anoFundacao": "1933",
        "pop": "1.600.000",
        "conteudo": "Goiânia mistura modernidade e charme, com uma natureza exuberante e uma vida cultural rica que atrai turistas e moradores com sua hospitalidade."
    },
    {
        "id": 7,
        "estado": "Minas Gerais",
        "nome": "Belo Horizonte",
        "anoFundacao": "1897",
        "pop": "2.600.000",
        "conteudo": "Belo Horizonte é uma cidade de montanhas e sabores, com uma gastronomia inesquecível e um povo apaixonado por seu estado e suas tradições."
    },
    {
        "id": 8,
        "estado": "Rio de Janeiro",
        "nome": "Rio de Janeiro",
        "anoFundacao": "1565",
        "pop": "6.700.000",
        "conteudo": "O Rio é a cidade maravilhosa que nunca dorme, com suas praias mundialmente conhecidas, o Cristo Redentor e um carnaval que é sinônimo de festa."
    },
    {
        "id": 9,
        "estado": "Santa Catarina",
        "nome": "Florianópolis",
        "anoFundacao": "1673",
        "pop": "600.000",
        "conteudo": "Florianópolis é uma das cidades mais charmosa do Brasil, com suas praias paradisíacas, rica gastronomia e cultura açoriana."
    },
    {
        "id": 10,
        "estado": "São Paulo",
        "nome": "São Paulo",
        "anoFundacao": "1554",
        "pop": "12.500.000",
        "conteudo": "São Paulo é a metrópole que nunca para, uma cidade de gigantes, onde o cosmopolitismo se mistura com uma diversidade cultural incomparável."
    }
]
```