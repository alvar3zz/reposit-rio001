# reposit-rio001

echo --- Retirando Usuario GitHUB ----

git config --global --unset-all user.mail // *desconectar todos os emails*
git config --global --unset-all user.name // *desconecta todos os nomes usados no momento*

echo --- Configurando Usuario GitHUB ----

git config --global user.name "Seu Nome" // *Configurar seu nome*
git config --global user.email "seuemail@" // *Configurar seu email*

echo --- Mostrando a configuração atual do GitHUB 

git config --list // *Ver o usuário conectado no momento*

echo --- Fim ---
