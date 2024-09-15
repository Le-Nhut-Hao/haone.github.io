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
[Uploading style.css…/* Reset một số thuộc tính mặc định */
body, h1, h2, p, ul, li, form, input, textarea {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}
[Uploading script.js…]()document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contact-form');
    
    form.addEventListener('submit', function(event) {
        event.preventDefault(); // Ngăn chặn hành động gửi form mặc định
        
        const name = document.getElementById('name').value;
        const email = document.getElementById('email').value;
        const message = document.getElementById('message').value;
        
        alert(`Tên: ${name}\nEmail: ${email}\nTin Nhắn: ${message}`);
        
        // Thực hiện xử lý form tại đây, ví dụ gửi dữ liệu đến máy chủ
    });
});



main {
    padding: 1rem;
}

section {
    margin-bottom: 2rem;
}

form label {
    display: block;
    margin-top: 0.5rem;
}

form input, form textarea {
    width: 100%;
    padding: 0.5rem;
    margin-top: 0.2rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    background: #333;
    color: #fff;
    border: none;
    padding: 0.7rem;
    border-radius: 4px;
    cursor: pointer;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

/* Responsive Styles */
@media (max-width: 768px) {
    header {
        padding: 0.5rem;
    }
    
    nav ul {
        text-align: center;
    }
    
    nav ul li {
        display: block;
        margin-bottom: 0.5rem;
    }
    
    form input, form textarea {
        padding: 0.4rem;
    }
    
    form button {
        padding: 0.5rem;
    }
}
]()


