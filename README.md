# 📘 Lộ trình học C# toàn diện

## 🚀 Giới thiệu
C# là ngôn ngữ lập trình hiện đại, mạnh mẽ do Microsoft phát triển, chạy trên nền tảng **.NET**. Với C#, bạn có thể phát triển:
- Ứng dụng **Desktop (WinForms, WPF)**
- Ứng dụng **Web (ASP.NET Core)**
- Ứng dụng **Mobile (Xamarin, MAUI)**
- **Game (Unity)**

Repo này là lộ trình học C# chi tiết, từ cơ bản đến nâng cao, kèm theo tài liệu, dự án mẫu và bảng theo dõi tiến độ học.

---

## 🗂️ Mục lục
1. [Cài đặt môi trường](#-cài-đặt-môi-trường)
2. [Cơ bản](#-cơ-bản)
3. [OOP trong C#](#-oop-trong-c)
4. [Nâng cao](#-nâng-cao)
5. [Ứng dụng thực tế](#-ứng-dụng-thực-tế)
6. [Dự án mẫu](#-dự-án-mẫu)
7. [Ví dụ code](#-ví-dụ-code)
8. [Bảng tiến độ học tập](#-bảng-tiến-độ-học-tập)
9. [Tài liệu tham khảo](#-tài-liệu-tham-khảo)

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

---

## 📊 Bảng tiến độ học tập
Đại ka có thể tick ✅ khi hoàn thành từng mục.

| STT | Chủ đề                  | Nội dung chính                          | Hoàn thành |
|-----|--------------------------|-----------------------------------------|-------------|
| 1   | Cài đặt môi trường       | Visual Studio / VS Code, .NET SDK       | ⬜ |
| 2   | Biến & Kiểu dữ liệu      | int, string, bool, double, var, dynamic | ⬜ |
| 3   | Toán tử & Cấu trúc lặp   | if, switch, for, while, foreach         | ⬜ |
| 4   | Hàm & Collection         | Method, Array, List, Dictionary         | ⬜ |
| 5   | OOP cơ bản               | Class, Object, Encapsulation            | ⬜ |
| 6   | OOP nâng cao             | Inheritance, Polymorphism, Abstraction  | ⬜ |
| 7   | Interface & Abstract     | get; set;, interface, abstract class    | ⬜ |
| 8   | Delegate & Event         | Delegate, Event, Lambda                 | ⬜ |
| 9   | LINQ                     | Query dữ liệu                           | ⬜ |
| 10  | Async/Await & File I/O   | Bất đồng bộ, đọc/ghi file               | ⬜ |
| 11  | Dự án nhỏ                | Quản lý SV / ToDo App                   | ⬜ |
| 12  | Hướng chuyên sâu         | Web / Desktop / Game / Mobile           | ⬜ |

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
by qngoc
