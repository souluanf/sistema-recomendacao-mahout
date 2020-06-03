<div align="center">
<a href="https://www.apache.org/" target="_blank">
    <img src="https://mahout.apache.org/assets/asf_logo_white.svg" height="100px" alt="PlanD"/>
</a>

<h2>Sistema de Recomendação com Apache Mahout</h2>

<a href="https://www.oracle.com/br/java/technologies/javase-downloads.html" target="_blank">
  <img src="https://img.shields.io/badge/devel-Java-brightgreen" alt="Java"/>
</a>

<a href="https://mahout.apache.org/" target="_blank">
  <img src="https://img.shields.io/badge/library-Apache Mahout-brightgreen" alt="Django"/>
</a>

<a href="https://maven.apache.org/" target="_blank">
  <img src="https://img.shields.io/badge/package management-Maven-brightgreen" alt="Django"/>
</a>

<a href="https://opensource.org/licenses/MIT" target="_blank">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="MIT"/>
</a>

</div>

## Execução

#### Configuração inicial do Maven

No diretório em que deseja criar o projeto, execute o seguinte comando (no terminal):

```bash
mvn archetype:generate -DgroupId=dev.luanfernandes -DartifactId=sistema-de-recomendacao-java-mahout -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```


##### Onde:

- ```mvn archetype: generate ``` - cria projeto

- ```GroupId ``` - identificação do grupo do projeto, por convenção, inciamos com nomedopais.com.nomedaorganização

- ```ArtifactId ``` - nome do projeto

- ```arc hetypeArtifactId ``` - tipo de configuração inicial do projeto, no caso o quickstart usa configurações default.


Se o seu prompt não reconhecer o comando mvn, devemos adicioná-lo no PATH:

```bash
PATH=$PATH:onde_esta_o_bin_do_maven
```

E tente executar o comando para gerar o projeto novamente.#### Requirements
- All API responses must be JSON
- Provide a README.md file with usage instructions (how to run, endpoints etc)
- Provide a testing environment (heroku, docker, etc)

___
### Ambiente de Desenvolvimento

<table>
    <thead>
        <tr class="table100-head">
            <th class="column1">Resource</th>
            <th class="column2">Description</th>
            <th class="column3">Version</th>
        </tr>
    </thead>
    <tbody>
            <tr>
                <td class="column1">Laptop</td>
                <td class="column2">16 GB Memory</td>
                <td class="column3">I7 G7</td>
            </tr>
            <tr>
                <td class="column1">Operating System</td>
                <td class="column2">Ubuntu LTS</td>
                <td class="column3">18.04.2</td>
            </tr>
            <tr>
                <td class="column1">Editor/IDE</td>
                <td class="column2">IntelliJ IDEIA</td>
                <td class="column3">2020.1</td>
            </tr>
            <tr>
                <td class="column1">Graphics Card</td>
                <td class="column2">nVidia GM107 </td>
                <td class="column3">GeForce 940MX</td>
            </tr>
            <tr>
                <td class="column1">Devel</td>
                <td class="column2">Java</td>
                <td class="column3">JDK 14</td>
            </tr>
    </tbody>
</table>
