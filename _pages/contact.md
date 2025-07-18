---
title: "Contact"
layout: single
permalink: /contact/
author_profile: true
classes: wide
---

## 연락처 정보

저에게 연락하고 싶으시다면 아래의 방법을 이용해주세요.

<div class="contact-container">
  <div class="contact-item">
    <div class="contact-icon"><i class="fas fa-envelope"></i></div>
    <div class="contact-info">
      <h3>이메일</h3>
      <p><a href="mailto:kjhun0525@email.com">kjhun0525@email.com</a></p>
    </div>
  </div>
  
  <div class="contact-item">
    <div class="contact-icon"><i class="fab fa-linkedin"></i></div>
    <div class="contact-info">
      <h3>LinkedIn</h3>
      <p><a href="https://linkedin.com/in/kjhun0525" target="_blank">linkedin.com/in/kjhun0525</a></p>
    </div>
  </div>
  
  <div class="contact-item">
    <div class="contact-icon"><i class="fab fa-github"></i></div>
    <div class="contact-info">
      <h3>GitHub</h3>
      <p><a href="https://github.com/kjhun0525" target="_blank">github.com/kjhun0525</a></p>
    </div>
  </div>
</div>

## 메시지 보내기

<form id="contact-form" action="https://formspree.io/f/your-formspree-id" method="POST">
  <div class="form-group">
    <label for="name">이름</label>
    <input type="text" id="name" name="name" required>
  </div>
  
  <div class="form-group">
    <label for="email">이메일</label>
    <input type="email" id="email" name="_replyto" required>
  </div>
  
  <div class="form-group">
    <label for="subject">제목</label>
    <input type="text" id="subject" name="subject" required>
  </div>
  
  <div class="form-group">
    <label for="message">메시지</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>
  
  <button type="submit">보내기</button>
</form>

<style>
.contact-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-bottom: 40px;
}

.contact-item {
  display: flex;
  align-items: flex-start;
  width: 100%;
  max-width: 400px;
  padding: 15px;
  border-radius: 5px;
  background-color: #f8f9fa;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.contact-icon {
  font-size: 24px;
  margin-right: 15px;
  color: #4CAF50;
}

.contact-info h3 {
  margin-top: 0;
  margin-bottom: 5px;
}

.contact-info p {
  margin: 0;
}

#contact-form {
  max-width: 600px;
}

.form-group {
  margin-bottom: 20px;
}

label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

input, textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}

button {
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #45a049;
}
</style>