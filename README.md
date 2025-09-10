# 📘 Lộ trình học C# toàn diện

## 🚀 Giới thiệu
C# là ngôn ngữ lập trình hiện đại, mạnh mẽ do Microsoft phát triển, chạy trên nền tảng **.NET**. Với C#, bạn có thể phát triển:
- Ứng dụng **Desktop (WinForms, WPF, MAUI)**
- Ứng dụng **Web (ASP.NET Core)**
- Ứng dụng **Mobile (Xamarin, MAUI)**
- **Game (Unity)**

Repo này là lộ trình học C# chi tiết, từ cơ bản đến nâng cao, kèm theo tài liệu, dự án mẫu và phân tích điểm mạnh của C#.

---

## 🗂️ Mục lục
1. [C# có thể làm gì?](#-c-có-thể-làm-gì)
2. [C# mạnh nhất ở đâu?](#-c-mạnh-nhất-ở-đâu)
3. [Cài đặt môi trường](#-cài-đặt-môi-trường)
4. [Cơ bản](#-cơ-bản)
5. [OOP trong C#](#-oop-trong-c)
6. [Nâng cao](#-nâng-cao)
7. [Ứng dụng thực tế](#-ứng-dụng-thực-tế)
8. [Dự án mẫu](#-dự-án-mẫu)
9. [Bảng tiến độ học tập](#-bảng-tiến-độ-học-tập)
10. [Tài liệu tham khảo](#-tài-liệu-tham-khảo)

---

## 🌍 C# có thể làm gì?
C# là ngôn ngữ đa năng, chạy trên **.NET**, có thể phát triển:

- **Ứng dụng Desktop**: WinForms, WPF, MAUI.
- **Ứng dụng Web**: ASP.NET Core (MVC, Web API, Blazor).
- **Game**: Unity Engine (hầu hết code gameplay bằng C#).
- **Mobile App**: Xamarin / .NET MAUI (Android + iOS).
- **Cloud & Microservices**: Azure Functions, Web API.
- **AI, ML, IoT**: thông qua ML.NET hoặc tích hợp thư viện khác.
- **Automation & Tooling**: viết script, CLI tool, tự động hóa.

---

## 💪 C# mạnh nhất ở đâu?

1. **Game Development** 🎮  
   Unity là engine game top đầu thế giới (Genshin Impact, Cuphead, Ori, Hollow Knight…) → tất cả code gameplay bằng **C#**. Đây là điểm **C# độc quyền áp đảo**.

2. **Ứng dụng Enterprise & Web Backend** 🏢  
   ASP.NET Core có **hiệu năng cực cao**, bảo mật tốt, được doanh nghiệp lớn tin dùng (ERP, CRM, hệ thống quản lý).

3. **Desktop Application** 💻  
   WinForms, WPF, MAUI → phát triển app desktop nhanh chóng, tích hợp UI + backend trong cùng 1 ngôn ngữ.

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

## 📊 Bảng tiến độ học tập

- [ ] Cài đặt môi trường
- [ ] Biến & Kiểu dữ liệu
- [ ] Toán tử & Cấu trúc lặp
- [ ] Hàm & Collection
- [ ] OOP cơ bản
- [ ] OOP nâng cao
- [ ] Interface & Abstract
- [ ] Delegate & Event
- [ ] LINQ
- [ ] Async/Await & File I/O
- [ ] Dự án nhỏ
- [ ] Hướng chuyên sâu

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
