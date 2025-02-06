# **Aprofundamento-dos-sistemas-operacionais-Windows**
## _O que é_
---
Windows é um sistema operacional de multitarefas para computadores e até mesmo para dispositivos moveis, extremamente famoso, contando com mais de 1,6 bilhões de usuarios por todo mundo.
## _Como surgiu_ 
---
35 anos atrás a Microsoft, até então mais conhecida pelo sistema operacional usado no ***IBM PC*** e compatíveis, o ***MS-DOS***, lançou um produto chamado Windows. Seu objetivo era facilitar o uso do computador graças a um conceito e ferramenta revolucionários: a ***inteface gráfica e o mouse***. Em vez de memorizar e digitar comandos complexos, bastava apontar para opções na tela. 
De começo não foi um sucesso imediato, mas ao longo de vários anos e múltiplas versões o sistema foi crescendo e conquistando espaço, até dominar completamente a computação pessoal.
## _Cadeia Evolutiva_
---
### Windows 1.0, primeira versão.
 - Lançado em ___20 de novembro de 1985___, o software era uma interface gráfica (e não um sistema operacional) que, como foi dito antes, rodava sobre o MS-DOS, e não tinha um “desktop” como conhecemos hoje: o principal elemento da interface era um gerenciador de arquivos. Vinha com apps como o Paint, calculadora, agenda, editor de texto (o Write) um jogo simples, o Reversi. Era possível ver vários aplicativos na tela ao mesmo tempo, divindindo-a meio a meio como no Android, algo revolucionário na época. Os apps abertos eram representados por ícones no ___rodapé da tela___, o que lembra uma versão rudimentar da barra de tarefas do Windows 10.


### Windows 2.0, melhorias do processo.
 - Em 1987, nascia a primeira versão do Windows onde a janela de um aplicativo podia ser sobreposta às outras. Também foi nela que termos relacionados ao gerenciamento de janelas como “Minimizar” e “Maximizar” fizeram sua estréia, e que muitos comandos ganharam atalhos de teclado, já que uma das críticas ao Windows 1.0 era que ele dependia demais do mouse. O Windows 2.0 também foi a primeira versão capaz de ___tirar proveito do poder de processamento das CPUS Intel 286 e 386___, sendo que no 386 era capaz de executar múltiplos programas MS-DOS ao mesmo tempo, cada um em uma sessão “virtual” do MS-DOS.


### Windows 3.0, melhoria de qualidade.

 - Na década de 90 o Windows 3.0 apareceu e foi a primeira versão do sistema a ser um sucesso de crítica e público. Com inovações como o Gerenciador de Programas (responsável pelo desktop) e File Explorer (gerenciador de arquivos), ele estabeleceu o visual padrão do Windows pelos próximos cinco anos. Alem de que, os PCs deram os primeiros passos rumo à multimídia, com uma extensão chamada Windows 3.0 with Multimedia Extensions que adicionava suporte a gravação e reprodução de som, dispositivos MIDI e joysticks analógicos. E em 1992 lançou-se o Windows 3.1, sendo nele que surgiram as fontes TrueType, que tornaram o sistema uma opção viável para “Desktop Publishing” (DTP, diagramação digital de livros, jornais e revistas) e coisas que consideramos corriqueiras, como a capacidade de arrastar um arquivo para o ícone de um programa para que ele seja aberto.


### Windows 95, disponibilidade do entretenimento.

 - Em 1995 o mundo todo usuários fazia fila nas portas das lojas no dia do lançamento para conseguir uma cópia do software que prometia tornar os PCs ainda mais fáceis de usar. O Windows 95 prometia facilitar o upgrade do computador graças à ___tecnologia Plug & Play:___ bastava plugar uma placa de expansão (como placa de vídeo, som, modem, etc) e instalar um driver para começar a usá-la, sem ter que se preocupar em configurar IRQs e endereços de memória manualmente. Nem sempre dava certo, mas era melhor do que antes. Também foi a primeira versão do Windows “pronta para a internet” e redes em geral, com uma pilha TCP/IP integrada como parte do sistema operacional.

### Windows XP, Virada de chave.

 - No inicio do milenio (2001) o Windows finalmente se tornou um sistema operacional “de verdade”. O Windows XP não dependia mais do velho MS-DOS por debaixo dos panos e era baseado no ___Windows NT___, criado para o mundo corporativo. Com isso a Microsoft uniu os dois mercados sob um único sistema. Foi no XP que a Microsoft começou a integrar mais recursos de segurança ao sistema operacional, como a Central de Segurança do Windows XP Service Pack 2, que facilitava a configuração de recursos como o firewall do sistema e alertava caso não houvesse proteção antivírus instalada. Por fim, a interface gráfica foi renovada, ganhando mais cores e efeitos e abandonando o visual “cinzento” adotado desde o Windows 3.0. O sistema operacional ganhou mais desempenho e estabilidade e suporte a novas tecnologias como USB 2.0, Firewire 800 e ClearType, para melhorar a legibilidade das fontes nos então novos monitores LCD.

