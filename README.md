# RPG Game - Aplicando Princípios SOLID e POO

Este projeto tem como objetivo desenvolver uma estrutura para jogos de interpretação de papéis (RPG), mais conhecidos como jogos RPG (Role Playing Game), aplicando os princípios da arquitetura SOLID e os princípios de Programação Orientada a Objetos (POO). Foi utilizado Node.js, Docker e docker-compose para facilitar o desenvolvimento e a execução do projeto.

## Princípios SOLID e POO

Neste projeto, aplicamos os princípios da arquitetura SOLID e os princípios de Programação Orientada a Objetos (POO) para criar uma estrutura flexível, extensível e de fácil manutenção para jogos de interpretação de papéis (RPG).

### Princípios SOLID

- **Princípio da Responsabilidade Única (SRP)**: Cada classe no projeto possui uma única responsabilidade, ou seja, possui apenas um motivo para mudar. Isso torna as classes mais coesas e facilita a manutenção.

- **Princípio Aberto-Fechado (OCP)**: As classes são abertas para extensão e fechadas para modificação. Isso significa que podemos adicionar novas funcionalidades ao projeto sem precisar modificar o código existente.

- **Princípio da Substituição de Liskov (LSP)**: As subclasses podem ser usadas no lugar de suas classes base sem causar problemas de funcionalidade. Isso promove a reutilização de código e facilita a criação de novas classes derivadas.

- **Princípio da Segregação de Interfaces (ISP)**: As interfaces são segregadas em interfaces menores e mais específicas, evitando que as classes implementem métodos desnecessários. Isso garante que as classes dependam apenas do que realmente precisam.

- **Princípio da Inversão de Dependência (DIP)**: As classes dependem de abstrações, não de implementações concretas. Isso permite que diferentes implementações sejam usadas sem modificar o código que as utiliza.

### Tecnologia Utilizada
- TypeScript: TypeScript é uma linguagem de programação desenvolvida pela Microsoft que estende o JavaScript com tipagem estática opcional, trazendo mais segurança e facilidade na detecção de erros. Com recursos de programação orientada a objetos e compatibilidade com o JavaScript, o TypeScript melhora a legibilidade e a manutenção do código, além de possuir ampla comunidade e suporte de ferramentas.
- Classes: Classes na programação orientada a objetos são estruturas que encapsulam propriedades e comportamentos relacionados em um objeto. Elas definem a estrutura e o comportamento dos objetos, permitindo a criação de múltiplas instâncias com base em uma mesma classe.
- Instâncias: Instância é um objeto criado a partir de uma classe específica. É uma representação concreta da estrutura e do comportamento definidos na classe.
- Atributos: Atributos em POO são características ou propriedades associadas a uma classe ou instância dela.
- Métodos: Métodos em POO são funções que definem o comportamento dos objetos de uma classe.
- Objetos: Objetos em POO são instâncias de uma classe que possuem propriedades e comportamentos definidos pela classe.

- Node.js: Utilizei o Node.js como plataforma de desenvolvimento para criar a estrutura do projeto e implementar a lógica do jogo.

- Docker: Utilizei o Docker para facilitar o gerenciamento de dependências e a execução do projeto em diferentes ambientes. Com o Docker, é possível isolar o ambiente de execução do jogo e garantir sua portabilidade.

- Docker Compose: Utilizei o Docker Compose para facilitar a configuração e a execução de um contêiner Docker que compõe o ambiente de execução do projeto. Com o Docker Compose, é possível definir e orquestrar o serviço necessário para executar o jogo de forma simples e consistente.


## Como Executar o Projeto

Para executar o projeto, siga as etapas abaixo:

1. Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixar o Node.js em https://nodejs.org.

2. Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina. Você pode baixar o Docker em https://www.docker.com/products/docker-desktop e o Docker Compose em https://docs.docker.com/compose/install.

3. Clone este repositório em seu ambiente de desenvolvimento:
``` git clone git@github.com:matheusPrado007/rpg-dragons.git ```

4. Acesse o diretório do projeto:
```cd rpg-dragons ```

5. Execute o comando para instalar as dependências do projeto:
```npm install ```


## Contribuição

Se você quiser contribuir para este projeto, sinta-se à vontade para fazer um fork do repositório, fazer as alterações desejadas e enviar um pull request com suas melhorias.




