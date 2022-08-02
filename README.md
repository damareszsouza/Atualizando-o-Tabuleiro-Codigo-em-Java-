# Atualizando-o-Tabuleiro-Codigo-em-Java-


Atualizando o Tabuleiro
O último método que devemos implementar é o método atualizaTabuleiro. Este método deve preencher as lacunas do tabuleiro nas posições onde a letra for encontrada na palavra. Mais uma vez deveremos percorrer o vetor da palavra e verificar onde a letra será encontrada, preenchendo as respectivas posições do tabuleiro com a própria letra (lembre-se que o tabuleiro vai revelando a palavra aos poucos). Assim, obtemos o código mostrado abaixo.



static void atualizaTabuleiro(char[] tabuleiro, char[] palavra, char letra) {

       for(int cont = 0; cont < palavra.length; cont++) {

             if(palavra[cont] == letra)

                    tabuleiro[cont] = letra;

       }

}


Para finalizar, lembre-se que os métodos mostrados devem ser incluídos ao código da classe JogoDaForca. Os métodos devem ser inseridos fora do método main, antes ou após ele.
