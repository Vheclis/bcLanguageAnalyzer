all:
	javacc ParserBC.jj
	javac *.java
	jar cfe bc.jar ParserBC *.class
run:
	java -jar bc.jar < in_default.bc > out_default.txt
clean:
	rm -f *.java
	rm -f *.class
