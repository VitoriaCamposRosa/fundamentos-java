# Fundamentos, Evolução e o Ecossistema Java

Curso: Ciência da Computação  
Disciplina: Paradigmas de Linguagens de Programação  
Professor: Marcelo Josue Telles  

Autora: Vitória Campos da Rosa  
Porto Alegre – 2026

---

# Sumário

- [Introdução](#introdução)
Parte 1 – Histórico e Evolução do Java
  - [Criação do Java](#criação-do-java)
  - [Empresa responsável pelo Java](#empresa-responsável-pelo-java)
  - [Objetivo principal do Java](#objetivo-principal-do-java)
  - [Principais versões do Java](#principais-versões-do-java)
Parte 2 – Ambientes de Desenvolvimento (IDEs)
  - [Matriz de Diferenciação Técnica](#matriz-de-diferenciação-técnica)
  - [Visualização da Interface de Desenvolvimento](#visualização-da-interface-de-desenvolvimento)
  - [Diagnóstico da Melhor IDE para os Estudos](#diagnóstico-da-melhor-ide-para-os-estudos)
Parte 3 – Programação Orientada a Objetos (POO)
  - [Classe](#classe)
  - [Encapsulamento](#encapsulamento)
  - [Herança](#herança)
  - [Polimorfismo](#polimorfismo)
Parte 4 – Mercado de Trabalho para Desenvolvedores Java
  - [Panorama Salarial (Referência Brasil)](#panorama-salarial-referência-brasil)
  - [Verticais de Atuação](#verticais-de-atuação)
  - [Stack Tecnológico Indispensável](#stack-tecnológico-indispensável)
- [Conclusão](#conclusão)

---

# Introdução
  O Java não surgiu apenas como uma linguagem de programação, mas como uma resposta disruptiva à fragmentação tecnológica da década de 90. A sua filosofia fundamental, "Write Once, Run Anywhere" (Escrever uma vez, correr em qualquer lugar), revolucionou a indústria ao introduzir a Java Virtual Machine (JVM), uma camada de abstração que isola o software das complexidades do hardware subjacente. Este paradigma moldou o desenvolvimento moderno, estabelecendo padrões de robustez e portabilidade que permitiram a criação de sistemas globais escaláveis e independentes de plataforma.

---

# Parte 1 – Histórico e Evolução do Java

## Criação do Java

  A linguagem de programação Java foi criada em 1995 por James Gosling, juntamente com Mike Sheridan e Patrick Naughton. O desenvolvimento ocorreu na empresa Sun Microsystems.
Inicialmente, o projeto tinha como objetivo criar softwares para dispositivos eletrônicos e sistemas embarcados. No entanto, com o crescimento da internet, a linguagem passou a ser utilizada para o desenvolvimento de aplicações web.

## Empresa responsável pelo Java

  Lançado oficialmente em 1995 pela Sun Microsystems, sob a liderança de James Gosling, o Java foi inicialmente projetado para dispositivos inteligentes. Contudo, o seu verdadeiro impacto deu-se na Web e nos sistemas corporativos. Em 2010, a Oracle Corporation adquiriu a Sun, um marco que gerou apreensão inicial na comunidade, mas que resultou numa profissionalização da gestão da linguagem. Sob a tutela da Oracle, o ecossistema bifurcou-se de forma saudável entre o OpenJDK (a implementação de referência de código aberto) e o Oracle JDK (com suporte comercial), garantindo que a linguagem permanecesse gratuita para a comunidade enquanto oferecia garantias de nível empresarial para o setor corporativo.

## Objetivo principal do Java

  O principal objetivo do Java é oferecer uma linguagem de programação portátil, segura e orientada a objetos. Isso permite que aplicações sejam desenvolvidas de forma estruturada e executadas em diferentes plataformas.
  O Java teve um grande impacto na programação moderna, principalmente em sistemas corporativos e aplicações de grande escala. Muitas empresas utilizam Java para desenvolver sistemas bancários, aplicações web e serviços que precisam suportar milhões de usuários.
  
## Principais versões do Java

  Ao longo dos anos, o Java provou ser resiliente ao adotar inovações que o mantiveram competitivo:
  
- Java 5 (2004): Um salto qualitativo com a introdução de Generics, Enums e Annotations, ferramentas que reduziram erros de tipagem e permitiram o surgimento de frameworks modernos como o Spring.
- Java 8 (2014): Introduziu as Lambda Expressions e a Stream API, integrando conceitos de programação funcional e permitindo o processamento eficiente de coleções de dados.
- Java 9 e o Ciclo Semestral: A partir da versão 9, o Java adotou um ciclo de lançamentos a cada seis meses. Como mentor, sublinho a importância estratégica das versões LTS (Long Term Support), como o Java 11, 17 e 21. Para o mercado profissional, estas são as âncoras de estabilidade; enquanto as versões intermédias servem para inovação rápida, as LTS são as escolhidas para produção devido ao seu suporte prolongado.
  
O impacto do Java reside nesta capacidade única de equilibrar a inovação agressiva com a segurança e a retrocompatibilidade necessárias para sistemas críticos.

---

# PARTE 2 – AMBIENTES DE DESENVOLVIMENTO (IDEs)

  A escolha de uma IDE é uma decisão de engenharia que impacta diretamente a produtividade e a saúde do código. Uma ferramenta robusta atua como um mentor silencioso, aplicando análises estáticas e sugerindo refatorações que elevam a qualidade técnica do projeto antes mesmo da fase de testes.

## Matriz de Diferenciação Técnica

| IDE | Vantagens | Desvantagens | URL Oficial |
| :--- | :--- | :--- | :--- |
| **IntelliJ IDEA** | Assistência de código inteligente, suporte superior para frameworks modernos e refatoração preditiva. | A versão Ultimate (completa) é paga; exige hardware com elevada memória RAM. | [jetbrains.com/idea](https://www.jetbrains.com) |
| **Eclipse** | Gratuito, código aberto e extremamente estável para sistemas legados e grandes monólitos. | Interface datada; a gestão de plugins pode tornar-se complexa e instável. | [eclipse.org](https://www.eclipse.org) |
| **Apache NetBeans** | Integração nativa com ferramentas Apache, excelente suporte para Swing e configuração simplificada. | Ecossistema de extensões menos vibrante que o dos concorrentes. | [netbeans.apache.org](https://netbeans.apache.org) |

## Visualização da Interface de Desenvolvimento

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/6b3aafb4-0bc6-4205-9499-8ce63d3619c7" width="300"></td>
    <td>
      <h3>Apache NetBeans</h3>
      <p>Simples e direta, excelente para criar interfaces gráficas (Swing) e fácil de configurar nativamente.</p>
    </td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/1162b0f1-d68a-4d7f-ada3-b8d5c0c59c8d" width="300"></td>
    <td>
      <h3>Eclipse</h3>
      <p>Um clássico altamente extensível via plugins, ideal para projetos complexos e totalmente gratuitos.</p>
    </td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f0b00164-e619-4e36-b373-5ef8a7ce60d8" width="300"></td>
    <td>
      <h3>IntelliJ IDEA</h3>
      <p>A mais moderna e "inteligente", famosa pela auto completagem fluida e refatoração avançada (paga/gratuita).</p>
    </td>
  </tr>
</table>

## Diagnóstico da Melhor IDE para os Estudos

  Para um estudante de Programação Orientada a Objetos (POO), a minha recomendação é o IntelliJ IDEA (Community Edition). A sua capacidade de sinalizar erros de lógica em tempo real e a interface limpa permitem que o aluno se foque nos conceitos de arquitetura de software, em vez de se perder em configurações burocráticas da ferramenta.

---

# PARTE 3 – PROGRAMAÇÃO ORIENTADA A OBJETOS (POO) 

  A POO é a espinha dorsal do Java, permitindo a construção de sistemas que imitam a modularidade do mundo real. Este paradigma não serve apenas para organizar código; ele é a fundação para a criação de software extensível, onde a alteração num módulo não colapsa a estrutura inteira do sistema.

## Classe

A Classe define o contrato e os atributos (blueprint), enquanto o objeto é a materialização deste contrato na memória.

```java
// Classe: O modelo
class Carro {

    String modelo;
    int ano;

}

// Objeto: Instância da classe
public class Main {

    public static void main(String[] args) {

        Carro meuCarro = new Carro();
        meuCarro.modelo = "Sedan";
        meuCarro.ano = 2024;

        System.out.println(meuCarro.modelo);

    }

}
```

## Encapsulamento 

  Não se trata apenas de "esconder" variáveis, mas de garantir a integridade do estado interno do objeto. Ao usar métodos acessores, impedimos que o objeto entre num estado inválido (ex: saldo negativo ou idade impossível).

## Herança

  Permite a especialização de comportamentos, promovendo a reutilização e a organização hierárquica.

## Polimorfismo

  A capacidade de um objeto assumir múltiplas formas. Para ser efetivo, exige a sobrescrita de métodos para que o comportamento mude conforme o tipo real da instância.

  O domínio destes pilares garante a segurança do código e a facilidade de manutenção em sistemas empresariais, onde a reutilização de componentes é vital para a rentabilidade do projeto

---

# PARTE 4 – MERCADO DE TRABALHO PARA DESENVOLVEDORES JAVA

  O mercado Java é caracterizado pela sua "perenidade". Enquanto linguagens da moda surgem e desaparecem, o Java mantém-se como a escolha de confiança para infraestruturas críticas, garantindo uma carreira estável e com alta valorização salarial.
  
## Panorama Salarial (Referência Brasil)

- Desenvolvedor Júnior: R $4.000,00–R $6.500,00
- Desenvolvedor Pleno: R $7.000,00–R $12.000,00
- Desenvolvedor Sênior: R $13.000,00–R $20.000,00+ (podendo exceder este valor em cargos de liderança ou especialistas).
  
## Verticais de Atuação

O Java é predominante onde a falha não é uma opção:

- Sistemas Bancários e Fintechs: Processamento de milhões de transações com alta segurança.
- Aplicações Web (Backend): Microsserviços escaláveis para plataformas de streaming e e-commerce.
- Big Data: Ecossistemas como Apache Spark e Hadoop operam sobre a JVM.
Desenvolvimento Android: Camada de APIs nativas para o sistema mobile mais usado do mundo.
- Sistemas Corporativos (ERP): Gestão de recursos para as maiores empresas do mundo.
  
## Stack Tecnológico Indispensável

- Spring Boot: O padrão de facto para microsserviços.
- Hibernate: Para persistência de dados e mapeamento objeto-relacional.
- Maven/Gradle: Gestão profissional de dependências e automação de builds.
- JUnit 5: Garantia de qualidade através de testes automatizados.
- Docker: Contentorização para ambientes de Cloud modernos.

Para ser competitivo, o profissional deve dominar

---

# CONCLUSÃO
  
  O Java continua a ser a escolha das empresas da Fortune 500 devido à sua previsibilidade e ao vasto ecossistema de bibliotecas maduras. Para o desenvolvedor, investir em Java não é apenas aprender uma linguagem, mas integrar-se numa infraestrutura tecnológica que sustenta a economia digital global. O futuro aponta para uma convergência cada vez maior com ambientes Cloud Native, exigindo que o profissional Java seja, acima de tudo, um Engenheiro de Software completo.



























