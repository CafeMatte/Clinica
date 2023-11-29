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


## Adicionais e Boas Práticas
Ao decorrer do desenvolvimento sentimos a necessidade de adicionar outras classes e boas práticas etc etc etc
1. **Classe Histórico Médico:**



## Como baixar e instalar o sistema⬇️
 







## Equipe 🥇

- Rafaela Silva [Link - Git Hub](https://github.com/rafaelafsilva)
- Luiz Antonio Guidini [Link - Git HUb](https://github.com/LuizGuidini)
- Marcia Guidini [Link - Git Hub](https://github.com/MarciaGuidini)
- Matheus Vítor Martins [Link - Git Hub](https://github.com/CafeMatte)
