# Pesquisa Colaborativa - Github

Grupo: Gyck|Sense

## 1. Funções de um Sistema Operacional
---

Autor: Karine

**Um sistema operacional (SO) tem a função de servir como intermediário entre o hardware e o software, fornecendo uma interface para o usuário e gerindo recursos de forma eficiente.**

### 1.1. Gerenciamento de processos
---

**O gerenciamento de processos é uma das principais funções de um sistema operacional, responsável por controlar e coordenar todas as atividades de execução de programas (processos) no sistema.**
***Criação, Execução e Finalização:***
O SO cria novos processos, inicia sua execução e os finaliza quando necessário.
***Agendamento:***
O SO decide qual processo deve ser executado em determinado momento, usando algoritmos de escalonamento para garantir a eficiência.
***Alocação de Recursos:***
O SO aloca recursos do sistema (como CPU, memória, dispositivos) aos processos em execução.
***Comunicação e Sincronização:*** 
O SO facilita a comunicação e sincronização entre processos, permitindo que eles compartilhem dados e cooperem.

### 1.2. Gerenciamento de arquivos
---

**O gerenciamento de arquivos é uma função essencial de um sistema operacional (SO), responsável por organizar, armazenar e acessar arquivos em dispositivos de armazenamento.** 
***Criação e Deleção de Arquivos:***
O sistema operacional permite aos usuários criar novos arquivos e deletar arquivos não mais necessários. 
***Organização em Diretórios:***
Os arquivos são organizados em diretórios (pastas) para facilitar a navegação e o acesso.
***Acesso e Permissões:***
O sistema operacional controla o acesso aos arquivos, definindo quais usuários têm permissão para ler, gravar ou executar um determinado arquivo. 
***Mapeamento de Arquivos em Disco:***
O sistema operacional mapeia os arquivos em disco, permitindo que os programas acessem os dados de forma eficiente. 

