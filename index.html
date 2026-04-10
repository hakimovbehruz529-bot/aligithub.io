{% load static %}
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{% block title %}DIGITALLY.TJ{% endblock %}</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&family=Orbitron:wght@500;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="{% static 'css/styles.css' %}?v=20260410b">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <script src="https://unpkg.com/htmx.org@1.9.12"></script>
</head>
<body>
    <header class="header">
        <div class="container nav">
            <a class="brand" href="{% url 'products:home' %}"><span class="brand-accent">D</span>IGIT<span class="brand-accent">A</span>LLY.TJ</a>
            <nav class="top-nav">
                <a href="{% url 'products:home' %}">Главная</a>
                <a href="{% url 'products:product_list' %}">Каталог</a>
                <a href="{% url 'products:pc_builder' %}">Конфигуратор ПК</a>
                <a href="{% url 'products:about' %}">О нас</a>
                <a href="{% url 'products:warranty' %}">Гарантия</a>
                <a href="{% url 'cart:cart_detail' %}">Корзина ({{ cart_items_count }})</a>
                <div class="theme-switch-icons" aria-label="Режим темы">
                    <button type="button" id="theme-sun" class="theme-icon-btn" title="Светлая тема" aria-label="Светлая тема">☀</button>
                    <button type="button" id="theme-moon" class="theme-icon-btn" title="Темная тема" aria-label="Темная тема">🌙</button>
                </div>
                {% if user.is_authenticated %}
                    <a href="{% url 'users:profile' %}">Кабинет</a>
                    <form method="post" action="{% url 'users:logout' %}" class="inline-form">{% csrf_token %}<button type="submit" class="link-btn">Выход</button></form>
                {% else %}
                    <a href="{% url 'users:login' %}">Вход</a>
                    <a href="{% url 'users:register' %}">Регистрация</a>
                {% endif %}
            </nav>
        </div>
    </header>
    <main class="container page">
        {% if messages %}
            <ul class="messages">
                {% for message in messages %}
                    <li>{{ message }}</li>
                {% endfor %}
            </ul>
        {% endif %}
        {% block content %}{% endblock %}
    </main>
    <footer class="site-footer">
        <div class="container footer-grid">
            <div>
                <h3><span class="brand-accent">D</span>IGIT<span class="brand-accent">A</span>LLY.TJ</h3>
                <p>Интернет-магазин компьютерной техники с современным сервисом и быстрой доставкой.</p>
            </div>
            <div>
                <h4>Разделы</h4>
                <a href="{% url 'products:home' %}">Главная</a>
                <a href="{% url 'products:product_list' %}">Каталог</a>
                <a href="{% url 'products:pc_builder' %}">Конфигуратор ПК</a>
                <a href="{% url 'products:about' %}">О нас</a>
                <a href="{% url 'products:warranty' %}">Гарантия</a>
                <a href="{% url 'cart:cart_detail' %}">Корзина</a>
            </div>
            <div>
                <h4>Контакты</h4>
                <p>Тел: +992 00 000 00 00</p>
                <p>Email: support@digitally.tj</p>
                <div class="social-links">
                    <a href="https://t.me/" target="_blank" rel="noopener noreferrer" aria-label="Telegram"><i class="fa-brands fa-telegram"></i></a>
                    <a href="https://instagram.com/" target="_blank" rel="noopener noreferrer" aria-label="Instagram"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Facebook"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://youtube.com/" target="_blank" rel="noopener noreferrer" aria-label="YouTube"><i class="fa-brands fa-youtube"></i></a>
                </div>
            </div>
        </div>
    </footer>
    <script>
        (function () {
            var key = "digitally_theme_mode";
            var sunBtn = document.getElementById("theme-sun");
            var moonBtn = document.getElementById("theme-moon");
            if (!sunBtn || !moonBtn) return;

            function applyTheme(theme) {
                document.documentElement.setAttribute("data-theme", theme);
                sunBtn.classList.toggle("active", theme === "light");
                moonBtn.classList.toggle("active", theme !== "light");
            }

            var saved = localStorage.getItem(key);
            var initial = saved === "light" ? "light" : "dark";
            applyTheme(initial);

            sunBtn.addEventListener("click", function () {
                localStorage.setItem(key, "light");
                applyTheme("light");
            });
            moonBtn.addEventListener("click", function () {
                localStorage.setItem(key, "dark");
                applyTheme("dark");
            });
        })();
    </script>
</body>
</html>
