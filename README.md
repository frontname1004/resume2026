# 🖥️ 정우석 포트폴리오
---

#🧑‍🎓 About Me <br>

프론트엔드 개발자를 목표하며 



---

# 🛠️ Tech Stack
·  **HTML5**<br>
·  **CSS3<br/>**

**- Tools**

**· VS Code <br/>**
**· Figma <br/>**
**· Github <br/>**

----

# 🗃️ Sections (
1. 💡 Introduction (머리말)
2. 🧑‍🎓 About Me (자기 소개)
3. 💪 Strengths ( 강점 3가지)
4. 🛠️ Tech Stack (기술 스택 및 수준)
5. 🎨 Project Showcase (프로젝트 소개)
6. 📬 Contact (연락처 및 이메일)
---

# ✨ Key Features (핵심 구현 기능)

* **Flex와 Grid를 이용한 박스 모델(Card UI) 설계**<br>
  · 개인 정보 구역에는 Grid 체계를 적용하여 다차원 레이아웃을 깔끔하게 구조화했습니다.

```css
.info-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px 20px;
}
```
---

 * **·  상단 메뉴 구역 (.nav-menu ul)**<br>
메뉴 버튼들을 가로로 나란히 배치하고 사이 간격을 줄 때 Flex를 사용했습니다.
```css
.nav-menu ul {
  display: flex;
  gap: 30px;
  margin-bottom: 40px;
}
```
---

# 🔃 Updates (수정 내역)

* **모바일 가독성을 위한 예외 처리 및 디테일 최적화**<br>
· 767px 이하 모바일 환경에서 문장이 어색하게 쪼개지는 현상을 발견하고,<br>
br 태그를 무시하는 예외 처리를 구현했습니다.

```css
@media screen and (max-width: 767px) {
  .intro-text br {
    display: none;
  }
}
```




