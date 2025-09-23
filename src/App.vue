<template>
  <div id="app">
    <!-- Header -->
    <header class="header">
      <nav class="navbar">
        <div class="nav-brand">
          <h2>百科软件</h2>
        </div>
        <ul class="nav-menu">
          <li><a href="#home">首页</a></li>
          <li><a href="#services">服务</a></li>
          <li><a href="#about">关于我们</a></li>
          <li><a href="#contact">联系我们</a></li>
        </ul>
      </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
      <div class="hero-content">
        <h1>专业的软件开发服务</h1>
        <p>我们是一家专注于提供高质量软件解决方案的技术公司</p>
        <button class="cta-button">了解更多</button>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
      <div class="container">
        <h2>我们的服务</h2>
        <div class="services-grid">
          <div class="service-card">
            <h3>Web 开发</h3>
            <p>使用现代技术栈构建响应式和高性能的Web应用程序</p>
          </div>
          <div class="service-card">
            <h3>移动应用开发</h3>
            <p>开发跨平台的移动应用，支持iOS和Android系统</p>
          </div>
          <div class="service-card">
            <h3>软件定制</h3>
            <p>根据客户需求定制专业的企业级软件解决方案</p>
          </div>
          <div class="service-card">
            <h3>技术咨询</h3>
            <p>提供专业的技术咨询和架构设计服务</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
      <div class="container">
        <h2>关于我们</h2>
        <div class="about-content">
          <div class="about-text">
            <p>百科软件成立于2020年，是一家专业的软件开发公司。我们拥有经验丰富的开发团队，专注于为客户提供高质量的软件解决方案。</p>
            <p>我们的团队由资深的前端、后端和移动端开发工程师组成，具备丰富的项目经验和技术积累。</p>
          </div>
          <div class="about-stats">
            <div class="stat">
              <h3>50+</h3>
              <p>完成项目</p>
            </div>
            <div class="stat">
              <h3>30+</h3>
              <p>满意客户</p>
            </div>
            <div class="stat">
              <h3>5年</h3>
              <p>行业经验</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <div class="container">
        <h2>联系我们</h2>
        <div class="contact-content">
          <div class="contact-info">
            <div class="contact-item">
              <h4>电话</h4>
              <p>+86 138-0000-0000</p>
            </div>
            <div class="contact-item">
              <h4>邮箱</h4>
              <p>info@baikesoftware.com</p>
            </div>
            <div class="contact-item">
              <h4>地址</h4>
              <p>北京市海淀区中关村软件园</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>&copy; 2024 百科软件. 保留所有权利.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Microsoft YaHei', Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Header */
.header {
  background: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
}

.nav-brand h2 {
  color: #2c3e50;
}

.nav-menu {
  display: flex;
  list-style: none;
  gap: 2rem;
}

.nav-menu a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-menu a:hover {
  color: #3498db;
}

/* Hero Section */
.hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
  padding: 150px 0 100px;
  margin-top: 80px;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.cta-button {
  background: #3498db;
  color: white;
  border: none;
  padding: 15px 30px;
  font-size: 1.1rem;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s;
}

.cta-button:hover {
  background: #2980b9;
}

/* Services Section */
.services {
  padding: 80px 0;
  background: #f8f9fa;
}

.services h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #2c3e50;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.service-card {
  background: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.service-card:hover {
  transform: translateY(-5px);
}

.service-card h3 {
  color: #2c3e50;
  margin-bottom: 1rem;
}

/* About Section */
.about {
  padding: 80px 0;
}

.about h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #2c3e50;
}

.about-content {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 3rem;
  align-items: center;
}

.about-text p {
  margin-bottom: 1rem;
  font-size: 1.1rem;
  color: #666;
}

.about-stats {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.stat {
  text-align: center;
  padding: 1rem;
  background: #f8f9fa;
  border-radius: 10px;
}

.stat h3 {
  font-size: 2rem;
  color: #3498db;
  margin-bottom: 0.5rem;
}

/* Contact Section */
.contact {
  padding: 80px 0;
  background: #f8f9fa;
}

.contact h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #2c3e50;
}

.contact-content {
  max-width: 800px;
  margin: 0 auto;
}

.contact-info {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
}

.contact-item {
  text-align: center;
  padding: 2rem;
  background: white;
  border-radius: 10px;
}

.contact-item h4 {
  color: #2c3e50;
  margin-bottom: 1rem;
}

/* Footer */
.footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 2rem 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    gap: 1rem;
  }

  .nav-menu {
    gap: 1rem;
  }

  .hero-content h1 {
    font-size: 2rem;
  }

  .about-content {
    grid-template-columns: 1fr;
  }

  .about-stats {
    flex-direction: row;
    justify-content: space-around;
  }
}
</style>
