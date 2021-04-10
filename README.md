# View-installation-of-GCC-C-C-Compiler-on-windows-10-
<!-- wp:paragraph -->
<p>In this article we will learn that how to install <strong>gcc</strong> windows 10. Download and  install gcc windows. GCC is compiler for C/C++ language.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>This post about how to install gcc ?</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Visual Studio Express and the system GCC compiler included in several modern Linux distributions still lack many modern C++ features. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>One such function is generic lambdas, also known as polymorphic lambdas. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>However, this function is included in the most recent versions of GCC and Clang.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The instructions below will take you through downloading the most current version of GCC on Windows, allowing you to play with generic lambdas and other cutting-edge C++ features. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>You'll have to compile GCC from source, but that shouldn't be a concern.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":5} -->
<h5><strong>These topics we will cover in this article :--</strong></h5>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li><strong>What is compiler ?</strong></li><li><strong>What is MinGW and GCC ?</strong></li><li><strong>Download and install MinGW Compiler on windows </strong>.</li><li><strong>Verify the installation.</strong></li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":4} -->
<h4><strong>Introduction</strong> <strong>:--</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>What is compiler ?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>A compiler is a computer program&nbsp;&nbsp;that transforms code written in one programming language into code written in another. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The term "compiler" refers to programs&nbsp;that convert source code from a high-level programming language to a lower-level programming language in order to produce an executable program.</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Compiler is a program that processes a statement written in particular programming language.</li><li>A computer is not take source code directly. So ,a compiler takes our written <strong>code</strong> and covert into <strong>Machine</strong> <strong>code</strong> that a computer's system process.</li><li>Example : <strong>MinGW GCC Compile</strong>r for <strong>C/C++ </strong>,  <strong>Java JDK</strong> for <strong>Java.</strong></li><li>There are three types of compilers :- <strong>1.Single Pass Compiler , 2. Two Pass Complier and 3. Multi pass Compiler </strong></li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":4} -->
<h4><strong>What is MinGW and GCC ?</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>MinGW (formerly mingw32) is a free and open source software development environment for creating Microsoft Windows applications. With the launch of the Mingw-w64 project in 2005–2008, the progress of the MinGW project was split in two.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>MinGW provides a Windows native build of the GNU Compiler Collection (GCC), GNU Binutils for Windows (assembler, linker, archive manager), a series of freely distributable Windows related header files and static import libraries that allow the use of the Windows API, and miscellaneous utilities.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>MinGW does not depend on a third-party dynamic-link library (DL) for C runtime.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Since the runtime libraries are not distributed under the GNU General Public License (GPL).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p> It is not mandatory to share the source code for the program generated, unless a GPL library is included elsewhere in the software.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>MinGW can run natively on Microsoft Windows, cross-hosted on Linux (or other Unix), or "cross-natively" on Cygwin.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p> Despite the fact that MinGW program are 32-bit executables, they can be found in both 32-bit and 64-bit models of Windows.</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li><strong>MinGW</strong> stands for Minimal GNU for Windows.</li><li><strong>MinGW</strong> contains <strong>GCC</strong> which in the collection of GNU free Software.</li><li><strong>It is a GCC-based compiler that compiles and connects windows code.</strong></li><li>Uses the Microsoft runtime libraries.</li><li>distributed with the Windows operating system.</li><li><strong>GCC</strong>&nbsp;stands for <strong>GNU</strong> Compiler Collections.</li><li>Used to compile <strong>C</strong> and <strong>C++</strong> language.&nbsp;</li><li><strong>GCC</strong>&nbsp;can compile any <strong><strong>.C</strong></strong> or<strong> .CPP</strong> files but they'll be considered <strong>C</strong> and <strong>C++</strong>, respectively.</li><li>Any <strong>.C</strong>  or <strong><strong>.CPP</strong></strong> files can be compiled with <strong>g++</strong> , but they will only be handled as <strong>C++</strong> files.</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":4} -->
<h4><strong>Download and install MinGW/gcc Compiler on windows ?</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>MinGW-w64 is a fork of MinGW that is designed to run on 64-bit Windows (as well as the 32-bit windows). http://mingw-w64.org/doku.php is the mother port.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>GNU is a source of open source programming software, and MinGW stands for Minimalist GNU for Windows (GNU stands for GNU is Not Unix).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In this handout, you'll get the files you'll need for GNU C++, and in the next, you'll get a version of Eclipse that's already configured to work with MinGW.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Before you started, you might want to print these instructions so that you can refer to them when downloading and installing MinGW.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p> Alternatively, you should simply bookmark this page in your browser. Until executing the action mentioned in - step, make sure you read it absolutely.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":4} -->
<h4><strong>Download MinGW :--</strong></h4>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>To Download MinGW <a href="https://sourceforge.net/projects/mingw/files/">Click here</a>. Following Screen appear after open this link in new tab. </li></ul>
<!-- /wp:list -->

