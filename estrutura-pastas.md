# Estruturas de Pastas no Linux

## Agradecimentos
> Obrigado Diolinux por proporcionar cada vez mais conhecimento sobre esse sistema que parece ser amedrontador, mas é incrível!

A estrutura de pastas do Linux pode muitas vezes ser algo bem difícil de compreender para quem está acostumado com o sistema Windows. Então, para abordar de uma forma certamente resumida. Vamos falar sobre as **Estruturas de Pastas** presentes nos sistemas Unix.

---

Bom, para começar, os sistemas Unix não tem uma pasta base como a `C:/` do Windows, a pasta base do Unix tem muitas informações, mas abaixo, coloco algumas das pastas presentes e seus significados.

Para acessar a pasta base dos sistemas Unix, podemos usar o seguinte comando:

`
cd /
`

Existem muitas pastas com permissões únicas e tipos de arquivos diferentes. Algumas delas, são **links** (sim, links mesmo) que direcionam para outras pastas presentes do sistema. Um exemplo desse tipo de pasta é a `bin`, que ao acessar as propriedades, veremos que ela direciona para `usr/bin`. Esses links existem para ter maior compatibilidade e conveniência de acesso.

E outros tipos de pastas, são as que o usuário comum não tem permissão de acesso, ou seja, são pertencentes ao usuário root.

## Resumo das pastas

> Obs: pode ser que seu computador não tenha todas as pastas listadas abaixo

`bin`aries: pasta onde podemos encontrar os executáveis de aplicativos do sistema (no Linux, nem todo executável precisa ser binário, então na pasta também é possível encontrarmos scripts do sistema).

`boot`: arquivos responsáveis pelo boot do sistema operacional.

`cdrom`: essa pasta é chamada de **ponto de montagem** (no Windows, é como vemos no Computador quando um disco é inserido), é nessa pasta que serão exibidos os arquivos de um CD conectado ao computador.

`dev`ices: essa pasta armazena os arquivos que correspondem ao hardware do computador (sim, o hardware no Linux é representado por arquivos, um deles, é o arquivo **sda** que também é conhecido como o HD).

`etc`: essa pasta armazena arquivos de configuração de softwares do sistema para os usuários. Muitas coisas que configuramos através de uma interface gráfica (por exemplo, uma rede Wi-Fi) podem alterar arquivos desse diretório (tudo por baixo dos panos).

`home`: essa pasta armazena dados dos usuários comuns do computador, é como a pasta padrão do Windows, onde encontramos o diretório de Documentos, Imagens, Músicas etc.

`lib`
`lib32`
`lib64`
`libx32`
Todas essas pastas são as bibliotecas de software para os desenvolvedores.

`lost+found`: em caso do sistema Linux ser interrompido por algum erro, assim que for iniciado, ele tentará fazer a recuperação dos arquivos, e caso tenha arquivos corrompidos, é nessa pasta que irão ser colocados.

`media`: essa pasta é parecida com a **cdrom**, porém, ao invés de CD's, ela é voltada para dispositivos removíveis (pendrives, cartões de memória etc).

`mnt`: essa pasta é mais um ponto de montagem, mas ao contrário da pasta **media**, serve para o usuário fazer a montagem que deseja.

`opt`ional: forma opcional de instalar alguns softwares no Linux, separando o conteúdo do programa do restante do sistema, um exemplo disso, é a instalação do Google Chrome no Linux, ele coloca os arquivos de instalação nessa pasta.

`proc`esses: diretório de arquivos virtuais, ou seja, são arquivos criados quando o computador é iniciado, são armazenados em memória e removidos assim que o sistema é desligado.

`root`: por padrão, essa pasta é inacessível, porém, é equivalente a pasta **home** do usuário comum, só que é para acesso do usuário root.

`run`time: outro diretório virtual, mas ao invés de armazenar processo, essa pasta armazena informações do sistema desde o último boot, por exemplo, os usuários logados.

`sbin`: essa pasta é a mesma coisa da pasta **bin**, porém os executáveis são apenas para o usuário root.

`snap`: só vai existir caso haja instalação de snaps.

`srv`: a pasta services (comumente inútil no desktop), é usado para caso formos rodar um servidor web, por exemplo, armazenar arquivos para outros usuários.

`sys`tem: essa é uma pasta virtual com arquivos que interagimos direto com o Kernel.

`tmp`: essa pasta armazena os arquivos temporários do sistema, que são excluídos ao reiniciarmos o dispositivo.

`usr`: nessa pasta, podemos encontrar arquivos de programas e bibliotecas consideradas "não essenciais" para o funcionamento e integridade do sistema.

`var`iable: essa pasta armazena arquivos de programas que se espera que aumentem de tamanho com o tempo e nela também podemos encontrar logs e arquivos de backup do sistema.
