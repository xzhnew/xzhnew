## 我的名字叫 xzh ———— 一个一心写好翻译器来着中国的男孩

> 我把技术栈收进一张卡片里，鼠标经过时，它会悄悄翻开。

<style>
  .folio-card-box {
    perspective: 1000px;
    width: 300px;
    height: 380px;
    margin: 0 auto 24px;
  }
  .folio-card {
    position: relative;
    width: 100%;
    height: 100%;
    transition: transform 0.7s cubic-bezier(0.23, 1, 0.32, 1);
    transform-style: preserve-3d;
  }
  .folio-card-box:hover .folio-card {
    transform: rotateY(180deg);
  }
  .folio-face {
    position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    box-shadow: 0 12px 28px rgba(0, 0, 0, 0.18);
  }
  .folio-front {
    background: linear-gradient(145deg, #1f1f1f, #2c2c2c);
    color: #f0f0f0;
  }
  .folio-back {
    background: #f8f6f2;
    color: #333;
    transform: rotateY(180deg);
    box-sizing: border-box;
    padding: 28px 22px;
    text-align: left;
    align-items: flex-start;
    font-family: 'Georgia', 'KaiTi', serif;
  }
  .folio-back h3 {
    margin: 0 0 16px;
    font-size: 18px;
    border-bottom: 1px solid #d0cfcf;
    padding-bottom: 8px;
    width: 100%;
  }
  .folio-back ul {
    list-style: none;
    padding: 0;
    margin: 0;
    line-height: 2.2;
    font-size: 15px;
  }
  .folio-back ul li::before {
    content: "▸ ";
  }
  .folio-back a {
    display: inline-block;
    margin-top: 20px;
    background: #2c2c2c;
    color: white;
    padding: 8px 24px;
    border-radius: 40px;
    text-decoration: none;
    font-size: 14px;
    letter-spacing: 0.5px;
    transition: background 0.3s;
    align-self: center;
  }
  .folio-back a:hover {
    background: #4a4a4a;
  }
  .folio-front img {
    border-radius: 50%;
    border: 2px solid rgba(255,255,255,0.3);
    margin-bottom: 14px;
  }
  .folio-front .quote {
    font-style: italic;
    letter-spacing: 1px;
    font-size: 15px;
    padding: 0 12px;
  }
  .folio-front .hint {
    color: #aaa;
    font-size: 12px;
    margin-top: 8px;
  }
</style>

<div class="folio-card-box">
  <div class="folio-card">
    <!-- 正面 -->
    <div class="folio-face folio-front">
      <!-- 换成你自己的头像地址 -->
      <img src="https://avatars.githubusercontent.com/u/583231?v=4" width="80" alt="头像" />
      <div class="quote">“ 寂静在生长，代码在发光 ”</div>
      <div class="hint">⏤ 天边云彩，变幻莫测。 ⏤</div>
    </div>
    <!-- 背面 -->
    <div class="folio-face folio-back">
      <h3>正在学习</h3>
      <ul>
        <li>▸ HTML </li>
        <li>▸ CSS </li>
        <li>▸ JavaScript </li>
        <li>▸ Git </li>
        <li>▸ Hexo </li>
      </ul>
      <a href="https://xzhnew.github.io">进入我的文字</a>
    </div>
  </div>
</div>


---

###  关于这里

 [blog](https://xzhnew.github.io) 是我思想的备份，每周会写点儿什么——可能是一个布局的感悟，或是一段调试时的絮语。  
如果你也相信「慢下来才能看见细节」，欢迎过去坐坐，留一盏茶的时间。

---
