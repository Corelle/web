# web<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <title>Rabbit : Home</title>
        <link rel="icon" type="image/icon" href="assets/images/tabicon.ico">

        <link rel="stylesheet" type="text/css" href="">
        <link href="assets/css/bootstrap.min.css" rel="stylesheet">
        <link href="assets/css/bootstrap-theme.min.css" rel="stylesheet">
        <link href="assets/css/font-awesome.min.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,400i,600,700,700i" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Crimson+Text:400,700,700i|Josefin+Sans:700" rel="stylesheet">
        <link href="assets/css/main.css" rel="stylesheet">
        <link rel="icon" href="assets/images/logo.png">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
        
    </head>

    <body>
        <div id="index">                                           <!-- Index starts here -->
            <div class="container main">
                <div class="row home">
                    <div id = "index_left" class="col-md-6 left">
                        <img class="img-responsive img-rabbit" src="assets/images/home.jpg">
                    </div>
                    <div id = "index_right" class="col-md-6 text-center right">
                        <div class="logo">
                            <img src="assets/images/logo.png">
                            <h4>A robat?</h4>
                        </div>
                        <p class="home-description">
							Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic aspernatur porro optio nemo accusamus magni delectus labore reprehenderit iure. Itaque aut at tempore architecto impedit illo magnam nobis quaerat delectus?
                        </p>
                        <div class="btn-group-vertical custom_btn animated slideinright">
                            <div id="about" class="btn btn-rabbit">个人简介</div>
                            <div id="work" class="btn btn-rabbit">项目经验</div>
                            <div id="contact" class="btn btn-rabbit">联系方式</div>
                        </div>      
                        <div class="social">
                            <a href="#" title="QQ:171076262"><i class="fa fa-qq" aria-hidden="true"></i></a>
                            <a href="#" title="WeChat:15398872763"><i class="fa fa-weixin" aria-hidden="true"></i></a>
                            <a href="#" title="E-mail:171076262@qq.com"><i class="fa fa-envelope-o" aria-hidden="true"></i></a>
                        </div>
                    </div>
               		<!--<div id="outer" class="col-md-10" style="position: fixed;background: rgba(0,0,0,0.6);">
	           			<div style="height: 10%;"><a href="" style="float: right;"><i class="fa fa-remove fa-3x"></i></a></div>
	           			<div style="height: 350px;width: 600px;text-align: center;background:gray;border-radius: 20px;">
	           				<img src="" alt="" />
	           				<div></div>
	           				<div></div>
	           			</div>
	           		</div>-->
                </div>
				
                
            </div>
        </div>                                                      <!-- index ends here -->

        <div id="about_scroll" class="pages ">                      <!-- about strats here  -->
            <div class="container main">
                <div class="row">
                    <div class="col-md-6 left" id="about_left">
                        <img class="img-responsive img-rabbit" src="assets/images/about.jpg">
                    </div>

                    <div class="col-md-6 right" id="about_right">
                        <a href="#index" class="btn btn-rabbit back"> <i class="fa fa-angle-left" aria-hidden="true"></i> Back to home </a>
                        <div id="watermark">
                            <h2 class="page-title" text-center>About</h2>
                            <div class="marker">a</div>
                        </div>
                        <p class='subtitle'>Hi, I am chris Howard. A freelance web designer, front-end developer and digital planner based in US.
                        </p>
                        <p class="info">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."</p>  
                    </div>
                </div>
            </div>            
        </div>                                                                <!-- About ends here -->

        <div id="work_scroll" class="pages">                                  <!-- Work starts here -->
            <div class="container main">
                <div class="row">
                    <div class="col-md-6" id="work_left">
                        <div id="owl-demo" class="owl-carousel owl-theme">
                            <div class="item"><img class="img-responsive img-rabbit" src="assets/images/work.jpg"></div>
                            <div class="item"><img class="img-responsive img-rabbit" src="assets/images/home.jpg"></div>
                            <div class="item"><img class="img-responsive img-rabbit" src="assets/images/contact.jpg"></div>
                        </div>
                    </div>

                    <div class="col-md-6" id="work_right">
                        <a href="#index" class="btn btn-rabbit back"> <i class="fa fa-angle-left" aria-hidden="true"></i> Back to Home </a>
                        <div id="watermark">
                            <h2 class="page-title" text-center>Work</h2>
                            <div class="marker">w</div>
                        </div>
                        <p class='subtitle'>This is a selection of my web design and development work. I've been involve in many different types of project.
                        </p>
                        <p class="info">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.</p>
                    </div>
                </div>
            </div>    
        </div>                                                                 <!-- Work ends here  -->


        <div id="contact_scroll" class="pages">                             <!-- Contact starts here -->
            <div class="container main">
                <div class="row">
                    <div class="col-md-6 left" id="contact_left">
                        <img class="img-responsive img-rabbit" src="assets/images/contact.jpg">
                    </div>

                    <div class="col-md-6 right" id="contact_right">
                        <a href="#index" class="btn btn-rabbit back"> <i class="fa fa-angle-left" aria-hidden="true"></i> Back to Home </a>
                        <div id="watermark">
                            <h2 class="page-title" text-center>联系方式</h2>
                            <div class="marker">c</div>
                        </div>
                        <p class='subtitle'>I'm based in cheltenham in the UK, not far from Bristol, Birmingham, Oxford and Swindom. Drop me a line.
                        </p>
                        <!-- form -->
                        <form class="form_edit"> 
                            <div class="form-group">
                              	<p>姓名：Corelle</p>
                            </div>

                            <div class="form-group">
                           		<p>手机号：15398872763</p>
                            </div>

                            <div class="form-group">
                        		<p>邮箱：171076262@qq.com</p>
                            </div>
                            <button type="submit" class="btn btn-rabbit submit">发送</button>
                        </form>
                    </div>
                </div>
            </div>
       
            <footer class="text-center">
                <div class="container bottom">
                    <div class="row">
                        <div class="col-sm-12">
                            <p>Made with <i class="fa fa-heartbeat" aria-hidden="true"></i> by <a href="#">Themewagon</a> More Templates <a href="http://www.cssmoban.com/" target="_blank" title="模板之家">模板之家</a> - Collect from <a href="http://www.cssmoban.com/" title="网页模板" target="_blank">网页模板</a></p>
                        </div>
                    </div>
                </div>
            </footer>
            
        </div>                                                              <!-- Contact ends here -->
        
        <script src="assets/js/jquery-3.1.0.min.js"></script>
        <script src="assets/js/bootstrap.min.js"></script>
        <script src="assets/js/script.js"></script>
    </body>
</html>