### Windows 7, Nova era.

 - O Windows 7 adicionou melhor suporte a recursos comuns a muitos dos computadores modernos, como processadores com múltiplos núcleos, unidades SSD e múltiplas placas de vídeo. Além disso, a estabilidade e o desempenho melhoraram significativamente em relação ao Windows Vista. Agora era possível prender apps à barra de tarefas, e os ícones podiam ter atalhos (“jump lists”) para tarefas comuns dentro de um app. O gerenciamento de janelas também ganhou novidades: um recurso útil que surgiu foi a possibilidade de “colar” janelas à direita ou esquerda da tela, facilitando rodar dois apps lado a lado, com cada um ocupando metade dela. Sendo o Windows 7 a ___base padrão___ agora para todos os futuros Windows (8,10 e 11)

![Descrição da Imagem](https://thumbnails.genial.ly/63fdceafe0331c001180edbc/screenshots/fc1fb32a-a9ca-437b-84fa-15d7da3fdbdc.jpg)

---

## Arquitetura presente no Windows

 ### Kernel
 
 #### Gerenciamento de Processos
   
 - >Controle da execução de programas e threads
 - >Priorização e escalonamento de processos

 #### Gerenciamento de Memória

 -  >Alocação de RAM e memória virtual
 -  >Proteção contra acessos indevidos

 #### Segurança e Permissões

 -  >Controle de Conta de Usuário (UAC)
 -  >BitLocker e criptografia de disco

 ### Interface Gráfica (GUI - Graphical User Interface)

 #### Windows Shell

- >Menu Iniciar, Barra de Tarefas e Explorador de Arquivos
- >Suporte a gestos e toque

 #### DWM (Desktop Window Manager)

- >Efeitos visuais, transparência e animações
- >Suporte a monitores de alta taxa de atualização

 #### Personalização e Estilo

- >Modo Escuro e temas customizáveis
- >Layouts dinâmicos e widgets

 ### Gerenciador de Arquivos (Windows Explorer / File Explorer)

 #### Navegação e Organização

- >Estrutura hierárquica de diretórios
- >Fixação de arquivos e pastas mais usados

 #### Sincronização e Armazenamento

- >Integração com OneDrive e armazenamento na nuvem
- >Compartilhamento e backup automático

 #### Recursos Avançados

- >Pesquisa Rápida e Indexação
- >Abas e multitarefa no Explorador

 ### Camada de Serviços e Drivers

 #### Serviços do Windows

- >Processos essenciais como Windows Update e Firewall
- >Gerenciamento de impressão e conectividade

 #### Gerenciamento de Hardware

- >Controle de drivers de dispositivos (GPU, teclado, mouse)
- >Plug and Play para reconhecimento automático

 #### Compatibilidade com Dispositivos

- >Suporte a drivers herdados
- >Modo de compatibilidade com versões antigas

### Subsistemas e Compatibilidade

 #### Execução de Aplicativos
- >Suporte a Win32, UWP e PWA
- >Integração entre apps modernos e antigos
 #### Windows Subsystem for Linux (WSL)
- >Permite rodar comandos e aplicações Linux no Windows
- >Suporte a múltiplas distribuições

 #### Suporte a Aplicativos Android
- >Disponível no Windows 11 via Amazon Appstore
- >Permite rodar apps móveis diretamente no PC
---
## Comandos do Windows

 ### Sfc 
Se você quer identificar possíveis erros do Windows e descobrir o que é a melhor coisa a ser feita, o comando CMD pode ajudar. Ao realizar a execução do prompt, ele vai fazer uma varredura em todo seu sistema e encontrar as falhas. Por essa razão, o processo pode demorar um pouquinho. Para isso, basta utilizar o seguinte comando:
 
 #### sfc /scannow
 
![Descrição da Imagem](https://lh5.googleusercontent.com/Z_GeeJ9kLieE_iJQsGtcz7wCw964lZQDxM-14pbKxgjsX2Ylth8UnFkqiUyx5FGOG1EooXdd3OfPU-uH5--QDDhIHJ4VrtRPWCKvBaYXKCQeyhixj5JsJznMPZdum8mcWhvRd7kz)

 ### Taskkill 
Se o computador travou e está difícil usar o gerenciador de tarefas, uma maneira de forçar o encerramento é por meio do taskkill. Insira o comando e, ao final, inclua o arquivo que precisa ser finalizado. No exemplo abaixo usamos o software Filezilla, que é um programa de auxílio para transferência de arquivos via FTP: 

 #### taskkill /f /im filezilla.exe 

![Descrição da Imagem](https://blog.betrybe.com/wp-content/uploads/2020/05/image30.png)

 ### Shutdown
Ao utilizarmos esse utilitário, conseguimos desligar sua máquina, mesmo que tenhamos algum problema que impeça isso. Basta incluir no comando do Windows “shutdown -r -t 300”, sem as aspas. Além disso, o shutdown contém interessantes variações. O 0 no comando é referente ao tempo que você deseja programar em segundos. Se colocar 300 ao invés de 0, isso significa que faremos uma programação para a máquina desligar em 5 minutos. Caso seu desejo seja reiniciar, substituímos o “-s” do comando por “-r”.

 ![Descrição da Imagem](https://blog.betrybe.com/wp-content/uploads/2020/05/image23.png)

 ### Ipconfig 
 Esse é um dos comandos mais comuns para quem é usa os comandos CMD do Windows. O comando “ipconfig /all” exibe diversas informações referentes à sua internet. Para quem trabalha com rede, é um excelente utilitário.

  ![Descrição da Imagem](https://lh6.googleusercontent.com/8OW3w2ie_-AeOFHS5zaA0CgVma5LAeGiCtdNJrloDMzJYumFPElu_yvnnKez85o8NB1zed_sqDhYRLqHRKWhaPeEgo1dA60pXL7o4i_TgG_A7o-FXNOxAAm2HmP_8uOINK4m4ecO)

 ### Assoc 
 Você baixou um arquivo da internet, mas não sabe qual programa e/ou aplicativo na sua máquina é ideal para executá-lo? Basta utilizar “assoc” juntamente com o tipo de arquivo em questão.

 ![Descrição da Imagem](https://lh5.googleusercontent.com/-hGp-NU13Lz-Q9dTwETJsQdA3yF441gKG8OKSNmQocphG7beMTR3IpzZ7V5Mi9Ma_OULe9dd8cfOCC53IYQ_X3cTfytUU6AoYtvoij992q1dkTKTeAhBeAZFdEnjk9XEt5CO3KsR)

 O resultado será uma listagem de extensões grande, dependendo das extensões que você tiver em seu equipamento.

 ### Driverquery 
 É muito comum termos diferentes drivers para conseguir rodar nossos programas, certo? Mas como conseguir controlá-los e saber quais são referentes a cada diretório? Com “driverquery -v”, sem as aspas, identificamos os drivers instalados em nossas máquinas:

![Descrição da Imagem](https://lh6.googleusercontent.com/f4gy8N9GQFT731pkEMrDKJFlACntBtmfAeUnaxWyVkbrnVG8Owre9AaCzl7CCZ5eE4HAJPznblIAOwmvpmGIEsYJ1rURI8vLLi_obUfS679BZ6B6vOhZFjN62tWJab-Ngs6HOcCi) 

O resultado poderá ser uma listagem grande, dependendo da quantidade drivers instalados.

---

## Curiosidades

### Historia do som de inicialização
O som original do Windows 95 foi criado por Brian Eno, famoso produtor musical. Ele foi escolhido para dar um tom futurista e agradável, e o som foi o primeiro a ser feito por um compositor de renome para um sistema operacional.

### Modo Deus
O 'Modo Deus' é uma ferramenta secreta: O "God Mode" do Windows não é um modo de invencibilidade, mas sim uma pasta oculta que permite acessar todas as configurações do sistema de maneira rápida e prática. Para ativá-lo, basta criar uma pasta e renomeá-la como: GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}.

### Versões vazadas
Em 1995, antes de seu lançamento oficial, a versão beta do Windows 95 foi vazada para a internet, fazendo com que milhões de pessoas já testassem o sistema operacional antes da data oficial. Isso ajudou a gerar uma enorme expectativa.

### Lago Azul
O erro fatal "Tela Azul da Morte" (BSOD) do Windows, que já foi conhecida por ser um problema temido, tinha uma versão de tela azul diferente durante os testes do Windows 10. Durante um período, o fundo da BSOD era um "lago azul" ao invés da tradicional tela preta com texto de erro.

### Simulador de graficos
O Windows 1.0, lançado em 1985, não tinha o famoso desktop gráfico que conhecemos hoje. Mas ele vinha com um pequeno programa chamado "Paint", que permitia desenhar gráficos simples com o mouse, muito antes de se tornar um aplicativo popular.
