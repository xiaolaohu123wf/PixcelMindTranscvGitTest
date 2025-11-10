# PixcelMindTranscvGitTest
学习git操作


## 成员

|名称|生日|
|-|-|
|王文斐|020618|
|杨咏涵|*041105*|
|秦智健|**030915**|
|擢升于|040310|
|张子珺|**040713**|

### 基础用法

> 核心思想：GPL 的约束并非为了限制自由，而是通过法律工具来捍卫和扩展自由。它确保任何从自由软件中受益的衍生作品，也必须同样自由，从而形成一个不断增长的软件公地。对于开发者来说，在使用 GPL 软件前，务必理解其“传染性”条款，并评估它是否与你项目的商业模式和许可证策略兼容。

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
---
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
这个游戏非常好玩
![项目截图](https://picb1.photophoto.cn/18/430/18430591_1.jpg)