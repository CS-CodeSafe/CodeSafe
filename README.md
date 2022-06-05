<img src="/img/CodeSafe.jpg">

### Clone nosso projeto e execute da seguinte maneira:

```java -jar codesafe-1.0-SNAPSHOT-jar-with-dependencies```

### Você acessará o seguinte menu:

<img src="/img/main.png">

### Digite o número da opção escolhida e pressione ```enter```

## **1 - Padrão**
### Para execução com interface gráfica (GUI)

## **2 - Servidor**
### Para execução em linha de comando (CLI)
### Docker: imagem disponível em:
```docker pull allanbernardo/codesafe:v1.0```

## **3 - Completo**
### Para execução com interface gráfica (GUI) e backup local do MySQL em Docker

**Obs. 1ª execução:** Execute o **./criarSQL.sh** para configurar o MySQL em Docker
 Ele irá criar um docker ConteinerBD com a imagem MySQL e abrirá um terminal novo, cole os seguintes comandos:

```use banco1;```

```create table historico(idHistorico INT PRIMARY KEY AUTO_INCREMENT, dataHorario DATETIME, unidadeMedida VARCHAR(45), consumo FLOAT, total FLOAT, percentualConsumo INT, fkComponente INT);```

Depois saia com ```exit```

**Obs. Nª execução:** Certifique-se de que o **ConteinerBD** está rodando antes de executar a 3ª opção de execução.