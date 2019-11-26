# Análise de Tarefas

## 1. Introdução

<p align="justify">&emsp;&emsp;A análise de tarefas é um procedimento realizado com o objetivo de decompor uma tarefa complexa em seus componentes mais simples. Trata-se da análise de como uma tarefa é realizada, incluindo uma ou mais das informações a seguir: descrição detalhada tanto de atividades físicas como mentais, duração da tarefa, frequência da tarefa, complexidade da tarefa, condições ambientais, vestimenta e equipamentos necessários.</p>

## 2. Objetivos
### 2.1. Ver o resultado de jogos
#### 2.1.1. **Diagrama**

![Diagrama1](../../img/ver_resultado.png)

#### 2.1.2. **Especificação**

| Objetivos/operações | Problemas e recomendações |
|  :------: | :------: |
| 0. Abrir site do Lance 1 > 2| - |
| 1. Clicar em "MENU" na aba lateral 1 / 2| *feedback*: aba lateral modificada para apresentar as opções do menu<br>*problema*: as opções de "TIMES" apresentadas na aba lateral são omitidas<br>*recomendação*: apresentar as opções conforme o usuário selecionar |
| 1.1 Passar a seta em "Futebol"| *feedback*: nova aba responsiva ao *hover* do mouse aparece na tela|
| 1.2 Passar a seta em "Fut Inter"| *feedback*: nova aba responsiva ao *hover* do mouse aparece na tela |
| 2. Clicar em "Tempo Real"| *feedback*: usuário é redirecionado para uma nova aba<br>*problema*: o site abre uma nova aba no navegador para apresentar as informações dos jogos<br>*recomendação*: redirecionar o usuário sem trocar de abas |
| 3. Procurar pelo jogo desejado| - |

### 2.2 Olhar as notícias do seu time
#### 2.2.1 **Diagrama**
![Diagrama2](../../img/ver_noticia.png)

#### 2.2.2. **Especificação**

| Objetivos/operações | Problemas e recomendações |
|  :------: | :------: |
| 0. Abrir site do Lance| - |
| 0.1. Caso os brasões estejam omitidos, clicar em "TIMES"| *feedback*: as opções de brasão disponíveis aparecerão |
| 1. Clicar no brasão do time desejado na aba lateral 1 < 2| *feedback*: o site redirecionará para a página do time escolhido<br>*problema*: o *layout* do site é diferente na nova página, causando estranhamento e confusão<br>*recomendação*: manter o *layout* padronizado entre as páginas |
| 1.1 Navegar pelas notícias disponíveis| - |
| 1.2 Clicar na notícia desejada| *feedback*: o site apresentará a notícia |
| 2. Clicar em "+TIMES"| *feedback*: o site redirecionará para uma página com os times disponíveis |
| 3. Selecionar o time desejado 1 < 2| *feedback*: o site redirecionará para a página do time escolhido<br>*problema*: o *layout* do site é diferente na nova página, causando estranhamento e confusão<br>*recomendação*: manter o *layout* padronizado entre as páginas |

## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 12/10/2019 | 0.1 | Iniciando documento | Murilo Loiola |
| 12/10/2019 | 0.2 | Adição da análise 1 | Murilo Loiola |
| 13/10/2019 | 0.3 | Adição da análise 2 | Murilo Loiola |
