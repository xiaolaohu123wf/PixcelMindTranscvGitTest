以下是简单的 Python 和 Java 代码示例：

## Python 示例

```python
# 定义一个简单的类
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def introduce(self):
        return f"你好，我叫{self.name}，今年{self.age}岁"

# 函数示例
def calculate_sum(a, b):
    """计算两个数的和"""
    return a + b

# 主程序
if __name__ == "__main__":
    # 创建对象
    person = Person("张三", 25)
    
    # 调用方法
    print(person.introduce())
    
    # 调用函数
    result = calculate_sum(10, 20)
    print(f"10 + 20 = {result}")
    
    # 列表操作
    numbers = [1, 2, 3, 4, 5]
    squares = [x**2 for x in numbers]
    print(f"数字: {numbers}")
    print(f"平方: {squares}")
```

## Java 示例

```java
// 主类
public class SimpleExample {
    // 属性
    private String name;
    private int age;
    
    // 构造方法
    public SimpleExample(String name, int age) {
        this.name = name;
        this.age = age;
    }
    
    // 方法：自我介绍
    public String introduce() {
        return "你好，我叫" + name + "，今年" + age + "岁";
    }
    
    // 静态方法：计算和
    public static int calculateSum(int a, int b) {
        return a + b;
    }
    
    // 主方法
    public static void main(String[] args) {
        // 创建对象
        SimpleExample example = new SimpleExample("李四", 30);
        
        // 调用方法
        System.out.println(example.introduce());
        
        // 调用静态方法
        int result = calculateSum(15, 25);
        System.out.println("15 + 25 = " + result);
        
        // 数组操作
        int[] numbers = {1, 2, 3, 4, 5};
        System.out.print("数字: ");
        for (int num : numbers) {
            System.out.print(num + " ");
        }
        System.out.println();
    }
}
```

## 两个语言的主要区别：

1. **语法**：Python 更简洁，Java 需要分号和花括号
2. **类型**：Python 是动态类型，Java 是静态类型
3. **类定义**：Python 使用 `class` 关键字，Java 需要 `public class`
4. **主程序**：Python 用 `if __name__ == "__main__"`，Java 用 `public static void main`
5. **输出**：Python 用 `print()`，Java 用 `System.out.println()`

这两个示例都展示了面向对象编程的基本概念：类、对象、方法和基本操作。