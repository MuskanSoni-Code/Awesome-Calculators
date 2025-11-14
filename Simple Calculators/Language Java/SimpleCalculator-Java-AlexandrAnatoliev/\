import org.junit.jupiter.api.*;
import static org.junit.jupiter.api.Assertions.*;

public class CalculatorTest {

    @Test
    void testAdd2and3return5() {
        Calculator calculator = new Calculator(2,3);
        long answer = calculator.add();
        long expectedAnswer = 5;
        assertEquals(expectedAnswer, answer);
    }

    @Test
    void testSub5and3return2() {
        Calculator calculator = new Calculator(5,3);
        long answer = calculator.sub();
        long expectedAnswer = 2;
        assertEquals(expectedAnswer, answer);
    }

    @Test
    void testMult5and3return15() {
        Calculator calculator = new Calculator(5,3);
        long answer = calculator.mult();
        long expectedAnswer = 15; 
        assertEquals(expectedAnswer, answer);
    }

    @Test
    void testDiv3and5return06() {
        Calculator calculator = new Calculator(3,5);
        double answer = calculator.div();
        double expectedAnswer = 0.6; 
        assertEquals(expectedAnswer, answer);
    }
}
