# 부산대학교 K-Digital 2기
### Project_Java_03_Exception

```java
public static void main(){
  try(ClassType cls = new ClassType()){
    // try(...) 형태는 반드시 선언되지 않아도 무관함. 해당 형태로 생성된 cls instance는 try를 벗어나면 소멸한다.
  } catch(Exception e){
    // Exception case에서 실행되는 구문.
    e.getMessage();       // try에서 발생한 Exception Message를 Return <String>.
    e.printStackTrace();  // try에서 발생한 Exception Case를 Return.
    e.toString();
  } finally {
    // try 또는 catch Body 실행 후 최종적으로 실행되는 구문.
    // try 또는 catch에서 return 문을 만나더라도 finally 문은 return 전에 반드시 실행된다는 특징을 가지고 있음.
  }
  
#####  // 주요 사용 Method();
  
}
```
