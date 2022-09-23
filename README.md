# Banco_de_Dados
Conceitos, definição e insight
Banco de Dados 
SQL e NOSQL

1 – Conceito de Banco de Dados
“O principio básico de um Banco de Dados é armazenar informações de um sistema.”
1.1.	Banco de Dados Relacional
Um banco de dados relacional é um tipo de banco de dados que armazena e fornece acesso a pontos de dados relacionados entre si. Bancos de dados relacionais são baseados no modelo relacional, uma maneira intuitiva e direta de representar dados em tabelas. 

MySQL: O banco de dados SQL relacional

Os benefícios e pontos fortes do MySQL são:

Maturidade. O MySQL é uma base de dados extremamente estabelecida, o que significa que há uma grande comunidade por trás, testes extensos e muita estabilidade.

Compatibilidade. O MySQL está disponível para todas as plataformas mais utilizadas, inclusive Linux, Windows, Mac, BSD e Solaris. Ele também tem conectores para linguagens como Node.js, Ruby, C#, C++, Java, Perl, Python e PHP, então não está limitado à linguagem de consulta SQL.

Custo-benefício. A base de dados é open source e gratuita.

Replicável. A base de dados MySQL pode ser replicada através de vários nós, significando que a carga de trabalho pode ser reduzida e a escalabilidade e disponibilidade da aplicação podem ser aumentadas.

Sharding. Apesar do sharding (termo comum das bases de dados não-relacionais que significa divisão de dados entre vários servidores) não poder ser feito na maioria das bases de dados SQL, ele pode ser feito em servidores MySQL. Isso é tanto economicamente viável quanto bom para a empresa.



1.2.	Banco de Dados Não relacional.
Um banco de dados não relacional é um banco de dados que não usa o esquema de tabela de linhas e colunas encontrado na maioria dos sistemas de banco de dados tradicionais. Em vez disso, os bancos de dados não relacionais usam um modelo de armazenamento otimizado para os requisitos específicos do tipo de dados que está sendo armazenado. Por exemplo, os dados podem ser armazenados como pares chave/valor simples, como documentos JSON ou como um gráfico que consiste em bordas e vértices.

MongoDB: O banco de dados NoSQL não-relacional
Os benefícios e pontos fortes do MongoDB são:
Esquema dinâmico. Como mencionado, isso te dá flexibilidade para mudar seu esquema de dados sem modificar nenhum outro dado existente.
Escalabilidade. O MongoDB é horizontalmente escalável, o que ajuda a reduzir a carga de trabalho e escalar seu negócio com facilidade.
Gerenciamento. A base de dados não requer um administrador. Isso facilita o uso do sistema, já que ele pode ser usado tanto pelos desenvolvedores quanto administradores.
Velocidade. Tem performance alta para consultas simples.
Flexibilidade. Você pode adicionar novas colunas e campos no MongoDB sem afetar as colunas existentes nem a performance da aplicação.




Desafio 
As organizações têm acesso a muitos novos tipos de dados e fontes de dados hoje. Dados de sensor de máquina, conteúdo de Mídias social e texto e vídeo de tamanho variável são alguns exemplos. Todos esses dados diferem das fontes tradicionais, por exemplo, dados financeiros ou ERP, pois nem sempre seguem uma estrutura ou esquema consistente (certos campos podem aparecer em determinados registros e não aparecer em outros) e, portanto, não se prestam naturalmente para o formato tabular tradicional.
No entanto, esses novos dados também refletem a realidade dos negócios de uma forma que os dados convencionais e estruturados não conseguem. Naturalmente, os usuários de negócios desejam insights acionáveis para seus negócios a partir desses novos dados. Além disso, os usuários não técnicos querem poder consultar os dados da maneira que quiserem, ou seja, possibilidades de consulta com flexibilidade e agilidade incorporadas – ou seja, o tipo de funcionalidade que o software moderno de análise e relatórios de negócios deve fornecer.
Os bancos de dados NoSQL continuarão a fazer parte da solução para extrair informações significativas dos vastos recursos de dados não estruturados, devido à facilidade de captura desses dados. Além disso, os desenvolvedores que viram como é fácil desenvolver aplicativos nesses bancos de dados vão querer continuar usando-os. O desafio é, portanto, construir soluções analíticas adequadas sobre bancos de dados NoSQL, em vez de tentar encaixar big data em bancos de dados SQL, mesmo que a funcionalidade analítica já esteja disponível para o último.
