# Manipulando arquivos em C/C++

# :wave: Manipulaçao de Arquivos binários

## 🤓 Resumo

Objetivo dessa atividade é praticar manipulaçao de arquivos em C++ 🚀

Espera-se que ao final desta atvidade você seja capaz de criar, editar, buscar informaçoes e 
fechar arquivos e compreender os principais conceitos por tras dessas açoes. 

## Atividade :

No repositorio [dcc012-arquivos](https://github.com/ufjf-dcc-josecamata/dcc012-arquivos) 
apresentamos um um pequeno exemplo de manipulação de arquivos binários 
usando a linguagem C. Neste exemplo, manipulamos o cadastro de informações de estudantes
em um arquivo binário.

Nesta atividades, iremos implementar algo semelhante. Desajamos criar um embrião
do nosso sistema SIGA. Nosso projeto está organizado na seguinte estrutura de arquivos:

src
  - [estudante.h](src/estudante.h) e [estudante.cc](src/estudante.cpp) : Implementa a entidade estudante
  - gerencia_siga.h e gerencia_siga.h.cc}: Implementa um sistema de gerenciamento de estudante.
  
test 
  - test1.cc:  Testa a abertura do arquivo.  
  - test2.cc:  Insere dados de estudante no gerencia_siga
  - test3.cc:  Cadastra um novo estudante na base de dados
  - test4.cc:  Pesquisa por um estudante cadastrado.
  - test5.cc:  Altera os dados de cadastro de uma aluno.
  - test6.cc:  Imprime a base de dados em um arquivo texto. 

Detalhes do que deve ser feito encontra-se no arquivos fontes.

### Compilação e Execução: 

Para a compilação em ambiente Unix/linux, use o comando:

 - cmake -B build
 - cmake --build build 
 - ./build/test1
 - ./build/test2
 - etc 

## 📝 Importante

Voce deve implementar uma versão C++ usando fstream

## 📝 Procure saber mais...

* ["Referencia cplusplus"](https://www.cplusplus.com/reference/fstream/fstream/).

* ["Tutorial sobre Arquivos"](https://www.cplusplus.com/reference/fstream/fstream/)



