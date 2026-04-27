# hello-world
Exercício GIT/Github

## 15 Exercícios Simples de Git e GitHub

### 1. Clonar repositório para pasta local
```bash
git clone https://github.com/usuario/repositorio.git projeto-local
```

### 2. Entrar na pasta do projeto
```bash
cd projeto-local
```

### 3. Verificar status do repositório
```bash
git status
```

### 4. Criar branch com seu nome
```bash
git branch aluno01
```

### 5. Criar branch hello-world
```bash
git branch hello-world
```

### 6. Listar branches existentes
```bash
git branch
```

### 7. Alternar para a branch aluno01
```bash
git switch aluno01
```

### 8. Alternar para a branch hello-world
```bash
git switch hello-world
```

### 9. Criar branches para cada aluno
```bash
git branch aluno01
git branch aluno02
git branch aluno03
```

### 10. Alternar entre branches
```bash
git switch aluno01
git switch aluno02
git switch aluno03
```

### 11. Criar arquivo para commit inicial
```bash
echo "# Meu Projeto" > README.md
```

### 12. Adicionar arquivo para commit
```bash
git add README.md
```

### 13. Fazer commit inicial
```bash
git commit -m "commit inicial"
```

### 14. Enviar branch para GitHub
```bash
git push origin aluno01
```

### 15. Fazer merge da branch
```bash
git switch main
git merge aluno01
```
