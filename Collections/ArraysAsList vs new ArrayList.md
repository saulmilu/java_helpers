Arrays.asList vs new ArrayList()
https://www.baeldung.com/java-arrays-aslist-vs-new-arraylist

Resusmo:
Arrays.asList
- não gera novo area de memória apenas referenciando a que previamente existe
- por isso, não permite modificação do tamanho da estrutura

new ArrayList
- cria um novo conteudo em memória
- permite qualquer manipulação sobre a estrutura
