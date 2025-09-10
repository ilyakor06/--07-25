Илья Коростелёв ЭФБО-07-25
Python:
Массив:
ls = [54, 142, 152, 164, 555]
print(ls)
Стек:
st=[]
st.append(40)# [40]
st.append(42)# [40,42]
st.append(52)# [40,42,52]

print(st.pop())# 52 [40,42]
java:
Массив:
int[] myArray; // объявление массива
myArray = new int[10]; // создание, то есть, выделение памяти для массива на 10 элементов типа int
Стек:
package Edureka;
import java.util.EmptyStackException;
import java.util.Stack;
public class StackOperations {  
public static void main (String[] args) 
{ 
    Stack stack = new Stack();
    stack.push("1");
    stack.push("2");
    stack.push("3");
    // Check if the Stack is empty
            System.out.println("Is the Java Stack empty? " + stack.isEmpty());
    // Find the size of Stack
            System.out.println("Size of Stack : " + stack.size());
    }
} 
c++:
Массив:
#include <iostream>
 
int main()
{
    int numbers[4]{1,2,3,4};
    int first = numbers[0];     // получаем первый элемент
    std::cout << first << std::endl;    // 1
    numbers[0] = 34;                    / изменяем значение элемента
    std::cout << numbers[0] << std::endl; // 34
}
Стек:
#include <iostream>
#include <stack>
 
int main()
{
    std::stack<std::string> stack;    // пустой стек строк
}
В C++ и Java, в отличие от Python, массив не может менять размер, и размер пишется при объявлении массива.
В C++ и Java, в отличие от Python, массив не может содержать элементы разных типов, и тип элементов пишется при объявлении массива.

В Python стек представлен с помощью массива.
В C++ для работы со стеком нужно подключать заголовочный файл.