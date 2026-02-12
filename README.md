# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código utilizando Git e GitHub.

Além disso, aborda:

* GitFlow
* Visual Studio Code
* Repositórios remotos
* Fluxos profissionais de trabalho

Disponível gratuitamente no YouTube.

---

# Fluxo de Trabalho — Git Local

Utilizado quando você está trabalhando apenas no seu repositório local.

```bash
git checkout -b <nova-branch>
```

2. Criar ou atualizar arquivos
3. Verificar alterações:

```bash
git status
```

4. Adicionar arquivos ao stage:

```bash
git add <arquivos>
```

5. Verificar novamente:

```bash
git status
```

6. Criar commit:

```bash
git commit -m "minha mensagem"
```

7. Voltar para a branch principal:

```bash
git checkout main
```

8. Fazer merge da branch criada:

```bash
git merge <nova-branch>
```

---

# Fluxo de Trabalho — GitHub <> Local

## Projeto próprio ou da empresa

1. Clonar o projeto:

```bash
git clone <endereco-do-projeto>
```

2. Criar nova branch:

```bash
git checkout -b <nova-branch>
```

3. Realizar alterações nos arquivos
4. Verificar alterações:

```bash
git status
```

5. Adicionar arquivos:

```bash
git add <arquivos>
```

6. Verificar novamente:

```bash
git status
```

7. Criar commit:

```bash
git commit -m "nova mensagem"
```

8. Enviar branch para o GitHub:

```bash
git push origin <nova-branch>
```

9. Abrir Pull Request no GitHub para `main`
10. Excluir branch remota após merge
11. Voltar para main:

```bash
git checkout main
```

12. Excluir branch local:

```bash
git branch -D <nova-branch>
```

---

# Fluxo de Trabalho — GitHub <> Local

## Projetos open source

1. Fazer Fork do projeto para o seu GitHub
2. Clonar o fork:

```bash
git clone <endereco-do-fork>
```

3. Criar nova branch:

```bash
git checkout -b <nova-branch>
```

4. Realizar alterações
5. Verificar alterações:

```bash
git status
```

6. Adicionar arquivos:

```bash
git add <arquivos>
```

7. Verificar novamente:

```bash
git status
```

8. Criar commit:

```bash
git commit -m "nova mensagem"
```

9. Enviar branch para seu fork:

```bash
git push origin <nova-branch>
```

10. Abrir Pull Request do seu fork para a `main` do projeto original
11. Excluir branch remota após merge
12. Voltar para main:

```bash
git checkout main
```

13. Excluir branch local:

```bash
git branch -D <nova-branch>
```

---

# Pessoas Participantes

* Igor Dammous
* Infoslack
* Leo Medeiros
* Mateus Dantas
* Nicolle de Assis
* Tales
* Téo Calvo


