[Uploading webtest.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Di Động</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Chào mừng đến với Trang Web của Tôi</h1>
        <nav>
            <ul>
                <li><a href="#home">Trang Chủ</a></li>
                <li><a href="#about">Giới Thiệu</a></li>
                <li><a href="#contact">Liên Hệ</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Trang Chủ</h2>
            <p>Đây là phần nội dung chính của trang chủ.</p>
        </section>
        
        <section id="about">
            <h2>Giới Thiệu</h2>
            <p>Đây là phần giới thiệu về bạn hoặc doanh nghiệp của bạn.</p>
        </section>
        
        <section id="contact">
            <h2>Liên Hệ</h2>
            <form id="contact-form">
                <label for="name">Tên:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Tin Nhắn:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Gửi</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Trang Web của Tôi. Bảo lưu mọi quyền.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>

