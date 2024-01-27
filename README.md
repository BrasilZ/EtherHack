

Este é um cheat escrito em Java (API) e LUA (GUI) para o Projeto Zomboid. O objetivo é fornecer ao jogo funcionalidades adicionais que permitam aos usuários obter alguns benefícios. Use com responsabilidade e entenda as consequências que podem surgir como resultado do uso indevido.
O desempenho do cheat foi testado na versão mais recente do jogo `41.78.16 (Steam)` (09 de julho de 2023).


### Prerequisites

- [Java 17](https://www.oracle.com/java/technologies/downloads/) ou mais recente
- Cópia Steam do [Projeto Zomboid](https://store.steampowered.com/app/108600/Project_Zomboid/)

### Installation

1. Baixe e instale o Java no seu computador
2. Certifique-se de que o caminho para Java esteja definido em suas variáveis ​​de ambiente

(Para Windows: `WIN + X` -> `"System"` -> `"Advanced System Parameters"` -> `"Environment Variables"` -> `Double click on "Path"` -> `Insert path to java, for example "C:\Program Files\Java\jdk-20\bin"`)

3. Clone o repositório
4. Abra o projeto no IDE e construa o executável via arquivo Gradle `.jar`
5. Mova o `.jar` criado para a pasta raiz do jogo

(Exemplo `c:\Steam\steamapps\common\ProjectZomboid`)

6. Abra o console na pasta raiz e execute o seguinte comando:

```
java -jar ./EtherHack-{yourVersion}.jar --install
```

`{yourVersion}` - versão do cheat

Exemplo:
```
java -jar ./EtherHack-1.1.jar --install
```
### Uninstallation
Abra o console na pasta raiz e execute o seguinte comando:
```
java -jar ./EtherHack-{yourVersion}.jar --uninstall
```

`{yourVersion}` - Versão do cheat

Exemplo:
```
java -jar ./EtherHack-1.1.jar --uninstall
```

## Usage

Depois de instalar o cheat com sucesso, você precisa fazer login no jogo. Ao carregar, o logo do cheat aparecerá na frente do logo principal, no próprio jogo (menu e na sessão do jogo) no canto inferior esquerdo estarão informações sobre o cheat. O nome da janela do jogo também mudará.

Para abrir o menu de truques, pressione `Insert`

Para recarregar o LuaGUI, pressione `Home`, mas primeiro certifique-se de que todas as janelas de cheats estejam fechadas, caso contrário aparecerá um erro.
