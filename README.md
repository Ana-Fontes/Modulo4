import javax.swing.*;
import java.awt.*;

public class Exercicio1A extends JFrame {

    public Exercicio1A() {
        setTitle("Teste");
        setSize(400, 250);
        setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

        setLayout(new FlowLayout(FlowLayout.LEFT));

        add(new JButton("Um"));
        add(new JButton("Dois"));
        add(new JButton("Três"));
        add(new JButton("Quatro"));

        setVisible(true);
    }

    public static void main(String[] args) {
        new Exercicio1A();
    }
}
