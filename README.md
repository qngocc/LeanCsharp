# 📘 Lộ trình học C# toàn diện

## 🚀 Giới thiệu
C# là ngôn ngữ lập trình hiện đại, mạnh mẽ do Microsoft phát triển, chạy trên nền tảng **.NET**. Với C#, bạn có thể phát triển:
- Ứng dụng **Desktop (WinForms, WPF)**
- Ứng dụng **Web (ASP.NET Core)**
- Ứng dụng **Mobile (Xamarin, MAUI)**
- **Game (Unity)**

Repo này là lộ trình học C# chi tiết, từ cơ bản đến nâng cao, kèm theo tài liệu và dự án mẫu.

---

## 🗂️ Mục lục
1. [Cài đặt môi trường](#-cài-đặt-môi-trường)
2. [Cơ bản](#-cơ-bản)
3. [OOP trong C#](#-oop-trong-c)
4. [Nâng cao](#-nâng-cao)
5. [Ứng dụng thực tế](#-ứng-dụng-thực-tế)
6. [Dự án mẫu](#-dự-án-mẫu)
7. [Ví dụ code](#-ví-dụ-code)
8. [Tài liệu tham khảo](#-tài-liệu-tham-khảo)

---

## 💻 Cài đặt môi trường
- Cài **[Visual Studio 2022 Community](https://visualstudio.microsoft.com/)**
- Hoặc **[Visual Studio Code](https://code.visualstudio.com/)** + C# Extension
- Cài **.NET SDK** (phiên bản mới nhất)

Chạy thử chương trình đầu tiên:
```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, C#!");
    }
}
```

---

## 📕 Cơ bản
✅ Thời gian: 2–3 tuần  
Nội dung:
- Biến & Kiểu dữ liệu (int, string, bool, double, var, dynamic)
- Toán tử (số học, logic, so sánh)
- Cấu trúc điều khiển: `if`, `switch`, `for`, `while`, `foreach`
- Hàm (method)
- Mảng & Collection (Array, List, Dictionary)
- Xử lý chuỗi (`string`, `StringBuilder`)

👉 Bài tập:
- Viết chương trình tính toán (máy tính cơ bản)
- Quản lý danh sách sinh viên bằng `List`

---

## 🧩 OOP trong C#
✅ Thời gian: 3–4 tuần  
Nội dung:
- Class & Object
- Tính chất OOP:
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Abstraction
- Constructor, Destructor
- Interface & Abstract class
- Property (`get; set;`)

👉 Bài tập:
- Xây dựng hệ thống quản lý nhân viên (Employee, Manager, Developer)
- Tạo class `Animal` → kế thừa thành `Dog`, `Cat`

---

## ⚡ Nâng cao
✅ Thời gian: 1–2 tháng  
Nội dung:
- Delegate & Event
- Lambda Expression
- LINQ (query dữ liệu như SQL)
- Generic
- Exception Handling (try-catch-finally)
- Async/Await (bất đồng bộ)
- File I/O (đọc/ghi file)

👉 Bài tập:
- Viết chương trình đọc/ghi dữ liệu từ file CSV
- Tạo ứng dụng quản lý todo-list với LINQ

---

## 🌐 Ứng dụng thực tế
Chọn 1 trong các hướng:

- **Desktop**: WinForms, WPF
- **Web**: ASP.NET Core (MVC, API)
- **Game**: Unity + C#
- **Mobile**: Xamarin / .NET MAUI

---

## 🛠️ Dự án mẫu
- Quản lý sinh viên (WinForms)
- Web API quản lý sản phẩm (ASP.NET Core)
- Game nhỏ (Unity - Pong, Flappy Bird clone)
- Ứng dụng ToDo App (WPF hoặc Console)

---

## 📂 Ví dụ code
Repo sẽ có thư mục `examples/` chứa code mẫu theo từng cấp độ:

```
examples/
├── 01_hello_world/Program.cs
├── 02_calculator/Program.cs
├── 03_student_list/Program.cs
├── 04_oop_animals/Animal.cs, Dog.cs, Cat.cs
├── 05_oop_employees/Employee.cs, Manager.cs, Developer.cs
├── 06_file_io/FileReadWrite.cs
└── 07_linq_todo/TodoApp.cs
```

**01_hello_world/Program.cs**
```csharp
using System;
class Program
{
    static void Main() => Console.WriteLine("Hello, C#!");
}
```

**02_calculator/Program.cs**
```csharp
using System;
class Program
{
    static void Main()
    {
        Console.Write("Nhập a: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Nhập b: ");
        int b = int.Parse(Console.ReadLine());
        Console.WriteLine($"Tổng: {a+b}, Hiệu: {a-b}, Tích: {a*b}, Thương: {(double)a/b}");
    }
}
```

**03_student_list/Program.cs**
```csharp
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        var students = new List<string> {"An", "Bình", "Chi"};
        foreach (var s in students)
            Console.WriteLine($"Sinh viên: {s}");
    }
}
```

**04_oop_animals/Animal.cs**
```csharp
public abstract class Animal
{
    public string Name { get; set; }
    public abstract void Speak();
}
```

**04_oop_animals/Dog.cs**
```csharp
using System;

public class Dog : Animal
{
    public override void Speak() => Console.WriteLine($"{Name} sủa: Gâu Gâu!");
}
```

**04_oop_animals/Cat.cs**
```csharp
using System;

public class Cat : Animal
{
    public override void Speak() => Console.WriteLine($"{Name} kêu: Meo Meo!");
}
```

**05_oop_employees/Employee.cs**
```csharp
public class Employee
{
    public string Name { get; set; }
    public double Salary { get; set; }

    public virtual double GetSalary() => Salary;
}
```

**05_oop_employees/Manager.cs**
```csharp
public class Manager : Employee
{
    public double Bonus { get; set; }
    public override double GetSalary() => Salary + Bonus;
}
```

**05_oop_employees/Developer.cs**
```csharp
public class Developer : Employee
{
    public string ProgrammingLanguage { get; set; }
}
```

**06_file_io/FileReadWrite.cs**
```csharp
using System;
using System.IO;

class FileReadWrite
{
    static void Main()
    {
        string path = "data.txt";
        File.WriteAllText(path, "Xin chào C#!");
        string content = File.ReadAllText(path);
        Console.WriteLine($"Nội dung file: {content}");
    }
}
```

**07_linq_todo/TodoApp.cs**
```csharp
using System;
using System.Collections.Generic;
using System.Linq;

class TodoApp
{
    static void Main()
    {
        var todos = new List<string> {"Học C#", "Làm bài tập", "Viết dự án"};

        var query = from t in todos
                    where t.Contains("Học")
                    select t;

        Console.WriteLine("Công việc cần làm có từ 'Học':");
        foreach (var t in query)
            Console.WriteLine(t);
    }
}
```

---

## 📚 Tài liệu tham khảo
- [Microsoft C# Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [C# Programming Yellow Book – Rob Miles](http://www.csharpcourse.com/)
- [TutorialsTeacher C#](https://www.tutorialsteacher.com/csharp)
- [w3schools C#](https://www.w3schools.com/cs/)

---

## 🎯 Lộ trình đề xuất
1. 2–3 tuần: Học cú pháp cơ bản
2. 3–4 tuần: Nắm OOP
3. 1–2 tháng: Làm dự án nhỏ
4. Sau đó: Chọn hướng chuyên sâu (Web, Desktop, Game, Mobile)

---

👉 Repo này sẽ có thêm thư mục `examples/` chứa code mẫu cho từng phần học.
