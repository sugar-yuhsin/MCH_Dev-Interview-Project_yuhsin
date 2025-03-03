<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-container">
        <img src="../../public/images/Me.jpeg" alt="個人照片" class="profile-image" />
        <div class="intro-text">
          <h2>自我介紹</h2>
          <p>
            Hi! 開發部長們你們好 >< <br>
            我是現在就讀清大資工大二的施又歆，是苗栗人，但高中在新竹讀，已經在這邊當被風吹的女子第五年了，<br>
            常自稱自己是假E人（我很Ｉ），就是還算可以跟別人講話，但其實也蠻喜歡自己一個人安安靜靜的時候。<br>
            對我來說，參加各式資訊領域活動，可以發揮長才，也可以認識更多資訊領域的夥伴，並從中接觸到所有有趣的知識。<br>
            所以想成為黑客松的開發部員，跟一樣喜歡這個領域的人們籌備這場盛會！<br>
          </p>
        </div>
      </div>
    </header>
    
    <section class="about-section">
      <h3>&#128161; 大學的職務經驗</h3>
      <ul>
        <li>外工資夜主持人</li>
        <li>梅竹黑客松活動部</li>
      </ul>
      <h3>&#128161; 社團</h3>
      <ul>
        <li>清大熱舞</li>
        <li>交大SDG好想去但還沒...</li>
      </ul>
      <h3>&#128161; 分享資工爛笑話</h3>
      <ul>
        <li>一天有二十四小時，但是所謂的"今天之內"，指的是到明天早上上班為止。</li>
        <li>為什麼程式設計師討厭大自然？因為有太多 bug！</li>
      </ul>
      
      


    </section>
  </div>
</template>

<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1000px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 35px;
  border-radius: 10px;
}

.intro-container {
  display: flex;
  align-items: center;
  gap: 20px; 
}

.profile-image {
  width: 170px; 
  height: 200px;
  border-radius: 50%; 
  object-fit: cover; 
}

.intro-text {
  flex: 1; 
}

.intro-text h2 {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1rem;
  margin-bottom: 20px;
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

.about-section ul {
  list-style-type: disc;
  padding-left: 20px;
}

.about-section li {
  font-size: 1rem;
  line-height: 1.6;
}

.joke-card {
        background: #f9f9f9;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        margin: 10px;
        width: fit-content;
}
</style>
