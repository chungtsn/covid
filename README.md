# covid
Code thông báo ca nhiễm covid trên toàn thế giới

<!DOCTYPE html>
<!-- Code By Webdevtrick ( https://webdevtrick.com ) -->
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>COVID-19 Realtime Update | Webdevtrick.com</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link rel="stylesheet" href="style.css">
 
</head>
<body>
 
<div class="preloader">
  <div class="preloader__content">
    <div class="preloader__loader"></div>
    <div class="preloader__txt">Loading ...</div>
  </div>
</div>
<div class="container">
  <div class="statistics">
    <div class="global">
      <div class="global__title">
        corona virus update
      </div>
      <div class="global__cases">
        <h1></h1>
        <h2>Total Cases</h2>
      </div>
      <div class="global__deaths">
        <h1></h1>
        <h2>Total Deaths</h2>
      </div>
      <div class="global__recovered">
        <h1></h1>
        <h2>Total Recovered</h2>
      </div>
    </div>
    <input type="text" id="search" name="country" placeholder="Search Countries">
    <select class="custom-select" id="select" onchange="changeOrder()">
      <option selected="" disabled="">Sort By</option>
      <option value="cases">Total Cases</option>
      <option value="deaths">Total Deaths</option>
      <option value="recovered">Total Recoveries</option>
    </select>
    <table class="table">
      <thead>
        <tr>
          <th>Country</th>
          <th>Cases</th>
          <th>Deaths</th>
          <th>Recovered</th>
        </tr>
      </thead>
      <tbody>
      </tbody>
    </table>
  </div>
  <div class="arrow">
    <div class="arrow__up">
    </div>
    <div class="arrow__down">
    </div>
  </div>
</div>
 
  <script src='https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.min.js'></script>
<script src='https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.min.js'></script>
<script src='https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/iamdustan-smoothscroll/0.4.0/smoothscroll.min.js'></script>
<script  src="function.js"></script>
 
</body>
</html>
