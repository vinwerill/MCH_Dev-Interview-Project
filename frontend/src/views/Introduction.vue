<template>
  <div class="introduction">
    <header class="intro-header">
      <h2>自我介紹</h2>
      <div style="display: flex;">
      <img src="/images/Self_picture.jpg" alt="Avatar" style="vertical-align: top; width: 200px; border-radius: 50%;">
      <p style="vertical-align: text-top; margin: 10px;">
        
        我是清大資工系二年級的陳廷森。興趣是玩遊戲、看動漫和小說。因為對資工領域有興趣，偶爾也會自行學習一些酷炫的相關知識或相關課程。不過我也發現自己似乎並非天賦異稟，常遇到許多困難而影響學習速度，甚至課業的關係不得不放棄。因此，我也希望能有熟悉相關知識的人能夠幫我解惑，讓我能夠更快速的學習。
        在聽聞梅竹黑客松後我便產生了興趣，尤其是開發部。希望能透過參與這項活動，學習有趣的知識和技術。
      </p>
    </div>
      
    </header>
    <section class="about-section">
      <h3>相關能力</h3>
      <ul>
        <li>擅長程式語言：C/C++、Python</li>
        <li>會使用Javascript、CSS、HTML等程式語言，也會使用Flask、Bootstrap框架，並粗淺學過JQuery函式庫</li>
        <li>曾負責架設高雄中學學聯會網站，不過目前網站已由他人管理維護並更改使用的程式語言，並非我所製作的版本，不過部分功能和樣板仍有留下</li>
      </ul>
      <h3>相關作品成果</h3>
      <ul>
        <li>現今網站：<a href="https://kssasite.com/" target="_blank" style="color: blue;">https://kssasite.com/</a></li>
        <li>網頁repo：<a href="https://github.com/vinwerill/kssasite" target="_blank" style="color: blue;">https://github.com/vinwerill/kssasite</a></li>
      </ul>
    </section>
  </div>
</template>


<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 10px;
}



.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}
</style>
