<template>
  <div id="app">
    <div class="top">
      <div class="logo">
        <img src="./assets/hubei-images/hubei_logo.png" alt="">
      </div>
      <div class="tabs">
        <div class="tab" :class="{active_tab:chooseTab == 1}" @click="chooseTab=1">首页</div>
        <div class="tab" :class="{active_tab:chooseTab == 2}" @click="chooseTab=2">关于湖北</div>
        <div class="tab" :class="{active_tab:chooseTab == 3}" @click="chooseTab=3">湖北景点</div>
        <div class="tab" :class="{active_tab:chooseTab == 4}" @click="chooseTab=4">湖北美食</div>
      </div>
    </div>
    <div class="banner">
      <img src="./assets/hubei-images/banner.png" alt="">
    </div>
    <div class="about_hb">
      <div class="title">————&nbsp;&nbsp;&nbsp;关于湖北&nbsp;&nbsp;&nbsp;————</div>
      <div class="info">
        <div class="l_pic">
          <img src="./assets/hubei-images/bg.png" alt="">
        </div>
        <div class="r_intro">
          <p>湖北</p>
          湖北省，简称“鄂”，中华人民共和国省级行政区，省会武汉。地处中国中部地区，东邻安徽，西连重庆，西北与陕西接壤，南接江西、湖南，北与河南毗邻，介于北纬29°01′53″—33°6′47″、东经108°21′42″—116°07′50″之间，东西长约740千米，南北宽约470千米，总面积18.59万平方千米，占中国总面积的1.94%。最东端是黄梅县，最西端是利川市，最南端是来凤县，最北端是郧西县。
        </div>
      </div>
    </div>
    <div class="scenery">
      <div class="title">————&nbsp;&nbsp;&nbsp;湖北景点&nbsp;&nbsp;&nbsp;————</div>
      <div class="info">
        <div class="item">
          <div class="l_pic">
            <img src="./assets/hubei-images/huanghelou.png" alt="">
          </div>
          <div class="r_intro">
            <p>黄鹤楼</p>
            黄鹤楼，位于湖北省武汉市武昌区，地处蛇山之巅，濒临万里长江，为武汉市地标建筑；始建于三国吴黄武二年（223年），历代屡加重修，现存建筑以清代“同治楼”为原型设计，重建于1985年；因唐代诗人崔颢登楼所题《黄鹤楼》一诗而名扬四海。自古有“天下绝景”之美誉，与晴川阁、古琴台并称为“武汉三大名胜”，与湖南岳阳岳阳楼、江西南昌滕王阁并称为“江南三大名楼”，是“武汉十大景”之首、中国古代四大名楼之一、“中国十大历史文化名楼”之一，世称"天下江山第一楼"。
          </div>
        </div>
        <div class="item">
          <div class="l_pic">
            <img src="./assets/hubei-images/wudangshan.png" alt="">
          </div>
          <div class="r_intro">
            <p>武当山</p>
            武当山，中国道教圣地，又名太和山、谢罗山、参上山、仙室山，古有“太岳”、“玄岳”、“大岳”之称。位于湖北省西北部十堰市丹江口市。东接襄阳市，西靠十堰市 ，南望神农架，北临南水北调中线源头丹江口水库。
明代，武当山被皇帝封为“大岳”、“治世玄岳”，被尊为“皇室家庙”。武当山以“四大名山皆拱揖，五方仙岳共朝宗”的“五岳之冠”地位闻名于世 [1]  。武当山是道教名山和武当武术的发源地，被称为“亘古无双胜境，天下第一仙山”。武当武术，是中华武术的重要流派。元末明初，道士张三丰集其大成，开创武当派 [1]  。截至2013年，武当山有古建筑53处，建筑面积2.7万平方米，建筑遗址9处，占地面积20多万平方米，全山保存各类文物5035件。
          </div>
        </div>
      </div>
    </div>
    <div class="foods">
      <div class="title">————&nbsp;&nbsp;&nbsp;湖北美食&nbsp;&nbsp;&nbsp;————</div>
      <div class="info">
        <div class="item">
          <div class="t_pic">
            <img src="./assets/hubei-images/zhangguanhezha.png" alt="">
          </div>
          <div class="b_intro">
            <p>张关合渣</p>
            合渣，又名懒豆腐。恩施土家人对合渣有着深厚的感情，特别是在兵荒马乱之年，由于粮食奇缺，合渣救下了不少人的性命，流传有“辣椒当盐，合渣过年”的民谚。
