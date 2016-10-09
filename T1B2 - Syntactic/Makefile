all:
	javacc ParserBC.jj
	javac *.java
	jar cfe bc.jar ParserBC *.class
run:
	java -jar bc.jar < in.bc
clean:
	rm -f *.java
	rm -f *.class
