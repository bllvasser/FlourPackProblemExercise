# FlourPackProblemExercise
public class Main {

    public static void main(String[] args) {

        System.out.println(canPack(2,2,11));


    }
    public static boolean canPack(int bigCount, int smallCount, int goal){

        if((bigCount >=0) && (smallCount >=0) && (goal > 0) && (bigCount * 5 + smallCount >= goal)) {
            return smallCount >= goal %5;
        }
        return false;
    }
}
"C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=50362:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\ForLoopExercises\out\production\ForLoopExercises academy.learnprogrmming.Main
true

Process finished with exit code 0
