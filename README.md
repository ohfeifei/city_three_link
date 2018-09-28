# city_three_link
angular2+ Directive typescript

地区数据来自https://github.com/itmyhome2013/national-cities-three-linkage, 做了angular2 directive封装，包含全国大多数省市区

使用

  .html
  
  <app-threelink (notify)="getAddr($event)"></app-threelink>
  
  .ts
  
  getAddr(e) {
    console.log(e); //{ province: "重庆市", city: "重庆市", zone: "江北区" }
  }
  
  ![image](https://github.com/ohfeifei/city_three_link/blob/master/Screenshot%20from%202018-09-28%2011-55-59.png)
  
