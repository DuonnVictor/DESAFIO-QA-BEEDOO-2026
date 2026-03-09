# DESAFIO QA BEEDOO 2026

## 1. Análise da aplicação (objetivo)

A aplicação analisada tem como objetivo permitir o cadastro e a listagem de cursos. O sistema possibilita que o usuário registre cursos informando dados como nome do curso, descrição, instrutor, imagem de capa, datas de início e fim, número de vagas e tipo de curso (Online ou Presencial).

Após o cadastro, os cursos são exibidos em uma página de listagem (LISTAR CURSOS) permitindo visualizar as informações registradas e excluir cursos previamente cadastrados.

Trata-se de uma aplicação simples de gerenciamento de cursos, voltada para registrar e consultar cursos disponíveis.

---

## 2. Principais fluxos da aplicação

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

### Fluxo de cadastro de curso

1. Acessar o menu **CADASTRAR CURSO**
2. Preencher os campos obrigatórios do formulário
3. Clicar no botão **CADASTRAR CURSO**
4. O sistema registra o curso
5. O curso passa a ser exibido no menu **LISTAR CURSOS**

### Fluxo de listagem de cursos

1. Acessar o menu **LISTAR CURSOS**
2. Visualizar os cursos cadastrados
3. Conferir informações como:
   - nome
   - descrição
   - datas
   - número de vagas
   - tipo de curso
4. Possibilidade de excluir cursos cadastrados

---

## 3. Pontos críticos para teste

Durante a análise da aplicação, foram considerados críticos para teste os seguintes pontos:

- Validação dos campos obrigatórios no cadastro de cursos
- Validação de formato e consistência dos dados inseridos
- Validação das datas de início e fim do curso
- Validação do número de vagas
- Comportamento do sistema ao receber entradas inválidas ou inesperadas
- Exibição correta das informações na listagem de cursos
- Funcionamento da exclusão de cursos
- Comportamento da interface diante de textos muito longos ou caracteres especiais

Esses pontos foram considerados críticos por impactarem diretamente a integridade dos dados e a experiência do usuário.

---

## 4. Cenários e casos de teste

Com base na análise da aplicação, foram elaborados cenários e casos de teste para validar o funcionamento do módulo de cursos.

Os testes incluem:

- Fluxo principal de cadastro de curso
- Validação de campos obrigatórios
- Cenários negativos
- Testes com caracteres especiais
- Testes de limite de caracteres
- Comportamentos inesperados

Os cenários e casos de teste foram documentados na planilha abaixo:

Link da planilha de testes:  
https://docs.google.com/spreadsheets/d/1YPK1wsmXpMNX7cW_mCI0E1UmvEirhKYQzpviqsQadqA/edit?usp=sharing

---

## 5. Execução dos testes

Os cenários definidos foram executados manualmente na aplicação, registrando:

- resultado obtido
- status do teste (BUG ou OK)

---

## 6. Registro de bugs

Durante a execução dos testes foram identificados alguns comportamentos inesperados.

Os bugs encontrados foram documentados contendo:

- título do bug (Cenários)
- passos para reproduzir
- resultado atual
- resultado esperado
- severidade

Link para o relatório de bugs:  
https://drive.google.com/drive/folders/1Avmzi9ZeQTneuysoJ31LfkicVjgsZdG0?usp=sharing
