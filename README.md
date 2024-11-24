<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>repl.it</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <style>
    body {
      margin: 0;
    }

    .nav {
      height: 70px;
      border-bottom: 1px solid black;
      display: felx;
      text-align: center;
    }

    .nav-right-items {
      display: flex;
      margin-left: auto;
    }

    .nav-item {
      margin-left: 20px;
    }

    .company-name {
      margin-left: 20px;
    }

    .title {
      text-align: center;
      font-size: 3.5rem;
      font-weight: bold;
    }

    .subtitle {
      text-align: center;
      font-size: 1.25rem;
      font-weight: 300;
    }

    .main {
      width: 1000px;
      margin: 0 auto;
      margin-top: 60px;
    }

    .prices {
      display: flex;
    }

    .price-item {
      width: 300px;
      height: 350px;
      border: 1px solid black;
      margin: 20px;
      border-radius: 4px;
    }

    .price-item-title {
      font-size: 1.5rem;
      background: rgba(0, 0, 0, .03);
      text-align: center;
      height: 53px;
      line-height: 53px;
      border-bottom: 1px solid black;
    }

    .price-item-price {
      font-size: 2.5rem;
      font-weight: bold;
      padding: 20px;
    }

    .price-item-button {
      padding: .5rem 1rem;
      font-size: 1.25rem;
      line-height: 1.5;
      border-radius: .3rem;
      color: #007bff;
      background-color: transparent;
      background-image: nnone;
      border-color: #007bff;
      margin-top: 30px;
    }

    .price-item-button--active {
      background-color: #007bff;
      color: white;
    }

    .price-item-month {
      font-size: 16px;
      color: gray;
    }

    .price-item-detail {
      margin-bottom: 5px;
      font-size: 18px;
    }
  </style>
</head>

<body>
  <div class="nav">
    <div class="company-name">
      서창고
      <div class="nav-right-items">
        <div class="nav-item">사람1</div>
        <div class="nav-item">사람2</div>
        <div class="nav-item">사람3</div>
        <div class="nav-item">사람4</div>
      </div>
    </div>
    <div class="main">
      <div class="title">
        Hello world
      </div>
      <div class="subtitle">테스트용 웹사이트 
      </div>
      <div class="prices">
        <div class="price-item">
          <div class="price-item-title">
            Free
          </div>
          <div class="price-item-price">
            $0 / 월
          </div>
          <div class="price-item-detail">
            10명의 사용자가 포함됨
          </div>
          <div class="price-item-detail">
            2 GB의 저장공간
          </div>
          <div class="price-item-detail">
            이메일 지원
          </div>
          <div class="price-item-detail">
            도움말 센터 접근
          </div>
          <button class="price-item-button">
            Click me
          </button>
        </div>
        <div class="price-item">
          <div class="price-item-title ">
            Free
          </div>
          <div class="price-item-price">
            $0 / 월
          </div>
          <div class="price-item-detail">
            10명의 사용자가 포함됨
          </div>
          <div class="price-item-detail">
            2 GB의 저장공간
          </div>
          <div class="price-item-detail">
            이메일 지원
          </div>
          <div class="price-item-detail">
            도움말 센터 접근
          </div>
          <button class="price-item-button price-item-button--active">
            Click me
          </button>
        </div>
        <div class="price-item">
          <div class="price-item-title">
            Free
          </div>
          <div class="price-item-price">
            $0 / 월
          </div>
          <div class="price-item-detail">
            10명의 사용자가 포함됨
          </div>
          <div class="price-item-detail">
            2 GB의 저장공간
          </div>
          <div class="price-item-detail">
            이메일 지원
          </div>
          <div class="price-item-detail">
            도움말 센터 접근
          </div>
          <button class="price-item-button price-item-button--active">
            Click me
          </button>
        </div>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
