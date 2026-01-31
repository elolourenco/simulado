---

# Simulado: Respostas Formatadas

**1.** Conceito de programação que constrói o código em volta do objeto e não apenas da lógica, facilitando alterações e manutenção.

**2.** Esconde informações importantes, expondo apenas o necessário, trazendo mais segurança à aplicação.

**3.** Como está definido como público, permite que qualquer outra classe altere o valor diretamente.

**4.** Permitem validações futuras sem quebrar o código de quem utiliza a classe.

**5.** ```java
private double preco;

public double getPreco() {
return preco;
}

```

**6.** É um framework do Java que facilita a criação de aplicações, injeção de pacotes e dependências, tornando mais ágil a construção e manutenção de APIs.

**7.** `@RestController`

**8.** Mapeia rotas para classes ou métodos dentro do controller.

**9.** Mostra a entidade do banco de dados (exposição direta).

**10.** * **GET**: Consulta dados; 
* **POST**: Cria recurso; 
* **PUT**: Atualiza recursos que já existem; 
* **DELETE**: Remove recursos.

**11.** A JPA é um conjunto de regras/interfaces para persistência de dados. O Hibernate é a ferramenta que realmente executa essas regras, transformando classes Java em tabelas SQL.

**12.** `@Entity`

**13.** `@Id` define qual atributo é a chave primária; `@GeneratedValue` define a geração automática do ID.

**14.** Exibe métodos pré-definidos e ajuda na busca de dados de forma simplificada.

**15.** Aumenta a produtividade e deixa o código independente da tecnologia de banco de dados.

**16.** É um transferidor de dados de um objeto, serve para proteger os dados entre as camadas da aplicação.

**17.** Expõe a estrutura interna, causa falha na segurança do código e impede a validação correta de dados de entrada.

**18.** Guarda a regra de negócio da aplicação.

**19.** Camada **Service**. Serve para manter o código centralizado e reutilizável.

**20.** O controller tem o papel apenas de gerenciar a comunicação e retornar o status code adequado.

**21.** **S (SRP):** Uma classe deve ter apenas uma função/responsabilidade.

**22.** O controller deve exercer apenas uma função (gerenciar requisições).

**23.** **O (OCP):** Permite adicionar novos comportamentos sem alterar o código original já testado.

**24.** **L (LSP):** Uma classe filha deve poder substituir sua classe pai sem quebrar a aplicação.

**25.** **I (ISP):** Criar uma interface específica para cada validação ou necessidade, em vez de uma genérica.

**26.** Nesse conceito, a classe não conhece o detalhe da regra, está ligada apenas à interface, o que permite trocar a implementação sem afetar o sistema.

**27.** **D (DIP):** Dependa de abstrações (interfaces), não de implementações concretas.

**28.** Uso de `@Autowired` ou construtores para receber uma interface em vez de instanciar a classe manualmente.

**29.** **Fluxo:** Controller recebe o request -> extrai dados -> chama o Service (regra de negócio) -> chama o Repository -> Repository via JPA busca no banco de dados.

**30.** Com o **DTO** protegendo o domínio, o **Service** concentrando a regra de negócio e o **SOLID** definindo bem as camadas, a aplicação torna-se muito mais escalável.

---


```