如今，恩施人吃合渣已不是逢年过节才能吃的“奢侈品”了，平时在家里都能吃上合渣，许多餐馆更是把它当成一道特色菜上桌供应，深受顾客的青睐。
          </div>
        </div>
        <div class="item">
          <div class="t_pic">
            <img src="./assets/hubei-images/shennongjialarou.png" alt="">
          </div>
          <div class="b_intro">
            <p>神农架腊肉</p>
            神农架腊肉是一种利用猪肉、牛肉等制作成的腊肉，是神农架人逢年过节必备的特色美食，深得当地百姓及游客的喜爱。 原料：猪肉、牛肉、猪肠、猪肝、排骨、猪蹄、打算、辣椒等。 神农架腊肉具有味道鲜美，蛋白质丰富的特点，而且容易保存。制作完成之后烧汤、爆炒，也可以做成火锅，有一丝淡淡的香味。时间越长，味道越足。
          </div>
        </div>
        <div class="item">
          <div class="t_pic">
            <img src="./assets/hubei-images/doupi.png" alt="">
          </div>
          <div class="b_intro">
            <p>豆皮</p>
            豆皮是湖北省武汉市的著名小吃之一，一般在街头巷尾各早餐摊位供应，中午或晚上在一些特殊的餐厅或老字号饭店也有提供。现在许多的豆皮都被作为制作为一道道不同的菜上了餐桌，而且现在许多地方的人也都接受了这种食品的存在。
          </div>
        </div>
      </div>
    </div>
    <div class="bottom">
      Copyright@湖北旅游网站
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      chooseTab: 1
    }
  }
}
</script>

<style>
#app {
  background-color: #f4e2d2;
  height: 100%;
}
.top {
  width: 100%;
  background: #f4c9a1;
  height: 60px;
  padding: 0 80px;
  display: flex;
  align-items: center;
  box-sizing: border-box;
}
.top .logo {
  height: 100%;
  margin-right: 40px;
}
.top img {
  height: 100%;
}
.top .tabs {
  display: flex;
}
.top .tab {
  margin: 0 20px;
  cursor: pointer;
}
.active_tab {
  color: red;
}
.banner {
  padding: 0 80px;
  margin-bottom: 15px;
}
.banner img {
  width: 100%;
  height: 310px;
}
.about_hb,.scenery,.foods {
  padding: 0 80px;
}
.about_hb .title,.scenery .title,.foods .title {
  text-align: center;
  color: #d74326;
  font-size: 25px;
}
.about_hb .info,.scenery .item {
  height: 310px;
  display: flex;
  align-items: center;
  margin: 15px 0;
}
.about_hb .info .l_pic,.scenery .l_pic {
  height: 310px;
}
.about_hb .info img,.scenery .info img {
  width: 540px;
  height: 100%;
}
.about_hb .info .r_intro,.scenery .r_intro {
  box-sizing: border-box;
  height: 310px;
  padding: 30px 40px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  background: #fff;
}
.about_hb .info .r_intro p {
  font-size: 30px;
  margin: 0;
  margin-bottom: 15px;
}
.scenery .l_pic {
  height: 200px;
}
.scenery .info img {
  width: 350px;
}
.scenery .item {
  height: 200px;
}
.scenery .r_intro {
  padding: 10px 20px;
  font-size: 16px;
  height: 200px;
}
.scenery .r_intro p {
  margin: 0;
  font-weight: 700;
  margin-bottom: 8px;
  font-size: 23px;
}
.foods {
  padding-bottom: 40px;
}
.foods .info {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.foods .item {
  width: 30%;
  height: 480px;
  background: #fff;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}
.foods .title {
  margin-bottom: 15px;
}
.foods .t_pic {
  width: 100%;
}
.foods img {
  width: 100%;
  height: 240px;
}
.foods .b_intro {
  font-size: 16px;
  padding: 0 15px;
}
.foods .b_intro p {
  margin: 0;
  font-size: 20px;
  font-weight: 700;
  margin-bottom: 5px;
}
.bottom {
  height: 60px;
  line-height: 60px;
  text-align: center;
  color: #fff;
  background: #2c2c2c;
}
</style>