# Giới thiệu chương trình đặt mua trước khóa học Next.js Super

Khóa học gồm 2 phần:

1. Next.js 14 cơ bản: Học cơ bản lý thuyết và xây dựng 1 web CRUD có Authentication Session Based Token. Độ dài 15 giờ, phần này đã quay xong 100%. Mua xong học được luôn.

2. Dự án quản lý quán ăn bằng Next.Js FrontEnd và Fastify BackEnd (mình cung cấp full source code API, có thể code thêm tính năng) => Đang quay

## Giá khóa học

Chương trình Pre-order, kéo dài từ 15/5 - 30/6, giá sẽ tăng dần theo thời gian

- GD 1: 15/5 - 31/5 (hoặc 500 bạn đầu tiên, tùy điều kiện nào đến trước): 990k
- GD 2: 1/6 (hoặc kết thúc giai đoạn 1) - 10/6: 1090k
- GD 3: 11/6 - 20/6: 1190k
- GD 4: 21/6 - 30/6: 1290k

Giá chính thức:

- GD 5: Từ ngày 1/7 giá khóa học sẽ là 1590k

Học viên cũ áp dụng Voucher: `HOCVIENSUPER` giảm được 100k

## Roadmap

- ✅ NextJs Cơ bản: 15 giờ
- ⏰ Dự án quản lý quán ăn: dự kiến 40 giờ (dự kiến hoàn thành vào tháng 7, 8). Các video sẽ được cập nhật liên tục

## Yêu cầu kiến thức trước khi mua khóa này

- Kiến thức JavaScript: Callback, Promise, Async/Await, fetch API
- Đã học qua ReactJS và TypeScript: Context API, useState, useEffect, React Router, memo
- Biết Node.Js là một lợi thế (không biết cũng không sao, vì đây là khóa FrontEnd)

> Nếu muốn học thêm về React.js và Node.js thì có thể tham khảo các khóa học của mình.

## Target khi học xong khóa này

- Có 1 dự án độc lạ, full stack từ FrontEnd đến BackEnd. Đủ để các bạn dùng làm **Đồ án tốt nghiệp** hoặc bỏ vào **Portfolio** để xin việc. Có thể phát triển thêm tính năng để làm sản phẩm thương mại.

Về kiến thức Next.js

- Routing: Route Group, Dynamic Route ,Parallel Routes, Route Handlers, Middleware

- Data Fetching: Server component (Data Fetching, Caching, and Revalidating), Client component (Tanstack Query)

- Rendering: Static Rendering, Dynamic Rendering (ở server và client), Incremental Static Regeneration

- Cơ chế Caching

- Optimizing: Ảnh, font, Bundle, Lazyload,...

- SEO: Đưa web lên Google Search, tối ưu LightHouse, Chuẩn hóa Open Graph để đăng lên facebook, twitter

- Authentication: Không dạy về NextJs Auth, JWT Access Token, Refresh Token, Cookie, Role Based Authentication, Social Login

## Ý tưởng

Mình lấy ý tưởng từ phần mêm Sapo FNB: [QR Order trên Sapo FNB | Giải pháp gọi món tại bàn giúp quán tiết kiệm tối đa nguồn nhân lực](https://youtu.be/m8gCGGinoAs)

Mình sẽ đi chi tiết vào dự án quản lý quán ăn

## Công nghệ sử dụng

- FrontEnd: Next.js 14 App Router, TypeScript, TailwindCSS, ShadCn UI, Tanstack Query, WebSockets (Socket.io)
- BackEnd **(hosting local)**: Fastify, Prisma, TypeScript, JWT, WebSockets (Socket.io)
- Database: SQL Lite

## Chức năng chính dự án

- Quản lý authentication bằng JWT Access Token và Refresh Token
- Có phân quyền 3 role: Admin, Nhân viên, Khách hàng

Admin

- Quản lý tài khoản cá nhân
- Quản lý nhân viên
- Quản lý món ăn
- Quản lý bàn ăn
- Quản lý hóa đơn gọi món
- Thống kê doanh thu

Nhân viên

- Quản lý tài khoản cá nhân
- Quản lý hóa đơn gọi món
- Thống kê doanh thu

Khách hàng

- Xem menu
- Đặt món ăn bằng QR Code

## Vấn đề bản quyền

- Mỗi 1 học viên chỉ được dùng 1 tài khoản để học, nền tảng mình hạn chế đăng nhập trên nhiều thiết bị. Cũng như các bạn sẽ bị mất các quyền lợi nếu chia sẻ tài khoản cho người khác

- Nếu bạn mua từ một bên thứ 3, bạn sẽ không được join github hay các group hỗ trợ của mình. Dự án luôn có thay đổi và bạn sẽ không thể biết được những thay đổi đó

- Trong khóa này mình sẽ xen kẽ các video bí mật vào, chỉ những bạn mua khóa học, xem kĩ video mới biết được những nội dung đó, còn những ai tải khóa về và bán lại sẽ không biết được => Người mua lậu sẽ không học được

## Hỗ trợ khi học

- Mình có các group hỗ trợ trên Facebook và Telegram, nếu học viên gặp khó khăn có thể hỏi mình trên các group này

- Không nên inbox trực tiếp cho mình nhờ fix bug hộ, nếu gặp vấn đề gì khi học hãy hỏi trên group, nếu bug fix mãi k được thì đăng bài lên group facebook giúp mình.
