# Como inicializar um repositório
1. **Para iniciar o `Git Bash` em uma pasta:**  
    **Comando:** `Botão direito` :arrow_right: `Git Bash Here`¹ 
    > ¹ Estou usando Windows, em outros sistemas, podem possuir outras formas de entrar no Git Bash.
2. **Para iniciar um repositório:**  
    **Comando:** ``git init`` 
3. **Para verificar qual é o status de seu repositório:**  
    **Comando:** ``git status``
4. **Para adicionar o arquivo no controle de versão:**  
    **Comando:** ``git add "[NOME DO ARQUIVO COM EXTENSÃO]"``²
    > ² O nome do arquivo é obrigatório estar entre as aspas.
5. **Para adicionar vários arquivos no controle de versão:**  
    **Comando:** `git add .`
6. **Para fazer um `commit`:**  
    **Comando:** `git commit -m "Commit Inicial"`³
    > ³ O `-m` é para indicar que possui uma mensagem.
7. **Para enviar as alterações usando o Git Push**:  
    **Comando:** `git push --set-upstream origin master`
8. **Para definir onde o seu código será enviado:**  
    **Comando:** `git remote add origin [LINK]`
9. **Para verificar o histórico das versões:**  
    **Comando:** `git reflog`
10. **Para navegar entre as versões:**  
    **Comando:** `git reset --hard [ID DO COMMIT]`
11. **Para criar uma Branche:**  
    **Comando:** `git branch estavel`
12. **Para ver todas as Branches:**  
    **Comando:** `git branch`
13. **Para mudar de Branch:**  
    **Comando:** `git checkout estavel`
14. **Para atualizar a Branch principal:**  
    **Comando:** `git merge estavel`
15. **Para puxar as atualizações de código:**  
    **Comando:** `git pull`
