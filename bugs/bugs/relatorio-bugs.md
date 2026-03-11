

# Relatório de Bugs

## BUG 01 - Sistema permite cadastro sem nome

Severidade: Alta

Passos para reproduzir:

1 - Acessar a página "Cadastrar Curso"
2 - Deixar o campo nome vazio
3 - Preencher os outros campos
4 - Clicar em salvar

Resultado atual:

O sistema permite cadastrar o curso mesmo com o campo nome vazio.

Resultado esperado:

O sistema deveria impedir o cadastro e exibir uma mensagem de validação informando que o campo nome é obrigatório.

Evidência:

/evidencias/bug01.jpeg  

---



## BUG 02 - Sistema permite cadastro sem nenhum dado inserido

Severidade: Alta

Passos para reproduzir:

1 - Acessar a página "Cadastrar Curso"
2 - Deixar todos os campos vazios
3 - Clicar em salvar

Resultado atual:

O sistema permite cadastrar curso

Resultado esperado:

O sistema deveria impedir o cadastro e exibir uma mensagem de validação informando que todos os campos são obrigatórios.

Evidência:

/evidencias/bug02.png

---

## BUG 03 - Sistema permite cadastro com texto muito longo

Severidade: Média

Passos para reproduzir:

1 - Acessar a página "Cadastrar Curso"
2 - Preencher todos os campos
3 - Preencher o campo informações com texto muito longo
4 - Clicar em salvar

Resultado atual:

O sistema permite cadastrar o curso mesmo com o texto muito grande

Resultado esperado:

Sistema deve limitar ou validar o tamanho do texto.

Evidência:

/evidencias/bug03.png

---

## BUG 04 - Sistema permite cadastro com caracteres especiais

Severidade: baixa

Passos para reproduzir:

1 - Acessar a página "Cadastrar Curso"
2 - preencher apenas com caracteres especiais
3 - Preencher os outros campos
4 - Clicar em salvar

Resultado atual:

O sistema permite cadastrar o curso apenas com caracteres especiai

Resultado esperado:

Sistema deve validar ou impedir caracteres inválidos.

Evidência:

/evidencias/bug04.png

---

## BUG 05 - Cadastro Duplicado

Severidade: Alta

Passos para reproduzir:

1 - Acessar a página "Cadastrar Curso"
2 - cadastrar dois cursos com mesmo nome
3 - Clicar em salvar

Resultado atual:

O sistema permite cadastrar o curso mesmo já existindo um outro igua6

Resultado esperado:

Sistema deveria impedir duplicidade ou alertar.

Evidência:

/evidencias/bug05.png

---

## BUG 06 - checagem de listagem sem cursos

Severidade: baixa

Passos para reproduzir:

1 - Acessar a página "Listar cursos"
2 - abrir aplicação pela primeira vez e clicar em listar cursos


Resultado atual:

página em branco

Resultado esperado:

Sistema deve mostrar mensagem como: "Nenhum curso cadastrado".

Evidência:

/evidencias/bug06.png

---

## BUG 07 - excluir curso

Severidade: alta

Passos para reproduzir:

1 - Acessar a página 
2- ecolher um curso
3- excluir um curso



Resultado atual:

mensagem de excluído, curso permanece disponível

Resultado esperado:

Sistema deve remover o curso

Evidência:

/evidencias/bug06.png

---
