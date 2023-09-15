# HTML, CSS Project-BOMI DESIGN

인테리어 회사 웹사이트

## :computer: 프로젝트 소개

HTML과 CSS만을 이용한 반응형 웹사이트 입니다.
- Demo : <https://bomiinterior.netlify.app/>

## ⌚ 개발 기간

- 23.09.09(토) - 23.09.11(월)

## 🧑‍💻 사용 기술

- HTML
- CSS
- Bootstrap
- Media Query

## 👉 주요 기능

### Navbar (Bootstrap)

- 우측 input 박스와 button 대신 아이콘 넣기.
    
      <div class="d-flex">
        <ul class="navbar-nav nav-icons">
          <li>
            <a href="https://www.instagram.com/" target='_blank'>
              <i class="fa-brands fa-instagram icon"></i>
            </a>
          </li>
          <li>
            <a href="https://goo.gl/maps/efwMe1ktaHfEhPJM6" target='_blank'>
              <i class="fa-solid fa-location-dot icon map-icon"></i>
            </a>
          </li>
        </ul>
      </div>

- active 상태인 메뉴의 색상 바꾸기.
- 각 메뉴마다 페이지 링크 만들기.

    ```
    <li class="nav-item">
      <a class="nav-link active" aria-current="page" href="./ABOUT.html"
        >ABOUT</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="/PROJECTS.html">PROJECT</a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="./PROCESS.html">PROCESS</a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="./CONTACT.html">CONTACT</a>
    </li>
    ```
    ```
    .active {
      color: #d27328 !important;
    }
    ```

    ### 미디어 쿼리
  (web 버전)
  
    
