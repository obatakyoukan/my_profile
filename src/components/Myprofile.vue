<template>
 <div>
<el-container>
  <el-header> <h3>名前(name)</h3></el-header>
  <el-main> <h3>小畠 教寛<br /> Norihiro Obata </h3> </el-main>
</el-container>

<el-container>
  <el-header> <h3>所属</h3> </el-header>
  <el-main>
 <ul>

    <li> 
     <el-link href="https://www.hokudai.ac.jp/" type="primary">北海道大学</el-link>
     <el-link href="https://infoele.eng.hokudai.ac.jp/" type="primary">工学部情報エレクトロニクス科</el-link>
     <el-link href="https://www.ist.hokudai.ac.jp/divisions/csit/" type="primary">情報理工学コース</el-link>
     <el-link href="http://www-ikn.ist.hokudai.ac.jp" type="primary">情報知識ネットワーク研究室</el-link>
     (卒業)
    </li>
    <li> 
     <el-link href="https://www.hokudai.ac.jp/" type="primary">北海道大学</el-link>
     <el-link href="https://www.ist.hokudai.ac.jp/" type="primary">情報科学院</el-link>
     <el-link href="https://www.ist.hokudai.ac.jp/divisions/csit/" type="primary">情報理工学コース</el-link>
     <el-link href="http://www-ikn.ist.hokudai.ac.jp" type="primary">情報知識ネットワーク研究室</el-link>
     (2020/4~)
    </li>
  </ul>


  </el-main>
</el-container>

<el-container>
  <el-header> <h3>連絡先</h3></el-header>
  <el-main>
    oba.kyoukan[at]gmail.com
  </el-main>
</el-container>

<el-container>
  <el-header> <h3>研究分野</h3> </el-header>
  <el-main>
    グラフに対するアルゴリズム( algorithm for graph )
  </el-main>
</el-container>

<el-container>
<el-header> <h3>論文リスト</h3> </el-header>
<el-main> 
<ul>
<li>
<el-link href="https://github.com/obatakyoukan/paper/blob/main/%E5%8D%92%E8%AB%96.pdf" > 卒業論文 </el-link>
</li>
<li>
<el-link href="https://github.com/obatakyoukan/paper/blob/main/sigfpai114obata2020.pdf" > 
人工知能学会 第114回人工知能基本問題研究会(SIG-FPAI)
</el-link>
</li>
</ul>
</el-main>
</el-container>

<el-container>
  <el-header> <h3>制作物</h3> </el-header>
  <el-main>
    
 <ul>

    <li> 
     <el-link href="https://reading-recorder.firebaseapp.com/" type="primary"> 書籍管理アプリ (Vue.js version ) </el-link>
    </li>
    <li>
    <el-link href="https://readingrecorder.herokuapp.com/" type="primary"> 書籍管理アプリ (Ruby on rails version ) </el-link>
    </li>
 </ul>
 </el-main>
 
</el-container>




</div>
</template>


<script>
 export default {
  name: 'Myprofile',
 }
</script>


<style>
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 40px;
  }
  
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 40px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 40px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 40px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 40px;
  }
</style>