<!-- wp:image {"id":1247,"linkDestination":"none"} -->
<figure class="wp-block-image"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-164646.jpg" alt="" class="wp-image-1247"/></figure>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Click on <strong>'mingw-get-setup.exe(86.5 kb)' . </strong>This is  MinGW installer setup.</li></ul>
<!-- /wp:list -->

<!-- wp:list -->
<ul><li>Following Screen appear . The file will starting automatically download in standard download folder. It will download quickly.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1249,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-165502-1.jpg" alt="install gcc windows" class="wp-image-1249"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Go into your downloads folder and run the <strong>.exe</strong> file.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1250,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-170427.jpg" alt="install gcc windows" class="wp-image-1250"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li> popup appear on screen. Click on <strong>yes</strong>.</li></ul>
<!-- /wp:list -->

<!-- wp:list -->
<ul><li>Following window appear on screen.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1251,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-170446.jpg" alt="install gcc windows" class="wp-image-1251"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Click on <strong>Install</strong>.</li><li>Install on default directory or change if you want to change. Click  <strong>Continue</strong>.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1252,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-170504.jpg" alt="change drectory" class="wp-image-1252"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Download is in process. MinGW is downloading required filles. </li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1253,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-170523.jpg" alt="" class="wp-image-1253"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Click <strong>Continue</strong> download is completed.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1254,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-170632.jpg" alt="" class="wp-image-1254"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Following window will appear after download is complete . check on <strong>mingw32-base</strong> , <strong>mingw32-gcc-g++</strong> and <strong>msys-base</strong>.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1255,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-171033.jpg" alt="" class="wp-image-1255"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>After click on checkbox click on installation and click on <strong>Apply</strong>.</li><li>Following window will appear. Download is started. This is final installation.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"id":1256,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-171128.jpg" alt="" class="wp-image-1256"/></figure>
<!-- /wp:image -->

<!-- wp:image {"align":"center","id":1257,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-171246.jpg" alt="" class="wp-image-1257"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Than close the window and go in the installation directory <strong>C:\MinGW</strong> .</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1259,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172436-1.jpg" alt="" class="wp-image-1259"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Go into <strong>bin</strong> folder. click on address bar and copy the path <strong>C:\MinGW\bin</strong>.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"id":1261,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-180034.jpg" alt="" class="wp-image-1261"/></figure>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Go to <strong>System properties</strong>. </li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1262,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172755-1.jpg" alt="" class="wp-image-1262"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Than go to<strong> Advanced system settings</strong>. </li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1263,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172818.jpg" alt="" class="wp-image-1263"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Click on <strong>Environment variables</strong> to go into path setttings.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1264,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172818-1.jpg" alt="install gcc windows" class="wp-image-1264"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Press click on <strong>Path</strong> and than click on <strong>Edit</strong> to add GCC to path.  </li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1267,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172853-1.jpg" alt="install gcc windows" class="wp-image-1267"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Click on <strong>New</strong> to create new path .</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1265,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172913.jpg" alt="install gcc windows" class="wp-image-1265"/></figure></div>
<!-- /wp:image -->

<!-- wp:list -->
<ul><li>Paste the path copied you and click <strong>ok.</strong> Now everything is ok. MinGW is successfully installed and added to path. Now you verify that MinGW is working or not. </li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1269,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-172953.jpg" alt="install gcc windows" class="wp-image-1269"/></figure></div>
<!-- /wp:image -->

<!-- wp:heading {"level":4} -->
<h4><strong>Verify the installation :--</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Now everything is ok. Now verify that the MinGW was successfully install on your computer.</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Open <strong>cmd </strong>and type command <strong>gcc. </strong> The following window will appear after this command.</li><li>You should get output : <kbd>gcc: no input files</kbd>.&nbsp;it means that the <strong>gcc</strong> successfully installed in your computer. If you get other output try again this process and verify again.</li><li>Download any code editor or IDE and lets start coding.</li></ul>
<!-- /wp:list -->

<!-- wp:image {"align":"center","id":1270,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="aligncenter size-large"><img src="http://pcbloggers.com/wp-content/uploads/2021/03/Screenshot-2021-03-20-173851.jpg" alt="gcc" class="wp-image-1270"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Thank you for visiting our website and reading this blog post. We hope that this post was very helpful for you. If you think this post was helpful for you , please share it. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Give us your feedback in comments. Continue visit our website to get daily more helpful posts. Thank you again.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>For more helpful posts and updates please keep visiting our website.</p>
<!-- /wp:paragraph -->

To see new posts <a href="http://pcbloggers.com/install-gcc-windows-how-to-install-gcc-for-windows/" >Click here </a>
