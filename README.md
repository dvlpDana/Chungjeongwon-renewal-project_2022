# Chungjeongwon 리뉴얼 프로젝트(22.05.02~22.05.09)

![project_4_mockup](https://user-images.githubusercontent.com/102039456/187325470-f5acc728-3fee-4f28-a2e2-a6cd4746a667.jpg)

Demo : [https://dvlpdana.github.io/Chungjeongwon-renewal-project_2022/](https://dvlpdana.github.io/Chungjeongwon-renewal-project_2022/)

<br />

## 프로젝트 개발목표

<p align="justify">
-  브랜드 성격에 맞는 문구, 이미지, 컬러 등을 통일감 있게 사용하여 Visual Identity 강조하기 <br/ >
-  Media query 사용하여 미디어 사이즈에 따라 크기와 배치가 달라지는 반응형 웹 제작 <br/ >
</p>

<br />

## 기술 스택

|    JQuery   |    HTML   |   CSS   |
| :---------: | :------: | :------: |
|   <img src="https://user-images.githubusercontent.com/102039456/187320976-6a4d77f3-31e8-47c0-b1c6-ab0589b2bfd1.png" width="50" height="50" >    |   <img src="https://user-images.githubusercontent.com/102039456/187320974-e67dcaa0-529e-4092-956c-56f3c92c0770.png" width="35" height="50" >   |   <img src="https://user-images.githubusercontent.com/102039456/187320969-00071316-6aae-4612-9991-102a10bf055d.png" width="35" height="50" >   |

<br>

## Advandced Feature

### Mediau query 활용하여 디스플레이의 사이즈에 따라 CSS 다르게 적용하는 반응형 웹
> 코드(sec-newsRoom.css)
```css
/* sec-newsRoom 모바일 버전 : max-width 820px start*/
@media (max-width: 1170px) {
  .news-banners li {
    font-size: smaller;
  }
  .news-banners li>p {
    bottom: 0;
  }
}

@media (max-width: 820px) {
  .sec-newsRoom {
    height: 100%;
  }

  .sec-newsRoom .wrap {
    padding: 50px 0;
  }

  .sec-newsRoom h3 {
    font-size: 3rem;
    padding-top: 0;
  }

  .sec-newsRoom h3+span {
    font-size: 1.25rem;
    padding-top: 1.5rem;
  }

  .news-banners {
    flex-wrap: wrap;
    justify-content: space-evenly;
  }
 ···
}

@media (max-width: 414px) {
  .sec-newsRoom h3 {
    font-size: 1.75rem;
  }

  .sec-newsRoom h3+span {
    font-size: 1rem;
    padding-bottom: 0;
  }
  .news-banners li {
    font-size: smaller;
    width: calc(50% - 1rem);
    padding-top: 55%;
  }

  .news-banners li > div {
    font-size: smaller;
  }

  .news-banners li > p {
    bottom: 1%;
    font-size: smaller;
  }
 ···
}
```

> 구현화면
<img src="https://user-images.githubusercontent.com/102039456/187327355-3953bc46-37b2-4bc8-9268-36dbd9f8d1d7.gif">

<br />

## 개선사항

<p align="justify">
- 자바스크립트 활용하여 사용자의 스크롤 움직임에 따른 Interactive 효과 적용하기 <br/>
- 모바일 버전 시, 불필요한 정보 감추어 화면 안정적으로 구현하기
</p>

<br />

## 라이센스

MIT &copy; [dvlpDana](mailto:colleksql3@gmail.com)



