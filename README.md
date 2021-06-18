# Cyclops

![Cyclops](./img/cyclops_128x128.png)

- [Cyclops](#cyclops)
  - [O que � o Cyclops?](#o-que-�-o-cyclops)
  - [Quando posso utilizar o Cyclops?](#quando-posso-utilizar-o-cyclops)
  - [Experimente R�pido](#experimente-r�pido)
  - [Texto R�pido](#texto-r�pido)
    - [Associa��o com Letras / N�meros](#associa��o-com-letras--n�meros)
    - [Observa��es](#observa��es)
      - [Associar Texto](#associar-texto)
      - [Escrever Texto](#escrever-texto)
    - [Salvar Texto com uma Chave Personalizada](#salvar-texto-com-uma-chave-personalizada)
      - [Salvar Texto com Chave Personalizada](#salvar-texto-com-chave-personalizada)
      - [Escrever Texto Associado a Chave Personalizada](#escrever-texto-associado-a-chave-personalizada)
  - [Executar Arquivos/URL](#executar-arquivosurl)
    - [Observa��es](#observa��es-1)
    - [Associar Arquivo/URL](#associar-arquivourl)
    - [Executar Arquivo/URL](#executar-arquivourl)
  - [Windows Switcher / Alternador de Janelas](#windows-switcher--alternador-de-janelas)
    - [Observa��es](#observa��es-2)
    - [Teclado N�merico | Numpad](#teclado-n�merico--numpad)
    - [Associar uma Janela](#associar-uma-janela)
    - [Ativar Janela](#ativar-janela)
  - [Outras Fun��es](#outras-fun��es)
  - [Observa��es Importantes](#observa��es-importantes)
  - [LICEN�A MIT](#licen�a-mit)

<br>

## O que � o Cyclops?

**Cyclops** � um aplicativo desenvolvido na linguagem de Script chamada [AutoHotkey](https://www.autohotkey.com) que tem por objetivo tornar o usu�rio mais eficiente ao utilizar o Sistema Operacional Windows. Especialmente desenvolvedores.

Mais r�pido que Billy the Kid utilizando o <kbd>Alt</kbd> + <kbd>Tab</kbd>, agiliza a troca direcionada entre programas abertos do Sistema.

Com mais mem�ria que um Elefante com SSD, facilita a associa��o e recupera��o de textos com atalhos em cada Letra/N�mero do teclado.

Sem precisar digitar aquele endere�o enorme da Web, e sem precisar utilizar o Menu Iniciar ou Atalhos da �rea de Trabalho. "Uff!! Cansei!". Voc� pode abrir programas ou sites com apenas um atalho.

Se voc� � afixionado por atalhos assim como eu, ent�o este aplicativo � para voc�!!!

<br>

## Quando posso utilizar o Cyclops?

- Quando voc� deseja armazenar alguma informa��o onde digitaria em formul�rios.
  - Nome
  - E-mail
  - Usu�rio
  - Matr�cula
- Para desenvolvedores: voc� pode utilizar para armazenar dados de usu�rio e senha em testes
- Para desenvolvedores: armazenar _select's_ que voc� utiliza com frequencia ("select precisa estar em apenas 1 linha")
- Para desenvolvedores: armazenar _comandos prompt_: "git log --graph --oneline"
- Quando voc� deseja alternar entre janelas do Windows, mais r�pido que o <kbd>Alt</kbd> + <kbd>Tab</kbd> sonharia ser capaz de fazer.
- Quero abrir um programa mais r�pido, com apenas um atalho, sem precisar clicar no atalho da �rea de Trabalho ou ir ao Menu Iniciar

<br>

## Experimente R�pido

1. <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>C</kbd> - Digite um texto qualquer.

2. <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>1</kbd> - Abrir o Bloco de Notas.

3. <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd> - Ser� digitado o texto que voc� associou a Letra C.

<br>

## Texto R�pido

### Associa��o com Letras / N�meros

Com esta funcionalidade voc� pode armazenar um texto, frase, palavra, n�meros ou letras, associando com uma tecla, e recuperar rapidamente esta informa��o atrav�s de atalhos.

<br>

### Observa��es

- Voc� pode utilizar todas as letras [A..Z] e n�meros [0..9] do teclado normal (n�o � o teclado num�rico).
- O aplicativo realmente digita o texto associado. Como se cada tecla fosse pressionada.
- Todos os textos armazenados s�o salvos em apenas uma linha de texto.
- N�o � poss�vel armazenar um texto que possui m�ltiplas linhas � uma �nica chave. (N�o � multilinha)

<br>

#### Associar Texto

| Atalho                                         | Descri��o                                   |
| ---------------------------------------------- | ------------------------------------------- |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>A</kbd> | Associa um texto a Letra A                  |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>B</kbd> | Associa um texto a Letra B                  |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>C</kbd> | Associa um texto a Letra C                  |
| ...                                            | Associa com cada Letra do Teclado           |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Z</kbd> | Associa um texto a Letra Z                  |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>1</kbd> | Associa um texto a Tecla 1                  |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>2</kbd> | Associa um texto a Tecla 2                  |
| ...                                            | Associa um texto com cada N�mero do Teclado |
| <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>0</kbd> | Associa um texto a Tecla 0                  |

<br>

#### Escrever Texto

| Atalho                                           | Descri��o                                         |
| ------------------------------------------------ | ------------------------------------------------- |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>A</kbd> | Escreve texto associado a Letra A                 |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> | Escreve texto associado a Letra B                 |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd> | Escreve texto associado a Letra C                 |
| ...                                              | Escreve texto associado com cada Letra do Teclado |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd> | Escreve texto associado a Letra Z                 |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>1</kbd> | Escreve texto associado a Tecla 1                 |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>2</kbd> | Escreve texto associado a Tecla 2                 |
| ...                                              | Escreve texto associado com N�mero do Teclado     |
| <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>0</kbd> | Escreve texto associado a Tecla 0                 |

<br>

### Salvar Texto com uma Chave Personalizada

Talvez voc� queira associar um Texto a uma Palavra espec�fica para seu contexto. Neste caso voc� pode armazenar uma chave personalizada.

<br>

#### Salvar Texto com Chave Personalizada

**Input:** Faz a associa��o com uma chave personalizada

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>I</kbd>

Voc� pode utilizar a palavra "Matr�cula" como **Chave** e associar o Texto "12345"

- Informando a Chave Personalizada

  ![Input Key](./img/docs/input_key.png)

- Informando o Texto que ser� associado a esta Chave

  ![Input Value](./img/docs/input_value.png)

_Matricula=12345_

<br>

#### Escrever Texto Associado a Chave Personalizada

**Output:** Escreve o texto associado a chave personalizada

Para recuperar esta informa��o voc� pode utilizar o atalho

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>O</kbd>

- Informando a Chave Personalizada

  ![Output Key](./img/docs/output_key.png)

- Ser� digitado, na Tela que estiver ativa, o texto associado a Chave

  ![Output Value](./img/docs/output_value.png)

<br>

## Executar Arquivos/URL

Com o Cyclops voc� consegue associar um arquivo [\*.exe, \*.pdf, \*.xls] ou um endere�o da web [https://google.com.br] para abrir automaticamente utilizando apenas um atalho

### Observa��es

- Para arquivos � necess�rio informar o caminho completo do arquivos
- Tamb�m funciona com o path (endere�o completo) dos atalhos na �rea de trabalho
- Para endere�o da web voc� deve informar com o "HTTPS://" na frente
- P�ginas da Internet ser�o abertas no navegador padr�o do sistema

### Associar Arquivo/URL

| Atalho                                          | Descri��o                                         |
| ----------------------------------------------- | ------------------------------------------------- |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>A</kbd> | Associa um arquivo/url a Letra A                  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>B</kbd> | Associa um arquivo/url a Letra B                  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>C</kbd> | Associa um arquivo/url a Letra C                  |
| ...                                             | Associa um arquivo/url com cada Letra do Teclado  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Z</kbd> | Associa um arquivo/url a Letra Z                  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>1</kbd> | Associa um arquivo/url a Tecla 1                  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>2</kbd> | Associa um arquivo/url a Tecla 2                  |
| ...                                             | Associa um arquivo/url com cada N�mero do Teclado |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>0</kbd> | Associa um arquivo/url a Tecla 0                  |

### Executar Arquivo/URL

| Atalho                                          | Descri��o                                                  |
| ----------------------------------------------- | ---------------------------------------------------------- |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>A</kbd> | Executa um arquivo/url associado a Letra A                 |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>B</kbd> | Executa um arquivo/url associado a Letra B                 |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>C</kbd> | Executa um arquivo/url associado a Letra C                 |
| ...                                             | Executa um arquivo/url associado com cada Letra do Teclado |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Z</kbd> | Executa um arquivo/url associado a Letra Z                 |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>1</kbd> | Executa um arquivo/url associado a Tecla 1                 |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>2</kbd> | Executa um arquivo/url associado a Tecla 2                 |
| ...                                             | Executa um arquivo/url associado com N�mero do Teclado     |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>0</kbd> | Executa um arquivo/url associado a Tecla 0                 |

<br>

## Windows Switcher / Alternador de Janelas

Voc� pode alterar rapidamente entre janelas do Windows sem utilizar o <kbd>Alt</kbd> + <kbd>Tab</kbd> e indo direto para a janela que voc� deseja, sem precisar ficar escolhendo em uma lista.

<br>

### Observa��es

- Esta funcionalidade est� habilitada apenas para o Teclado N�mero (Numpad).
- Voc� pode associar janelas do Windows aos n�meros do Teclado Num�rico de 0 a 9.
- Precisa informar o t�tulo ou parte do t�tulo da janela que voc� deseja associar.
- � case-sensitive, considera diferen�a entre ma�uscula e m�nuscula.
- Funciona com parte do T�tulo da Janela. N�o precisa ser o t�tulo completo.
- H� um atalho, em **Outras Fun��es** para copiar o t�tulo da janela ativa.

<br>

### Teclado N�merico | Numpad

![Teclado N�merico](./img/docs/numeric_keyboard.png)]

<br>

### Associar uma Janela

| Atalho                                                | Descri��o                                 |
| ----------------------------------------------------- | ----------------------------------------- |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>NUMPAD 0</kbd> | Associa uma janela do Windows ao N�mero 0 |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>NUMPAD 1</kbd> | Associa uma janela do Windows ao N�mero 1 |
| ...                                                   |                                           |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>NUMPAD 9</kbd> | Associa uma janela do Windows ao N�mero 2 |

<br>

### Ativar Janela

| Atalho                                                 | Descri��o                                               |
| ------------------------------------------------------ | ------------------------------------------------------- |
| <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>NUMPAD 0</kbd> | Ativa a janela do Windows com T�tulo associado N�mero 0 |
| <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>NUMPAD 1</kbd> | Ativa a janela do Windows com T�tulo associado N�mero 1 |
| ...                                                    |                                                         |
| <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>NUMPAD 9</kbd> | Ativa a janela do Windows com T�tulo associado N�mero 9 |

<br>

## Outras Fun��es

| Atalho                                                             | Descri��o                      |
| ------------------------------------------------------------------ | ------------------------------ |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>NUMPAD 1</kbd>             | Abre o bloco de notas          |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>1</kbd>                    | Abre o bloco de notas          |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>NUMPAD 2</kbd>             | Abre a calculadora             |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>2</kbd>                    | Abre a calculadora             |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd> | Copia o t�tulo da janela ativa |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Shift</kbd> + <kbd>W</kbd> | Ativa todas as janelas abertas |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd> | Fecha todas as janelas abertas |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>8</kbd>   | Reinicia o Sistema Operacional |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>5</kbd>   | Hiberna o Sistema Operacional  |
| <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>0</kbd>   | Desliga o Sistema Operacional  |

<br>

## Observa��es Importantes

- Todos os textos e atalhos s�o armazenados em um arquivos **.ini** criado no mesmo diret�rio do execut�vel.
- Os dados que voc� informa n�o s�o compartilhados na nuvem ou em lugar algum.
- Todos os textos e atalhos ficam somente no seu computador.

<br>

## LICEN�A MIT

Este aplicativo foi desenvolvido para facilitar meu trabalho, me tornando mais produtivo e eficiente. Espero que ele possa ser t�o �til para voc� quanto � para mim.
� totalmente gratuito e est� sob a Licen�a MIT, podendo ser utilizado e distribuido livremente.

**Enjoy It!!!**

<br>

<div>Icons made by <a href="https://www.flaticon.com/authors/smashicons" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
