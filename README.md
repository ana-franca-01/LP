**questao 1**

**questao 2**
**questao 3**
**questao 4**
**questao 5**
**questao 6**
**questao 7**
**questao 8**

código quest.2
package org.example;

public class Coracao {
    private int intensidadeSentimento;
    private boolean ferido;
    private boolean desejaAmor;

    public Coracao(int intensidadeSentimento, boolean ferido) {
        this.intensidadeSentimento = intensidadeSentimento;
        this.ferido = ferido;
        this.desejaAmor = false;
    }

    public int getIntensidadeSentimento() {
        return intensidadeSentimento;
    }
    public void setIntensidadeSentimento(int intensidadeSentimento) {
        this.intensidadeSentimento = intensidadeSentimento;
    }

    public boolean isFerido() {
        return ferido;

    }
    public void setFerido(boolean ferido) {
        this.ferido = ferido;
    }

    public boolean isDesejaAmor() {
        return desejaAmor;
    }

    public void setDesejaAmor(boolean desejaAmor) {
        this.desejaAmor = desejaAmor;
    }

    public void bater{
        System.out.println("O coração bate masi forte");
    }

package org.example;

public class Palavra {
    private String texto;
    private boolean verdadeiro;
    private int repetida;

    public Palavra(String texto, boolean verdadeiro, int repetida) {
        this.tetxo = texto;
        this.verdadeiro = verdadeiro;
        this.repetida = repetida;
    }
    public String getTexto() {
        return texto;
    }
    public void setTexto(String texto) {
        this.tetxo = texto;
    }
    public boolean isVerdadeiro() {
        return verdadeiro;
    }
    public void setVerdadeiro(boolean verdadeiro) {
        this.verdadeiro = verdadeiro;
    }
    public int getRepetida() {
        return repetida;
    }

    public void setRepetida(int repetida) {
        this.repetida = repetida;
    }

    public void dizer{
        System.out.println("palavra dita" + texto);
    }
}


package org.example;

public class Mentira {
    private String palavras;
    private int itesnsidade;
    private boolean descoberta;

    public Mentira(String palavras, int itesnsidade,  boolean descoberta) {
        this.palavras = palavras;
        this.itesnsidade = itesnsidade;
        this.descoberta = false;
    }
    public String getPalavras() {
        return palavras;
    }
    public void setPalavras(String palavras) {
        this.palavras = palavras;
    }
    public int getItesnsidade() {
        return itesnsidade;
    }
    public void setItesnsidade(int itesnsidade) {
        this.itesnsidade = itesnsidade;
    }
    public boolean isDescoberta() {
        return descoberta;
    }
    public void setDescoberta(boolean descoberta) {
        this.descoberta = descoberta;
    }
    public String esconderVerdade() {
        if (!descoberta) {
            return "A mentira esconde a verdade dizendo: " + palavras;
        } else {
            return "A verdade veio à tona. A mentira foi descoberta!";
        }
    }

}


código quest.3

}

