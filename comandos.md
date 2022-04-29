# CRIAR CHAVE PUBLICA PARA SSH
### ssh-keygen -t ed25519 -C EMAIL
### cat nomeDoArquivo.pub

# ATIVAR AGENTE DE AUTENTICACAO DE CHAVE SSH
### eval $(ssh-agent -s)
### ssh-add id_ed25519

# COMANDOS INICIAIS
### git init
### git status

# COMANDOS COMMIT
### git add *
### git add .
### git add NOME_ARQUIVO_MODIFICADO
### git commit -m "menssagem a ser passada"

# COMANDOS PARA REPOSITORIO
### git clone ENDEREÇO_REPOSITORIO  //copia repositorio para maquina local
### git push origin REPOSITORIO

# CONFIGURAÇÕES GIT
### git config --list  //lista das configurações globais
### git config --global user.email "SEU_EMAIL" //setar email
### git config --global user.name SEU_NOME //setar usuario
### git config --global --unset user.name  //resetar config

