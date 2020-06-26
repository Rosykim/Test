package day01;

public class Hello1 {

	public static void main(String[] args) {
		System.out.println("문자열 출력");
		System.out.println("A");
		System.out.println("ABC");
		System.out.println(1);//숫자는 " 안해도 출력 가능
		System.out.println("1");
		System.out.println(1+2);// (결과)3
		System.out.println("1"+"2");//""와 + 연산자는 두 수의 병렬
		System.out.println("저의 나이는 26살입니다.");
		System.out.println("저의 나이는 " + 26+"살입니다.");
		int age =26;//한줄위에 변수에 대한 선언문; 
		System.out.println("저의 나이는 " + age +"살입니다.");
		age=20;//변수의 대입문 = means store , equal표시는 ==
		System.out.println("저의 나이는 " + age +"살입니다.");
		age= age + 1;//default에서 increment 표현법
		//age+=1;
		//age++;
		System.out.println("저의 나이는 " + age +"살입니다.");
	}

}

