---
title: ""
draft: false
hideMeta: true
---

<!-- 1. 极简高级的圆圈设计（完全居中，带缺口与手机端换行） -->
<div style="position: relative; display: flex; align-items: center; justify-content: center; height: 380px; margin-top: 20px; margin-bottom: 20px;">
  
  <!-- 背后的完整圆圈 (z-index: 1 保证它在下层) -->
  <div style="position: absolute; width: 350px; height: 350px; border: 1.5px solid var(--primary); border-radius: 50%; z-index: 1;"></div>  
  <!-- 前面的文字块 (z-index: 2 保证在最上层) -->
  <!-- 注意：这里的 background-color: #fcfcfc 必须和网页背景色完全一样，才能形成“缺口” -->
  <div style="position: relative; z-index: 2; background-color: #f5f5f5; padding: 20px 40px; font-size: 24px; font-weight: 500; color: var(--primary); letter-spacing: 4px; text-align: center; line-height: 1.6;">
    归于至简，<br class="mobile-br">做到极致。
  </div>

</div>



<!-- 2. 这是你的核心 Slogan（居中对齐，颜色稍微变灰一点显得有层次感） -->

<div style="text-align: center; color: var(--secondary); font-size: 16px; margin-bottom: 60px;">
  在这个有限的世界，玩长期主义的游戏。
</div>



<!-- 3. 下面就是你的理念长文（回归最舒服的正常阅读排版） -->

<div style="text-align: center; max-width: 680px; margin: 0 auto; padding: 0 20px;">

  <!-- 居中的正文段落 -->
  <p style="line-height: 1.85; letter-spacing: 0.04em; margin-bottom: 30px;">
    我，阅读、写作，理解这个世界；<br>
    工作、服务，与这个世界发生连接；<br>
    也走走看看，亲身体验这个世界。
  </p>

  <p style="line-height: 1.85; letter-spacing: 0.04em; margin-bottom: 30px;">
    这个网站分为三个部分，<br>
    也是我工作与生活的一个缩影。<br>
  </p>

  <!-- 居中的二号大标题 -->
  <h2 style="font-size: 20px; margin-top: 50px; margin-bottom: 20px;">创作</h2>

  <!-- 居中的正文段落 -->
  <p style="line-height: 1.85; letter-spacing: 0.04em; margin-bottom: 30px;">
    这里记录我长期阅读、思考与写作留下的东西。<br>
    有「商业的世界」，也有「世界的脉络」；<br>
    理解商业与财富，从世界的脉络里寻找答案。
  </p>


   <!-- 居中的二号大标题 -->
  <h2 style="font-size: 20px; margin-top: 50px; margin-bottom: 20px;">工作</h2>

  <!-- 居中的正文段落 -->
  <p style="line-height: 1.85; letter-spacing: 0.04em; margin-bottom: 30px;">
    这是我与现实世界发生连接的地方。<br>
    我提供国际游学、出境旅游与各国签证等服务；<br>
    以全球视野，为你搭建探索广阔世界的桥梁。
  </p>


  <!-- 居中的二号大标题 -->
  <h2 style="font-size: 20px; margin-top: 50px; margin-bottom: 20px;">体验</h2>

  <!-- 居中的正文段落 -->
  <p style="line-height: 1.85; letter-spacing: 0.04em; margin-bottom: 30px;">
    这里有我对这个世界的体验；<br>
    也有我正在经历和思考的一些事情。
  </p>


<!-- “和我联系” -->
  <div style="margin-top: 60px; text-align: center; display: flex; flex-direction: column; align-items: center; gap: 15px;">  
    <!-- 文字链接 -->
    <a href="/about/" style="font-size: 16px; font-weight: 600; letter-spacing: 2px; color: #314964; text-decoration: none; border-bottom: 2px solid #eaeaea; padding-bottom: 2px; transition: border-color 0.3s ease;">
      和我联系
    </a>
  </div>
  
</div>