# LinQ, EntityFramework, Technics, và ABP Framework

## 1. Một số kiến thức LinQ đã học ở tháng trước chưa review:

- **Linq to mem**
  - Tìm hiểu về `yeild`, `IQueryable` và `IEnumerable` + `IEnumerator`, khác biệt giữa `IQueryable` và `IEnumerable`.
- **Linq to xml**
  - Tạo `XDocument`, thao tác LinQ trên `XDocument`, sử dụng LinQ thêm, sửa, xóa các phần tử của `XDocument` và lưu nó dưới dạng XML hoặc HTML.
- **Thực hiện viết LinQ với 2 cách là sử dụng query syntax hoặc method syntax**
  - [Git](https://github.com/longdmhe161226/LinQ)

## 2. EntityFramework

- Học về thư viện EF cơ bản, cấu hình và map data, `DbSet<Entity>`, `DBContext`, thao tác DB dùng model DB first.
- Học về Migration, hiểu về từng file của migration tạo ra, workflow của các lệnh thêm sửa xóa migration, code demo Migration.
  - [Git](https://github.com/longdmhe161226/EntityFramwork)

## 3. Technics

- Học về Web APIs, tạo một API cơ bản, học về Attribute Routing.
- Học JWT, hiểu rõ các thành phân của token, hiểu workflow của 2 trường hợp standard nhất là: Author và Info exchange, Code Demo Author sử dụng JWT.
- Học Identity, hiểu rõ các thành phần bảng của Identity, custom Identity, Code Demo sử dụng Identity.
- Code Demo kết hợp sử dụng JWT và Identity để Author trong 1 project.
  - [Git](https://github.com/longdmhe161226/Technics)

## 4. ABP Framework

- Học về Clean Architecture và phương pháp Domain Driven Design (DDD), Permission, Code Demo Project Nolayer basic, Project Layered basic, Project BookStore (ASP.NET Core MVC & EF Core) hoàn thiện.
  - [Git 1](https://github.com/longdmhe161226/ABPs)
  - [Git 2](https://github.com/longdmhe161226/ABP)

**Điểm yếu:** Architecture mới phân nhiều layered nên vẫn còn rối chưa quen và chưa làm chủ được framework.

**Mục tiêu đề ra để khắc phục:** Tìm hiểu thêm về cách ABP sử dụng cùng với JWT và thực hiện trên các project ABP mới (sử dụng Angular & EF Core) và (web app sử dụng React).
