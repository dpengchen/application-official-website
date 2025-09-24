<script setup lang="ts">
import screenshot1 from './assets/1.jpg'
import screenshot2 from './assets/2.jpg'
import screenshot3 from './assets/3.jpg'
</script>

<template>
  <div class="app-container">
    <!-- 导航栏 -->
    <nav class="navbar">
      <div class="nav-container">
        <div class="nav-logo">
          <h2>百信好料</h2>
        </div>
        <ul class="nav-menu">
          <li class="nav-item">
            <a href="#home" class="nav-link">首页</a>
          </li>
          <li class="nav-item">
            <a href="#features" class="nav-link">产品展示</a>
          </li>
          <li class="nav-item">
            <a href="#screenshots" class="nav-link">应用截图</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link">关于我们</a>
          </li>
          <li class="nav-item">
            <a href="#contact" class="nav-link">联系我们</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- 首屏区域 -->
    <section id="home" class="hero">
      <div class="hero-content">
        <h1 class="hero-title">百信好料 - 改变您的数字生活</h1>
        <p class="hero-description">
          一款功能强大、设计精美的应用程序，帮助您更高效地了解最新资讯信息，更愉快地享受生活。百信好料
          提供多种实用功能，满足您的各种需求。
        </p>
        <div class="hero-buttons">
          <button class="btn primary">立即下载</button>
          <button class="btn secondary">了解更多</button>
        </div>
      </div>
      <div class="hero-image">
        <img :src="screenshot1" alt="应用界面截图" class="hero-screenshot" />
      </div>
    </section>

    <!-- 产品介绍 -->
    <section class="intro">
      <div class="intro-content">
        <h2>关于 百信好料</h2>
        <p>
          百信好料
          是一款集多种功能于一体的创新软件，旨在为用户提供一站式解决方案。我们的团队致力于打造简洁、高效、易用的产品，让用户在数字时代中更加轻松自如。
        </p>
        <p>
          经过多年研发和改进，百信好料
          已经成为行业领先的应用程序之一，并获得了广泛的好评和认可。
        </p>
      </div>
    </section>

    <!-- 功能特性 -->
    <section id="features" class="features">
      <div class="section-title">
        <h2>功能特性</h2>
        <p>探索 百信好料 的强大功能</p>
      </div>
      <div class="features-grid">
        <div class="feature-card">
          <div class="feature-icon">⚡</div>
          <h3>极速性能</h3>
          <p>优化的架构设计，提供流畅的用户体验，响应速度快，操作无延迟。</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🔒</div>
          <h3>安全保障</h3>
          <p>端到端加密，保护您的隐私和数据安全，让您使用无忧。</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🎨</div>
          <h3>精美设计</h3>
          <p>现代化界面设计，赏心悦目，操作直观，用户体验极佳。</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🔄</div>
          <h3>实时同步</h3>
          <p>多设备间数据实时同步，随时随地访问您的信息。</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">📱</div>
          <h3>跨平台支持</h3>
          <p>支持 Web、iOS、Android 等多个平台，无缝切换。</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">⚙️</div>
          <h3>个性化定制</h3>
          <p>丰富的个性化设置选项，让应用更符合您的使用习惯。</p>
        </div>
      </div>
    </section>

    <!-- 应用截图 -->
    <section id="screenshots" class="screenshots">
      <div class="section-title">
        <h2>应用截图</h2>
        <p>一览 百信好料 的精美界面</p>
      </div>
      <div class="screenshots-gallery">
        <div class="screenshot-item">
          <img :src="screenshot1" alt="截图1" />
        </div>
        <div class="screenshot-item">
          <img :src="screenshot2" alt="截图2" />
        </div>
        <div class="screenshot-item">
          <img :src="screenshot3" alt="截图3" />
        </div>
      </div>
    </section>

    <!-- 关于我们 -->
    <section id="about" class="about">
      <div class="section-title">
        <h2>关于我们</h2>
      </div>
      <div class="about-content">
        <h3>用户协议</h3>
        <p>使用 百信好料 即表示您同意以下条款：</p>
        <ol>
          <li>本软件为免费使用，但部分高级功能可能需要付费解锁</li>
          <li>用户需遵守相关法律法规，不得利用本软件从事违法活动</li>
          <li>我们尊重并保护用户隐私，不会未经允许收集或泄露用户个人信息</li>
          <li>软件所有权利归创新科技有限公司所有</li>
          <li>我们保留随时修改或终止服务的权利，恕不另行通知</li>
        </ol>

        <h3>版权所有</h3>
        <p>百信好料 未经许可，任何组织或个人不得以任何形式复制、转载或用于商业用途。</p>
      </div>
    </section>

    <!-- 联系我们 -->
    <section id="contact" class="contact">
      <div class="section-title">
        <h2>联系我们</h2>
      </div>
      <div class="contact-content">
        <div class="contact-info">
          <h3>联系方式</h3>
          <p><strong>客服热线：18385582406</strong></p>
          <p><strong>客服邮箱：406743415@qq.com </strong></p>
        </div>
        <div class="contact-form">
          <h3>留言反馈</h3>
          <form>
            <div class="form-group">
              <input type="text" placeholder="您的姓名" class="form-control" />
            </div>
            <div class="form-group">
              <input type="email" placeholder="您的邮箱" class="form-control" />
            </div>
            <div class="form-group">
              <textarea placeholder="留言内容" class="form-control textarea" rows="5"></textarea>
            </div>
            <button type="submit" class="btn primary">提交留言</button>
          </form>
        </div>
      </div>
    </section>

    <!-- 下载区域 -->
    <section class="download">
      <div class="download-content">
        <h2>立即开始使用</h2>
        <p>免费下载 百信好料，体验前所未有的便捷</p>
        <div class="download-buttons">
          <button class="btn primary large">免费下载</button>
          <button class="btn secondary large">查看更新日志</button>
        </div>
      </div>
    </section>

    <!-- 页脚 -->
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-info">
          <p>&copy; 2025</p>
          <!-- <p>网站备案号：京ICP备12345678号-1</p> -->
        </div>
        <div class="footer-links">
          <a href="#about">用户协议</a>
          <a href="#about">隐私政策</a>
          <a href="#contact">联系我们</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.app-container {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  color: #333;
  line-height: 1.6;
}

