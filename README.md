body{
    font-family: 'Titillium Web', sans-serif;
}

h1 { font-size: 66px; font-weight: 600; line-height: 80px;
color: skyblue;
}
h2{ font-size: 48px; margin-bottom: 30px;}

p {
    font-size: 18px;
    color: #999999;
    line-height: 1.8;
    margin-bottom: 0;
}

section {
    padding: 120px;
}



.topmargin-xs { margin-top: 15px; }
.topmargin-sm { margin-top: 30px; }
.topmargin-lg { margin-top: 60px; }

.btn {
    font-size: 14px;
    padding: 15px 26px;
    min-width: 160px;
    border-radius: 2px;
    display: inline-block;
}

.btn-ligth {
    background-color: #ffffff;
    color: #1a1a1a;
    border: 2px solid #ffffff;
}

.navbar{
    background-color: white;
    box-shadow: 0 2px 4px 0 rgba(0, 0, .05);
    min-height: 100px;
}

.nav-link{color:black;}
.nav-link:hover {color: #1a1a1a;}

.logo-brand {
    min-width: 160px;
    max-width: 100px;
}

.logo-brand {color: #1a1a1a;
    
}

#hero {
    background-image: url('images/20191019_134916.jpg');
    background-size: cover;
    padding-top: 200px;
    min-height: 700px;
    color: #ffffff;

}

.content-center {
    max-width: 880px;
    margin: 0 auto 60px auto;
    text-align: center; 


}

.Blog-center { 
    position: relative;
    overflow: hidden;
    margin: 10px;
    border-radius: 2px;
}

.Blog-details {
    position: absolute ;
    bottom: 25px;
    left: 25px;
    z-index: 9000;
}

.Blog-details a h2, .Blog-details a p {
    color: #ffffff;
}
}


@media (max-width: 575.98px) { 
    h1{font-size: 40px; line-height: normal;}
 }


@media (min-width: 576px) and (max-width: 767.98px) { ... }


@media (min-width: 768px) and (max-width: 991.98px) { ... }


@media (min-width: 992px) and (max-width: 1199.98px) { ... }


@media (min-width: 1200px) { ... }
