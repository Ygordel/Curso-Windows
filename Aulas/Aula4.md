# Aula 04 — Prompt de Comando (CMD)

**FAETEC | Professor Ygor**

## Objetivos
- Conhecer o CMD.
- Executar comandos básicos.
- Manipular arquivos e diretórios.
- Realizar diagnóstico básico do computador e da rede.

## Comandos essenciais

| Comando | Função |
|---|---|
| `DIR` | Lista arquivos e pastas |
| `CD` | Entra em uma pasta |
| `CD..` | Retorna à pasta anterior |
| `CLS` | Limpa a tela |
| `MD` | Cria uma pasta |
| `RD` | Remove uma pasta |
| `COPY` | Copia arquivos |
| `MOVE` | Move arquivos |
| `REN` | Renomeia arquivos |
| `DEL` | Exclui arquivos |
| `TREE` | Exibe estrutura de pastas |
| `TYPE` | Exibe arquivo de texto |
| `HOSTNAME` | Mostra o nome do computador |
| `IPCONFIG` | Mostra configuração IP |
| `PING` | Testa comunicação de rede |
| `SYSTEMINFO` | Mostra informações do sistema |
| `TASKMGR` | Abre o Gerenciador de Tarefas |
| `SHUTDOWN` | Desliga/reinicia o computador |
| `SFC /SCANNOW` | Verifica arquivos protegidos do sistema |

## Laboratório

Abra o CMD e execute:

```cmd
hostname
ipconfig
ping 127.0.0.1
systeminfo
taskmgr
```

### Desafio
Crie pelo CMD:

```cmd
md FAETEC
cd FAETEC
md Aula4
cd Aula4
echo Aula de Windows > atividade.txt
dir
type atividade.txt
```

Registre o resultado de cada comando.
