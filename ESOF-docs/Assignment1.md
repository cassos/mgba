```
  _____        _         _     __         _        
 |  __ \      | |       | |   /_/        (_)       
 | |__) | ___ | |  __ _ | |_  ___   _ __  _   ___  
 |  _  / / _ \| | / _` || __|/ _ \ | '__|| | / _ \ 
 | | \ \|  __/| || (_| || |_| (_) || |   | || (_) |
 |_|  \_\\___||_| \__,_| \__|\___/ |_|   |_| \___/ 
 ```
##Engenharia de Software - 2015/2016
:floppy_disk:  *Mestrado Integrado em Engenharia Informática e Computação*   :floppy_disk:

Faculdade de Engenharia da Universidade do Porto

###Team
* Carlos Samouco (up201305187@fe.up.pt)
* Carlos Soares (up201305514@fe.up.pt)
* Diogo Marques (up201305642@fe.up.pt)

###About

![](mgba-256.png)

**mGBA** is a new **Game Boy Advance** emulator written in C.

The project started in April 2013 with the goal of being fast enough to run on lower end hardware than other emulators support, without sacrificing accuracy or portability. Even in the initial version, games generally play without problems. It is loosely based on the previous GBA.js emulator, although very little of GBA.js can still be seen in mGBA.

Other goals include accurate enough emulation to provide a development environment for homebrew software, a good workflow for tool-assist runners, and a modern feature set for emulators that older emulators may not support.

mGBA is licensed under the **Mozilla Public License 2.0**.

###Processo

Sendo um emulador de uma máquina virtual, a melhor forma de avaliar os progressos no código será com base em testes unitários. Estes testes tanto podem ser escritos em código para verificar o correcto funcionamento da unidade de processamento e dos restantes periféricos (dispositivos de entrada e saída, memória, vídeo) ou carregando para a aplicaçaõ um ficheiro contendo uma cópia do software original. No caso dos emuladores, estes ficheiros contendo software designam-se por ROMs, uma vez que são obtidas por processos de dumping da memória ROM contida dentro das cassetes.

Test Driven Development (TDD) é uma técnica de desenvolvimento de software que baseia em um ciclo curto de repetições <sup>1</sup>.

Como a base do software está relativamente sólida há algum tempo, suficiente para garantir a compatibilidade com grande parte do software concebido para a *Gameboy Advance*, nos últimos meses a equipa tem-se dedicado sobretudo ao *refactoring* do código, à correcção de pequenos *bugs* específicos encontrados durante a execução dos testes, e à implementação de novas funcionalidades na interface gráfica do utilizador, como por exemplo a opção de carregar e guardar o estado da máquina virtual num ficheiro.

Além da optimização e melhoramento da estrutura do código base, a equipa está atualmente a fazer *ports* do mGBA para novas plataformas, também elas consolas de jogos (PlayStation Vita, Nintendo 3DS e Nintendo Wii).

**system testing**

###Analise Crítica


A realização de *ports* é notável para software que foi inicialmente desenhado para correr num computador e em sistemas operativos como *Windows*, *MacOS* ou *Linux*. 
e de eventuais regressões que surgiram como consequência dessas alterações no código.

###TODO:
- [x] Descrição do projeto
- [ ] Processo
- [ ] Análise critica