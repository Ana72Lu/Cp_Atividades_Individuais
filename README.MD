# Metodologias Ágeis

Abordagens flexíveis, iterativas e incrementais para o desenvolvimento de software, que priorizam colaboração, entrega contínua, valor para o cliente e adaptação a mudanças.

## Manifesto Ágil

**Valores**

* Indivíduos e interações mais que processos e ferramentas
* Software em funcionamento mais que documentação abrangente
* Colaboração com o cliente mais que negociação de contratos
* Responder a mudanças mais que seguir um plano

**Princípios**

1. Satisfaça o Consumidor
2. Aceite bem Mudanças 
3. Entregas frequentes  
4. Trabalhe em Conjunto
5. Confie e Apoie  
6. Conversas Face a Face 
7. Softwares Funcionando 
8. Desenvolvimento Sustentável 
9. Atenção Contínua 
10. Mantenha a Simplicidade 
11. Times Auto-organizados 
12. Refletir e Ajustar

## Scrum
Framework para gerenciamento de projetos ágeis. É leve, simples de entender e difícil de adaptar.

![Framework Scrum](https://raw.githubusercontent.com/Ana72Lu/Cp_Atividades_Individuais/refs/heads/main/Framework%20Scrum.jpg)

---

# Git e GitHub

## Git

* Sistema de controle de versão distribuído (software que controla versões de arquivos); 
* Gratuito e código aberto; 
* Controla versões de arquivos para programação, como aquivos em Python e arquivos HTML, e outros tipos de documentos (ex.: DOC e XLS); 
* Repositório local.

**Principais Comandos**

| Comando | Função |
| ------- | ------ |
| `git config --global user.name "nome"` | Define o nome do usuário globalmente. |
| `git config --global user.email endereco_email` | Define o e-mail do usuário globalmente. |
| `git init` | Inicializa um novo repositório Git. |
| `git clone URL` | Clona um repositório remoto para o computador local. |
| `git status` | Mostra o estado atual dos arquivos no repositório. |
| `git log` | Exibe o histórico de commits do repositório. |
| `git log --oneline` | Exibe o histórico de commits de forma compacta. |
| `git add nome_arquivo` | Adiciona um arquivo à área de staging. |
| `git add .` ou `git add --all` | Adiciona todas as alterações à área de staging. |
| `git rm nome_arquivo` | Remove um arquivo do repositório e do diretório de trabalho. |
| `git mv nome_atual nome_novo` | Renomeia um arquivo. |
| `git commit -m "mensagem"` | Realiza um commit com uma mensagem descritiva. |
| `git branch` | Lista todas as branches no repositório. |
| `git branch nome_branch` | Cria uma nova branch. |
| `git switch nome_branch` | Alterna para outra branch. |
| `git switch -c nome_branch` | Cria e alterna para uma nova branch. |
| `git merge -m "mensagem" nome_branch` | Mescla uma branch à branch atual. |
| `git branch -d nome_bran` | Exclui uma branch. |
| `git remote add origin URL` | Adiciona um repositório remoto. |
| `git push -u origin nome_branch` | Envia os commits para um repositório remoto. |
| `git push` | Envia commits para o repositório remoto na branch atual. |
| `git pull` | Baixa e aplica atualizações do repositório remoto. |
| `git reset --hard commit_hash` | Restaura o repositório para um commit específico, perdendo alterações posteriores. |
| `git config alias.nome_atalho "comando"` | Transforma um comando em atalho apenas para o repositório atual. |
| `git config --global alias.nome_atalho` | Transforma um comando em atalho globalmente, válido para todos os repositórios do sistema. |

## GitHub

* Serviço na Cloud para projetos que utilizam Git;
* Sincronização (sync) do Git com o GitHub;
* Facilidade para colaboração, trabalho em equipe, tarefas, bugs, projetos, etc.