.navbar {
  background-color: #fff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
}

.nav-logo h2 {
  color: #42b883;
  margin: 0;
}

.nav-menu {
  display: flex;
  list-style: none;
}

.nav-item {
  margin-left: 30px;
}

.nav-link {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-link:hover {
  color: #42b883;
}

.hero {
  padding: 150px 20px 100px;
  display: flex;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  gap: 50px;
}

.hero-content {
  flex: 1;
}

.hero-title {
  font-size: 3rem;
  margin-bottom: 20px;
  color: #2c3e50;
  line-height: 1.2;
}

.hero-description {
  font-size: 1.2rem;
  margin-bottom: 30px;
  color: #7f8c8d;
}

.hero-buttons {
  display: flex;
  gap: 15px;
}

.btn {
  padding: 12px 30px;
  border-radius: 30px;
  border: none;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
}

.primary {
  background-color: #42b883;
  color: white;
}

.secondary {
  background-color: transparent;
  color: #42b883;
  border: 2px solid #42b883;
}

.btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.hero-image {
  flex: 1;
  display: flex;
  justify-content: center;
}

.hero-screenshot {
  max-width: 100%;
  border-radius: 10px;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

.intro {
  padding: 80px 20px;
  background-color: #f8f9fa;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-content h2 {
  font-size: 2rem;
  color: #2c3e50;
  margin-bottom: 30px;
  text-align: center;
}

.intro-content p {
  font-size: 1.1rem;
  margin-bottom: 20px;
  color: #555;
  text-align: center;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.section-title {
  text-align: center;
  margin-bottom: 60px;
}

.section-title h2 {
  font-size: 2.5rem;
  color: #2c3e50;
  margin-bottom: 15px;
}

.section-title p {
  font-size: 1.2rem;
  color: #7f8c8d;
}

.features {
  padding: 100px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.feature-card {
  background: white;
  padding: 40px 30px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  transition: transform 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-10px);
}

.feature-icon {
  font-size: 3rem;
  margin-bottom: 20px;
}

.feature-card h3 {
  font-size: 1.5rem;
  margin-bottom: 15px;
  color: #2c3e50;
}

.screenshots {
  padding: 100px 20px;
  background-color: #f8f9fa;
  max-width: 1200px;
  margin: 0 auto;
}

.screenshots-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.screenshot-item img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.screenshot-item img:hover {
  transform: scale(1.03);
}

.about {
  padding: 100px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.about-content h3 {
  font-size: 1.8rem;
  color: #2c3e50;
  margin: 30px 0 15px;
}

.about-content p {
  margin-bottom: 15px;
  color: #555;
}

.about-content ol {
  padding-left: 20px;
  color: #555;
}

.about-content li {
  margin-bottom: 10px;
}

.contact {
  padding: 100px 20px;
  background-color: #f8f9fa;
  max-width: 1200px;
  margin: 0 auto;
}

.contact-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 50px;
}

.contact-info p {
  margin-bottom: 15px;
  font-size: 1.1rem;
}

.form-group {
  margin-bottom: 20px;
}

.form-control {
  width: 100%;
  padding: 12px 15px;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 1rem;
}

.textarea {
  resize: vertical;
}

.download {
  padding: 100px 20px;
  text-align: center;
  color: white;
  background: linear-gradient(135deg, #42b883, #3498db);
}

.download-content h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.download-content p {
  font-size: 1.2rem;
  margin-bottom: 40px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.download-buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.btn.large {
  padding: 15px 40px;
  font-size: 1.1rem;
}

.footer {
  background-color: #2c3e50;
  color: white;
  padding: 30px 20px;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.footer-info p {
  margin: 5px 0;
}

.footer-links a {
  color: #ecf0f1;
  margin-left: 20px;
  text-decoration: none;
  transition: color 0.3s;
}

.footer-links a:hover {
  color: #42b883;
}

@media (max-width: 768px) {
  .hero {
    flex-direction: column;
    text-align: center;
  }

  .hero-buttons {
    justify-content: center;
  }

  .nav-menu {
    display: none;
  }

  .hero-title {
    font-size: 2rem;
  }

  .footer-content {
    flex-direction: column;
    text-align: center;
  }

  .footer-links {
    margin-top: 20px;
  }

  .footer-links a {
    margin: 0 10px;
  }

  .contact-content {
    grid-template-columns: 1fr;
  }
}
</style>
