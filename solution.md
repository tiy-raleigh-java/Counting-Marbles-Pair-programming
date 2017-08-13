```java
public class MarbleBag {

    int numRedMarbles;
    int numGreenMarbles;
    int numBlueMarbles;

    public MarbleBag(int numRedMarbles, int numGreenMarbles, int numBlueMarbles) {
        this.numRedMarbles = numRedMarbles;
        this.numGreenMarbles = numGreenMarbles;
        this.numBlueMarbles = numBlueMarbles;
    }

    public int getTotalNumberOfMarbles () {
        return numBlueMarbles + numRedMarbles + numGreenMarbles;
    }

    public void printInfo () {
        System.out.println("Red: " + numRedMarbles);
        System.out.println("Green: " + numGreenMarbles);
        System.out.println("Blue: " + numBlueMarbles);
        System.out.println("Total: " + getTotalNumberOfMarbles());
    }

    public void removeAllRedMarbles () {
        numRedMarbles = 0;
    }

    public void removeAllGreenMarbles () {
        numGreenMarbles = 0;
    }

    public void removeAllBlueMarbles () {
        numBlueMarbles = 0;
    }
}
```
