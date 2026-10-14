# Como configurar o seu ambiente de estudo

## 1. Baixe os materiais oficiais

No site oficial do **BSTQB**, baixe a versão em português de:

- Syllabus CTFL v4.0
- Simulados oficiais (perguntas e respostas)
- Glossário ISTQB (também disponível on-line no site do ISTQB)

Esses arquivos não estão neste repositório porque pertencem ao ISTQB e ao BSTQB.

## 2. Configure a IA

### No Claude (recomendado)

1. Crie um **Projeto** dedicado à CTFL.
2. Cole o conteúdo de [`PROMPT-TUTOR.md`](PROMPT-TUTOR.md) nas **instruções do projeto**.
3. Envie o **syllabus** e os **simulados oficiais** para os **arquivos do projeto**. Assim o tutor consulta o texto oficial em vez de depender da memória.
4. Comece uma conversa dentro do projeto, por exemplo: *"Quero treinar análise de valor limite"*.

### Em outras IAs (ChatGPT, Gemini etc.)

1. Abra uma conversa nova e cole o prompt como primeira mensagem.
2. Se a ferramenta aceitar arquivos, envie o syllabus em PDF.
3. Em conversas longas, a IA pode "esquecer" as regras: se ela começar a revelar gabaritos ou facilitar, cole o prompt de novo.

## 3. Abra o painel

Abra `dashboard/index.html` no navegador. Registre cada questão:

- com os botões **Acertei** e **Errei**;
- em lote, para simulados (**Registrar várias de uma vez**);
- ou colando as linhas `#ctfl` que a IA gera (**Colar registros gerados pela IA**).

Os dados ficam salvos no navegador. Faça backups de vez em quando (**Ver backup**) e guarde o texto num arquivo.

## 4. Use os simulados oficiais como medida

Faça o simulado oficial **cronometrado (60 minutos)** e **sem consulta**, como na prova. Depois, envie suas respostas para a IA corrigir pelo gabarito e revise **só os erros**.

## Dica de rotina

| Bloco | Tempo |
|---|---|
| Revisar as regras do caderno sem olhar, depois conferir | 10 min |
| Leitura curta de uma seção do syllabus | 10–15 min |
| Questões com o tutor, uma por vez | 30–45 min |
| Pausa longe da tela | 10 min |
| Fechamento: anotar a regra de cada erro do dia | 10–20 min |
