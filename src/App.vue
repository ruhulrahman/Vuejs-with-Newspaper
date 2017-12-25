<template>
  <div id="news_app">
       <section id="header" class="text-center">
    <div class="container">
      <div class="row">
      <div class="col-md-8">
         <div class="logo">
         <img src="dist/images/logo.png"/>
         </div>
         <div class="date">
         <p> ঢাকা, সোমবার, ০৭ নভেম্বর ২০১৬, ২৩ কার্তিক ১৪২৩, ০৬ সফর ১৪৩৮</p>
         </div>
      </div>
       <div class="col-md-4">
         <div class="search">
        <form class="navbar-form navbar-left" role="search">
          <div class="form-group">
          <input type="text" class="form-control" placeholder="কী খুঁজতে চান? ">
          </div>
         <button type="submit" class="btn btn-default">অনুসন্ধান</button>
        </form>
         </div>
       </div>
     </div>
     </div>
     </section>


  <section id="menu">
     <div class="container">
       <nav class="navbar navbar-default">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          </button>
          
        </div>
        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
         <ul class="nav navbar-nav navbar-left">
          <li><a href="#">প্রচ্ছদ</a></li>
          <li><router-link to="/" exact>Home</router-link></li>
          <li><router-link to="/page">Single Page</router-link></li>
          <li><router-link to="/cat">Category</router-link></li>
          <li><a href="#">জাতীয়</a></li>
          <li><a href="#">আন্তর্জাতিক</a></li>
          <li><a href="#">অর্থনীতি</a></li>
          <li><a href="#">খেলার মাঠ</a></li>
          <li><a href="#">বিনোদন</a></li>
          <li><a href="#">ফিচার</a></li>
          <li><a href="#">বিজ্ঞান ও প্রযুক্তি</a></li>
          <li><a href="#">লাইফস্টাইল</a></li>
          <li><a href="#">মতামত</a></li>
          <li><a href="#">জীবনযাপন</a></li>
          <li class="dropdown">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">আরও...<span class="caret"></span></a>
            <ul class="dropdown-menu">
            <li><a href="#">আর্কাইভ</a></li>
            <li><a href="#">ছবি</a></li>
            <li><a href="#">ভিডিও</a></li>
            <li><a href="#">শিক্ষা</a></li>
            <li><a href="#">আমরা</a></li>
            <li><a href="#">শিল্প ও সাহিত্য</a></li>
            <li><a href="#">পাঁচমিশালি</a></li>
            <li><a href="#">বিশেষ সংখ্যা</a></li>
            </ul>
          </li>
         </ul>
        </div><!-- /.navbar-collapse -->

        </nav>
        </div><!-- /.container-fluid -->
      </section>
    <section id="breakingnews">
     <div class="container">
        <div class="row">
        <div class="col-md-12">
         <div class="brekeing_news">শিরোনাম :</div>
                <div class="breakings">
            <marquee height="25px" truespeed="truespeed" scrolldelay="10" scrollamount="1" 
            onmouseover="this.stop();" onmouseout="this.start();" direction="left" behavior="scroll"
            align="top">
              প্রধানমন্ত্রীর আজ টুঙ্গিপাড়া যাচ্ছেন   |  প্রথম নারী প্রেসিডেন্ট নাকি উদ্ধত ধনকুবের  |  জাতীয় পার্টি থেকে আরও দুজনের পদত্যাগ  |
              সেলফির প্রত্তুত্তর দিলেন নেত্রীরা   |  রাবির শিক্ষক তানভিরের ফেসবুক স্ট্যাটাস  |  অনুমোদনহীন পণ্য বিক্রির অভিযোগে আবারও স্বপ্নকে জরিমানা  |
            </marquee>
          </div>  
        </div>
        </div>
      </div>
      </section>


  <router-view></router-view>







    <section id="maincontent">
       <div class="container">
         <div class="footer_top">
          <div class="row">
          <div class="col-md-3">
            <div class="footer_logo">
              <img src="dist/images/logo.png"/>               
             </div>
            </div>
          <div class="col-md-3">
            <div class="footer_logo">
              <p>© সর্বস্বত্ব স্বত্বাধিকার সংরক্ষিত</p>
              <p> বাংলা নিউজ ২০১৬</p>             
              </div>
            </div>      
          <div class="col-md-6">
            <div class="footer_right">
              <p>সম্পাদক ও প্রকাশক - মোহাম্মদ সাদেকুজ্জামান</p>
              <p>বাসা নং -৩৯১, রোড নং-২৯ , নিউ ডিওআইচএস মহাখালি, ঢাকা-১২০৬ |
                      মোবাইলঃ ০১৯১১-১৮৩১৮১, ই-মেইল: sdai@purpleitltd.com</p>               
              </div>
            </div>
        
          </div>
       </div>
       </div>
    </section>



    <section id="maincontent">
       <div class="container">
         <div class="footer">
          <div class="row">
        <div class="col-md-12">
          <div class="footer_logo">
           <p>এই ওয়েবসাইটের কোনো লেখা বা ছবি অনুমতি ছাড়া নকল করা বা অন্য কোথাও প্রকাশ করা সম্পূর্ণ বেআইনি</p>
            </div>
            </div>
        </div>
       </div>
       </div>
    </section>


  </div>
</template>

<script>

import VueRouter from 'vue-router'
import Home from './pages/Home.vue'
import Single_page from './pages/Single_page.vue'
import Category from './pages/Category.vue'


const routes = [
  { path: '/', component: Home },
  { path: '/page', component: Single_page },
  { path: '/cat', component: Category },
]

const router = new VueRouter({
  routes, // short for `routes: routes`
  mode: 'history'
})


export default {
  name: 'news_app',
  router,
}
</script>
