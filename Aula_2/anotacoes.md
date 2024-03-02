# Modelagem de Dados
Utilizamos a modelagem para:
* Representar o ambiente observado;
* Fornecer processos de validação;
* Observar processos de relacionamentos entre objetos;
* Documentar.

## MER - Modelo Entidade Relacionamento
* Modelo Conceitual
* Usado para descrever objetos, suas características e como se relacionam.

## DER - Diagrama Entidade Relacionamento
* Representação gráfica do MER;
* Muitas vezes usado como sinônimo;
* Facilita a comunicação entre todos.

## Nomenclatura
#### Entidade (TABELA)
Define qualquer coisa que seja identificável, singular e tenha existência bem delimitada, tais como cidade e estado.

#### Atributo (COLUNA)
* É tudo aquilo que pode relacionar como propriedade da identidade;
* Atomicidade: podem ter valor único ou não (multivalorados);
* Opcional (Null) ou Obrigatório (Not Null).

#### Relacionamento
Descreve um evento significativo que ocorre entre duas entidades.

#### Cardinalidade
Conceitos usado para dizer quantas vezes uma entidade pode se relacionar com outra entidade, também referenciado como "grau de relacionamento".

## Tipos de Modelos de Dados
#### Modelagem de Dados Conceitual
Objetivos:
* Entender os requisitos;
* Representação visual;
* É o que se constrói juntamente com o negócio.

#### Modelagem de Dados Lógica
Objetivos:
* Descrição de como os dados serão armazenados;
* Descrever entidade, atributos, chaves primárias/estrangeiras;
* Relacionamentos;
* Construído com o time de dados baseando-se no modelo conceitual.

#### Modelagem de Dados Física
Objetivos:
* Descrevemos tabelas, colunas e relacionamentos;
* Consta tipagens e características "físicas" dos dados;
* Este é o que o time de dados constrói para colocar a mão na massa.

