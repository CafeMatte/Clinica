# Sistema de Gestão de Clinica Veterinária 🐶🐱
![Clinica veterinária](https://media.discordapp.net/attachments/1109909153431949333/1177220940225069076/image.png?ex=6571b76f&is=655f426f&hm=0d4ad78e8a54fe4402838437ac823e09c58c64018cfc65fe9c87bb9834378cb3&=&format=webp&width=553&height=459)

## Descrição 📑

O sistema de gestão de clínica veterinária tem como objetivo facilitar o gerenciamento de informações sobre os animais atendidos na clínica, bem como manter registros detalhados de seus históricos médicos. Para isso, o sistema é composto por três classes principais: Animal, Cão, Gato e Clínica.

## Proposta Clínica Veterinaria ⚕️
O sistema Clinica Veterinaria foi desenvolvido com base nas orientações do professor com os seguntes critérios:
1. **Classe Animal:**:
    - Atributos: nome, espécie, dono.
    - Métodos: getters, setters e **`toString()`**.
2. **Classe Cão**:
    - Herda de Animal.
    - Atributos: raça.
    - Métodos: getters e setters para os novos atributos e sobrescreva o método **`toString()`**.
3. **Classe Gato**:
    - Herda de Animal.
    - Atributos: tipo de pelagem.
    - Métodos: getters e setters para os novos atributos e sobrescreva o método **`toString()`**.
4. **Classe Clínica**:
    - Atributos: lista de animais registrados e seus históricos médicos.
    - Métodos: registrar animal, remover registro, listar animais, adicionar histórico médico.


## O Sistema💻
Conforme a proposta anterior, obtivemos o seguinte resultado:
1. **Classe Animal**
- **Atributos:**
    - **`nome`** (string): Nome do animal.
    - **`espécie`** (string): Espécie do animal (por exemplo, "Cão" ou "Gato").
    - **`Dono`** (string): Nome do dono do animal.
- **Métodos:**
    - **`getNome():`** Retorna o nome do animal.
    - **`setNome(nome):`** Define o nome do animal.
    - **`getEspécie():`** Retorna a espécie do animal.
    - **`setEspécie(espécie)`**: Define a espécie do animal.
    - **`getDono():`** Retorna o nome do dono do animal.
    - **`setDono(dono):`** Define o nome do dono do animal.
    - **`toString():`** Método que converte os atributos em uma representação de string.
2. **Classe Cão (Herda de Animal)**
- **Atributos adicionais:**
    - **`raça (string):`** Raça do cão.
- **Métodos adicionais:**
    - **`getRaça():`** Retorna a raça do cão.
    - **`setRaça(raça):`** Define a raça do cão.
    - **`toString():`** Sobrescreve o método **`toString()`** da classe Animal para incluir a raça.
3. **Classe Gato (Herda de Animal)**
- **Atributos adicionais**:
    - **`tipoPelagem (string):`** Tipo de pelagem do gato.
- **Métodos adicionais:**
    - **`getTipoPelagem():`** Retorna o tipo de pelagem do gato.
    - **`setTipoPelagem(tipoPelagem):`** Define o tipo de pelagem do gato.
    - **`toString():`** Sobrescreve o método **`toString()`** da classe Animal para incluir o tipo de pelagem.
4. **Classe Clínica**
- **Atributos:**
    - **`animaisRegistrados`** (lista): Lista de objetos do tipo Animal.
    - **`historicosMedicos`** (dicionário): Dicionário onde as chaves são os animais e os valores são listas de históricos médicos associados a cada animal.
- **Métodos:**
    - **`registrarAnimal(animal):`** Adiciona um novo animal à lista de animais registrados.
    - **`removerRegistro(animal):`** Remove o registro de um animal da lista.
    - **`listarAnimais():`** Retorna a lista de animais registrados.
    - **`adicionarHistoricoMedico (animal, historico):`** Adiciona um histórico médico à lista correspondente ao animal.
    - **`getHistoricoMedico(animal)':`** Retorna o histórico médico associado a um animal.


## Adicionais e Boas Práticas: 
Ao decorrer do desenvolvimento sentimos a necessidade de adicionar outras classes e boas práticas para melhor compreensão e correção de bugs do sistema.
1. **Classe Histórico Médico:**

- **Atributos:**
    - **`animal`** (Animal): puxará as informaçoes do pet.
    - **`Historico`** (String): Informará informação relevante da vida médica do pet.
    - **`DataHoraRegistro`** (LocalDateTime): Informará a entrada do PET ao consultório.
- **Métodos:**
    - **`getAnimal():`** Retorna animal.
    - **`setNome(Animal animal):`** Define animal.
    - **`getHistorico():`** Retorna o historico.
    - **`setHistorico(String historico)`**: Define qual o histórico.
    - **`getDataHoraRegistro():`** Define a data e hora do registro do Animal ao consultório.
    - **`setDataHoraRegistro(LocalDateTime DataHoraRegistro):`** Define a data e hora do registro do Animal .
    - **`toString():`** Método que converte os atributos em uma representação de string.


2. **Tratamento de exceções**

 Uso do try e catch para tratar os erros que podem acontecer ao ler o id do Animal nos seguintes métodos:
  - **Leitura de ID no Registrar Animal**
    
  - **Leitura do ID no Remover Animal**
 
  - **Leitura do ID no Adicionar Histórico**
 
  Nesses casos o usuário pode tentar digitar uma String no ID. Caso aconteça, o sistema retorna uma mensagem de erro e pede para digitar novamente.

    


## Como baixar e instalar o sistema⬇️

1. **Baixe o Código do Repositório GitHub** 
  - Abra o navegador e acesse o repositório no GitHub: [https://github.com/LuizGuidini/ProjetoClinica/tree/main/ClinicaVeterinaria]
  - Clique no botão verde "Code" e selecione a opção "Download ZIP".
  - Após o download, extraia o conteúdo do arquivo ZIP para o diretório desejado no seu computador.


2. **Abra o Projeto no IntelliJ IDEA**
 - Abra o IntelliJ IDEA.
 - Clique em "Open" ou "Abrir Projeto".
 - Navegue até o diretório onde você extraiu os arquivos do repositório.
 - Selecione a pasta do projeto e clique em "OK" ou "Abrir".

   



3. **Configure o SDK do Projeto (se necessário)**
 - Se o IntelliJ IDEA solicitar a configuração do SDK, selecione a versão do Java instalada em seu sistema.
 - Clique em "OK" ou "Aplicar".



4. **Execute a Aplicação**
 - Encontre a classe ClinicaVeterinaria no explorador de projetos.
 - Clique com o botão direito na classe e escolha "Run ClinicaVeterinaria.main()".


## Interagindo com a Aplicação
A aplicação será executada no console do IntelliJ IDEA e será apresentado um Menu com as seguintes opções:

  - **`Opção 1-Registrar Animal:`** Ao escolher Registrar Animal você foenecerá os dados do pet.
  - **`Opção 2-Remover Animal:`** Ao seloecionar Remover Animal, você removera os dados do pet do sistema.
  - **`Opção 3-Listar Animais:`** Ao escolher Listar Animais, o sistema mostrará na tela os dados dos animais cadastrados.
  - **`Opção 4-Adicionar Histórico Médico:`** Com esta opção o usuário tem pode adicionar um histórico médico ao animal cadastrado.
  - **`Opção 5-Listar Histórico Médico:`** Ao escolher esta opção o usuário poderá imprmir o Histórico Médico dos animais cadastrados.
  - **`Opção 9-Sair:`** O usuário sai do sistema.

 







## Equipe 🥇

- Rafaela Silva [Link - Git Hub](https://github.com/rafaelafsilva)
- Luiz Antonio Guidini [Link - Git Hub](https://github.com/LuizGuidini)
- Marcia Guidini [Link - Git Hub](https://github.com/MarciaGuidini)
- Matheus Vítor Martins [Link - Git Hub](https://github.com/CafeMatte)
