 # Simple Calculator 

#### Compile Java code
``` 
javac -d bin/main/ src/main/java/*.java    
```

#### Tests

* Compile
```
javac -d bin/test/ -cp "bin/main:/usr/share/java/junit-jupiter-api-5.10.1.jar:/usr/share/java/junit-platform-console-standalone-1.9.1.jar" src/test/java/*.java
```

* Run tests
```
java -cp "bin/main:bin/test:/usr/share/java/junit-jupiter-api-5.10.1.jar:/usr/share/java/junit-platform-console-standalone-1.9.1.jar" org.junit.platform.console.ConsoleLauncher --scan-classpath --class-path bin/test
```
#### Using program
* Move to directory
```
cd bin/main/                                                                                                                
```
* Run program
java Main 2 + 3                                                                                
2 + 3 = 5                                                                                                                                                                       
java Main 6 - 3                                                                                                                                                 
6 - 3 = 3
``` 

* Warning!!! To multiplication use '\*' operator instead '*'
```
java Main 2 \* 4                                                         
2 * 4 = 8
```

#### Files structure

```
SimpleCalculator-Java-AlexandrAnatoliev/
├── bin/
│   ├── main/
│   │   ├── Main.class
│   │   └── Calculator.class
│   └── test/
│       └── CalculatorTest.class
└── src/
    ├── main/
    │   └── java/
    │       ├── Main.java
    │       └── Calculator.java
    └── test/
        └── java/
            └── CalculatorTest.java
```