![Processos](https://miro.medium.com/v2/resize:fit:1200/1*qEgqvqcXDNB96ks4czt_gQ.png)
[Sistemas Operacionais](https://educacao.fit-tecnologia.org.br/courses/course-v1:fiteducacao+UX+WEB-2020/courseware/66e07b15f44a4b38912869892c8b5757/993ae6a32d0b420e87a13a7ee6eb7005/?activate_block_id=block-v1%3Afiteducacao%2BUX%2BWEB-2020%2Btype%40sequential%2Bblock%40993ae6a32d0b420e87a13a7ee6eb7005)

## 2. Sistemas de Arquivos
---

Autor: Gabriela

### 2.1. O que é um sistema de arquivos?
---

**Sistema de arquivo** (file system) é um conjunto de regras e estruturas usadas para organizar, gerenciar e armazenar informações em HDDs, módulos SSDs, CDs, DVDs, pen drives e cartões de memória. São essas regras que determinam como os dados serão gravados no dispositivo de armazenamento.
Existem muitos sistemas de arquivos, cada um projetado para suportar diferentes ambientes, sistemas operacionais, dispositivos, necessidades e plataformas.
Alguns exemplos de file systems comuns incluem o FAT32, NTFS, ReFS e exFAT utilizados por dispositivos Windows, HFS+ e APFS (macOS) e ext2, ext3, ext4 e btrfs encontrados em ambientes Linux.
Os sistemas de arquivo são os elementos responsáveis por gerenciar como os dados são escritos, armazenados e recuperados.
Eles mantêm diversas informações (metadados) sobre onde os dados estão alocados nos dispositivos de armazenamento e como o espaço livre será utilizado.
Essas regras também são importantes para manter a integridade dos dados, uma vez que elas gerenciam o processo de leitura e gravação de dados. Tipos de sistemas de arquivos: FAT32, NTFS, ext4
Um sistema de arquivos é um método que o sistema operacional usa para organizar e gerenciar arquivos e diretórios em um dispositivo de armazenamento, como um disco rígido ou um pendrive. Ele define como os dados são armazenados, acessados e organizados no dispositivo. Diferentes sistemas de arquivos (como FAT32, NTFS e ext4) possuem características específicas e são usados em diferentes sistemas operacionais ou dispositivos.
[Sistema de arquivos: o que é e qual sua importância | 4infra]https://4infra.com.br/o-que-e-sistema-de-arquivos/#:~:text=Alguns%20exemplos%20de%20sistemas%20de,%2C%20ext3%2C%20ext4%20e%20btrfs.
![sistema de arquivos](https://4infra.com.br/wp-content/uploads/2023/11/Sistema-de-Arquivos-1024x683.jpg)

### 2.2. Tipos de sistemas de arquivos: FAT32, NTFS, ext4
---

Existem diversos sistemas de arquivos, cada um desenvolvido para atender a diferentes ambientes, sistemas operacionais, dispositivos, necessidades e plataformas.
Alguns exemplos de sistemas de arquivos comuns incluem o FAT32, NTFS, ReFS e exFAT, utilizados por dispositivos Windows, enquanto o HFS+ e APFS são empregados no macOS. Já em ambientes Linux, encontramos sistemas como ext2, ext3, ext4 e btrfs.
Os sistemas de arquivo desempenham um papel crucial no gerenciamento da escrita, armazenamento e recuperação de dados. Eles mantêm informações detalhadas, também conhecidas como metadados, sobre a localização dos dados nos dispositivos de armazenamento e como o espaço livre será utilizado.
Essas regras são essenciais não apenas para a organização eficiente dos dados, mas também para preservar a integridade das informações. Isso ocorre porque elas supervisionam o processo de leitura e gravação de dados, garantindo um funcionamento consistente e seguro.

## 3. Gerenciamento de Dispositivos
---

Autor: Kayla


### 3.1. Como o SO se comunica com impressoras, HDs, mouses etc.
---

O Sistema Operacional (SO) se comunica com periféricos como impressoras, HDs e mouses através de drivers, que são programas que permitem que o SO interaja com os dispositivos. Os drivers traduzem as solicitações do SO em comandos específicos para cada dispositivo, e vice-versa. 

![nome da imagem](image.png)

### 3.2. O papel dos drivers de dispositivos
---

Os drivers de dispositivos são softwares que permitem a comunicação entre o sistema operacional e o hardware. Eles atuam como intermediários, traduzindo os comandos do sistema operacional para uma linguagem que o hardware possa entender, e vice-versa. Sem os drivers, um dispositivo de hardware não pode ser utilizado. 

[nome do site](https://learn.microsoft.com/pt-br/windows-hardware/drivers/gettingstarted/what-is-a-driver-)

## 4. Painel de Controle e Configurações
---

Autor: Yago Smirelli

O Painel de Controle é uma ferramenta usada para visualizar e modifcar as configurações do sistema. Já o app Configurações é o sucessor do Painel de Controle, com as mesmas configurações, e com um acesso simplificado.

[Acessibilidade](https://mwpt.com.br/ferramentas-de-acessibilidade-nativas-do-windows-e-do-seu-celular-android-que-voce-precisa-conhecer/#:~:text=Filtros%20de%20cor:%20essa%20%C3%A9,com%20o%20tipo%20de%20daltonismo)
![Painel de Controle](https://s2-techtudo.glbimg.com/_PwrPkjYh_A6XtlBbhFH_uh7pgk=/0x0:695x491/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/w/8/UQ4fhpQeCUW4aKkZ9llQ/2015-06-19-captura-de-tela-2015-06-13-as-202914.png)

### 4.1. O que pode ser configurado: rede, som, tela, idioma
---

No Painel de Controle do Windows (que está gradualmente a ser substituído pela app Configurações) é possível configurar diversas funcionalidades relacionadas com a rede, som, tela e idioma, entre outras. 
Rede:
Configuração de conexões de rede:
O Painel de Controle permite configurar e gerir as conexões de rede, como conexões Wi-Fi, Ethernet, VPN, entre outras.
Configuração de propriedades de rede:
Permite ajustar propriedades como endereços IP, DNS, e outros protocolos de rede.
Visualização do estado da rede:
Permite verificar o estado da conexão de rede, como a conexão Wi-Fi ativa, a velocidade de upload/download, entre outros. 
Som:
Configuração de dispositivos de áudio: O Painel de Controle permite escolher o dispositivo de saída de áudio (alto-falantes, fones de ouvido) e de entrada (microfone).
Configuração de volume e qualidade de áudio: Permite ajustar o volume de cada dispositivo e a qualidade do áudio.
Configuração de efeitos de áudio: Permite aplicar efeitos de som, como equalização, e outros efeitos. 
Tela:
Configuração de resolução:
Permite alterar a resolução da tela, ajustando-a para a que melhor se adapta ao seu monitor.
Configuração de layout da tela:
Permite configurar o layout da tela, como a orientação (horizontal/vertical), a escala e outras opções.
Configuração de tema da tela:
Permite escolher o tema da tela, que pode ser uma cor sólida, um padrão ou uma imagem. 
Idioma:
Configuração do idioma de entrada:
Permite selecionar o idioma de entrada do teclado, permitindo que você possa usar diferentes idiomas para escrever.
Configuração do idioma de exibição:
Permite escolher o idioma de exibição do sistema operacional, alterando assim o idioma do sistema operacional.
Configuração de formatos de data e hora:
Permite configurar o formato de data e hora, ajustando-o para o padrão do seu país. 
Em resumo, o Painel de Controle oferece uma forma centralizada de gerir as configurações do sistema, incluindo a rede, som, tela e idioma. 


### 4.2. Ferramentas de acessibilidade
---

Ferramentas de Acessibilidade no Windows:
Narrador: Um leitor de tela que lê o conteúdo do ecrã em voz alta, permitindo que pessoas com deficiência visual naveguem no sistema. 
Lupa: Permite ampliar a exibição do ecrã para facilitar a leitura e a visualização de detalhes. 
Contraste: Ajusta as cores do ecrã para melhor visibilidade, especialmente para pessoas com deficiência visual ou baixa visão. 
Filtros de cor: Permite personalizar as cores do ecrã para ajudar a diferenciar cores e facilitar a leitura. 
Legendas ao vivo: Transcreve o áudio em tempo real para legendas, facilitando a audição de pessoas com deficiência auditiva. 
Acesso por voz: Permite controlar o computador com comandos de voz, ideal para pessoas com dificuldades em usar o teclado e o rato. 
Controlo com os olhos: Permite navegar no computador com os olhos, útil para pessoas com dificuldades motoras. 
Digitação por voz: Permite digitar textos e e-mails utilizando comandos de voz. 
Teclado na tela (OSK): Permite digitar usando um teclado virtual, útil para pessoas com dificuldades em usar o teclado físico. 
Atalhos de teclado: Permitem executar ações mais rapidamente e de forma mais eficiente. 
Controlo do rato e teclado: Permite personalizar as configurações do rato e teclado para facilitar o uso. 
Windows Hello: Permite entrar no sistema sem senha, utilizando reconhecimento facial ou impressão digital. 
Verificador de acessibilidade: Permite verificar se um documento ou e-mail é acessível. 
Gestos de toque: Permite usar gestos de toque para interagir com o sistema. 
Compatibilidade com dispositivos braille: O Narrador é compatível com dispositivos Braille, permitindo que pessoas com deficiência visual leiam e escrevam em Braille. 


## 5. Ferramentas do Sistema
---

Autor: Gustavo


### 5.1. Gerenciador de Tarefas
---

Um gerenciador de tarefas, no contexto de software, é uma ferramenta que permite listar, organizar, priorizar e acompanhar o progresso de tarefas
Gerenciador de Tarefas (Windows): Em português: Gerenciador de Tarefas (sem "do Windows"), Em inglês: Task Manager.
Monitor do Sistema (Linux/macOS):
Em português: Monitor do Sistema (ou Gerenciador de Tarefas, dependendo do contexto, mas o primeiro é mais apropriado para a função)
Em Windows, "Gerenciador de Tarefas" é a ferramenta padrão para gerenciar processos e desempenho do sistema.
Em Linux e macOS, "Monitor do Sistema" é a ferramenta padrão para monitorar o desempenho do sistema, mas também pode ser chamado de "Gerenciador de Tarefas" em algumas situações, dependendo da distribuição ou contexto.
A nomenclatura "Monitor do Sistema" é mais genérica e mais apropriada para a função de monitoramento, enquanto "Gerenciador de Tarefas" pode ter uma conotação mais direta com a gestão de processos.
Em contextos específicos, como a interface do usuário de uma aplicação ou ferramenta, a nomenclatura pode variar (por exemplo, "Monitor de Desempenho" ou "Ferramenta de Monitoramento").


[nome do site](https://www.youtube.com/watch?v=RFtF-G3wUAQ)
![nome da imagem](https://images.wondershare.com/recoverit/task-manager-mac-1.jpg)


### 5.2. Prompt de Comando / Terminal
---

 É uma interface de linha de comando (CLI) que permite que o utilizador interaja com o sistema operacional (SO) através de comandos de texto, em vez de uma interface gráfica.
 Permite visualizar o desempenho do sistema, incluindo o desempenho de processos e serviço.
No Windows, clique com o botão direito no ícone do Windows, selecione "Pesquisar" e digite "Prompt de Comando".
 Clique com o botão direito e selecione "Executar como administrador", de acordo com a EaseUS. 
1. Acessar o Prompt de Comando: Abra o Prompt de Comando (Windows) ou o Terminal (Linux/macOS) como administrador. 
2. Identificar a Unidade: Determine qual a letra da unidade que deseja formatar (ex: D:, E:, etc). 
3. Usar o Comando format: Digite o comando "format" seguido da letra da unidade, do parâmetro /FS: e o sistema de arquivos desejado (FAT32, NTFS ou exFAT). 
4. Formatação Rápida: Adicione o parâmetro /Q para uma formatação rápida, que elimina a necessidade de verificar a unidade. e Enter.
 Substitua "[número_do_disco]" pelo número correspondent.


[nome do site](https://www.youtube.com/watch?v=qGdOFdBPBRM&pp=0gcJCdgAo7VqN5tD)
![nome da imagem](https://dtnetwork.com.br/wp-content/uploads/2023/07/comandos-basicos-do-cmd.png)

