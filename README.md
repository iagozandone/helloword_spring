# HelloWord Spring Boot

Este é um projeto simples utilizando o Spring Boot para criar uma aplicação RESTful básica.  
Ideal para iniciantes que desejam aprender sobre o desenvolvimento de APIs com Spring Boot.

## 🚀 Tecnologias Utilizadas

- **Java 17** – Versão do JDK utilizada para o desenvolvimento.
- **Spring Boot 3.4.5** – Framework para construção da aplicação.
- **Maven Wrapper** – Ferramenta para gerenciamento de dependências e execução do Maven sem necessidade de instalação prévia.

## 📦 Pré-requisitos

- JDK 17 ou superior instalado.
- Acesso à internet para download das dependências.

## 🔧 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/iagozandone/helloword_spring.git
cd helloword_spring
```
### 2. Execute a aplicação

Utilize o Maven Wrapper para compilar e rodar a aplicação:

```bash
./mvnw spring-boot:run
```
A aplicação estará disponível em http://localhost:8080

### 3. Teste a API

Você pode testar a API utilizando o curl ou qualquer ferramenta de sua preferência:

```bash
curl http://localhost:8080/hello
```

A resposta esperada será:
```bash
<b>Hello Word!</b>
```

Para o endpoint /hello/turma82:
```bash
curl http://localhost:8080/hello/turma82
```
Resposta esperada:
```bash
<b>A Turma Java 82 é TOP!</b>
```
## 🧪 Testes

Para rodar os testes automatizados:
```bash
./mvnw test
```

Os testes estão localizados no diretório src/test/java.

## 📄 Estrutura do Projeto
```bash
helloword_spring/
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── generation/
│   │   │           └── helloword/
│   │   │               ├── HellowordApplication.java
│   │   │               └── HelloWordController.java
│   │   └── resources/
│   │       └── application.properties
└── README.md
```
- HellowordApplication.java: Classe principal que inicializa a aplicação Spring Boot.

- HelloWordController.java: Controlador REST que define os endpoints /hello e /hello/turma82.

- application.properties: Configurações da aplicação.

## 🤝 Contribuindo

1. Faça um fork deste repositório.

2. Crie uma branch para sua feature (git checkout -b minha-feature).

3. Realize suas alterações e commit (git commit -am 'Adiciona nova feature').

4. Envie para o repositório remoto (git push origin minha-feature).

5. Abra um pull request explicando suas alterações.

## 📞 Contato

Desenvolvido por Iago Zandone.

* [GitHub](https://github.com/iagozandone)
* [LinkedIn](https://www.linkedin.com/in/iagozandone)
* [Portfólio Pessoal](https://iagozandone.github.io/portfolio_fundweb/)
