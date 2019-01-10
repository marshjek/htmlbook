<h1 id="bookmarkletscollection">Bookmarklets collection</h1>

<h2 id="howtoaddboomarklets">How to add Boomarklets</h2>

<p>Drag the "Drag me to your bookmarks bar" to your bookmark bar. If that doesn't work then click the star icon next to your extensions. A box will pop up and then you click more. Then where it says URL copy and paste the bookmarklet code. Then click save and your bookmarklet should be there.</p>

<h2 id="blockedbookmarklets">Blocked Bookmarklets</h2>

<p>Some bookmarklets are blocked as it loads json. Here is what you do if it is blocked: When you click on the bookmarklet a little shield with a X on it will appear next to the bookmark button. Click on that shield and it will tell you that the page is trying to load unathorized code or something along those lines. You click on load unsafe scripts and then the page will refresh. You then click on the bookmarklet again and it should load. On all of the bookmarklets that do this I will put blocked in parentheses next to it.</p>

<h2 id="asteroids">Asteroids</h2>

<p>This bookmarklet allows you to drive a spaceship around and destroy stuff. Use arrow keys to move and space to shoot stuff. </p>

<p><a href="javascript:var KICKASSVERSION='2.0';var s = document.createElement('script');s.type='text/javascript';document.body.appendChild(s);s.src='//hi.kickassapp.com/kickass.js';void(0);">Drag me to bookmarks bar.</a></p>

<p><img src="./Capture.PNG" alt="Picture" /></p>

<pre><code class="js language-js">javascript:var KICKASSVERSION='2.0';var s = document.createElement('script');s.type='text/javascript';document.body.appendChild(s);s.src='//hi.kickassapp.com/kickass.js';void(0);
</code></pre>

<h2 id="snake">Snake</h2>

<p>This allows you to play a miniuture game of snake anywhere! Use arrow keys to move and collect apples and P to pause/resume. Warning: After using this bookmarklet you will not be able type on the page you are on.</p>

<p><a href='javascript:Q=44;m=b=Q*Q;a=[P=l=u=d=p=S=w=0];u=89;f=(h=j=t=(b+Q)/2)-1;(B=(D=document).body).appendChild(x=D.createElement("p"));(X=x.style).position="fixed";X.left=X.top=0;X.background="#FFF";x.innerHTML="<p></p><canvas>";v=(s=x.childNodes)[0];(s=s[1]).width=s.height=5*Q;c=s.getContext("2d"); onkeydown=onblur=F=function(e,g){g?a[f]?(w+=m,f=Math.random(l+=8)*(R=Q-2)*R|(u=0),F(f+=Q+1+2*(f/R|0),g)):F(f):0>e?(l?--l:(y=t,t=a[t]-2,F(y)),S+=(w*=0.8)/4,m=999/(u++ +10),a[h+=[-1,-Q,1,Q][d=p]]?B.removeChild(x,alert("Game Over")):(F(h),F(e,j=h),v.innerHTML=P?(setTimeout(F,50,e,0),S|0):"Press P")):-e?(y=(a[e]=e<Q|e>=Q*Q-Q|!(e%Q)|e%Q==Q-1|2*(e==h))+(e==f),e==h&amp;&amp;(a[j]=2+h),c.fillStyle="hsl("+99*!a[e]+","+2*m+"%,"+50*y+"%)",c.fillRect(e%Q*5,5*(e/Q|0),5,5)):isNaN(y=e.keyCode-37)|43==y?(P=y&amp;&amp;!P)&amp;&amp;F(-1): p=!P|y&amp;-4|!(y^2^d)?p:y;return!1};for(;--b;F(b));void F(-1);'>Drag me to bookmarks bar.</a></p>

<p><img src="./CaptureSnake.PNG" alt="Picture" /></p>

<pre><code class="js language-js">javascript:Q=44;m=b=Q*Q;a=[P=l=u=d=p=S=w=0];u=89;f=(h=j=t=(b+Q)/2)-1;(B=(D=document).body).appendChild(x=D.createElement("p"));(X=x.style).position="fixed";X.left=X.top=0;X.background="#FFF";x.innerHTML="&lt;p&gt;&lt;/p&gt;&lt;canvas&gt;";v=(s=x.childNodes)[0];(s=s[1]).width=s.height=5*Q;c=s.getContext("2d"); onkeydown=onblur=F=function(e,g){g?a[f]?(w+=m,f=Math.random(l+=8)*(R=Q-2)*R|(u=0),F(f+=Q+1+2*(f/R|0),g)):F(f):0&gt;e?(l?--l:(y=t,t=a[t]-2,F(y)),S+=(w*=0.8)/4,m=999/(u++ +10),a[h+=[-1,-Q,1,Q][d=p]]?B.removeChild(x,alert("Game Over")):(F(h),F(e,j=h),v.innerHTML=P?(setTimeout(F,50,e,0),S|0):"Press P")):-e?(y=(a[e]=e&lt;Q|e&gt;=Q*Q-Q|!(e%Q)|e%Q==Q-1|2*(e==h))+(e==f),e==h&amp;&amp;(a[j]=2+h),c.fillStyle="hsl("+99*!a[e]+","+2*m+"%,"+50*y+"%)",c.fillRect(e%Q*5,5*(e/Q|0),5,5)):isNaN(y=e.keyCode-37)|43==y?(P=y&amp;&amp;!P)&amp;&amp;F(-1): p=!P|y&amp;-4|!(y^2^d)?p:y;return!1};for(;--b;F(b));void F(-1);
</code></pre>

<h2 id="wesiteedit">Wesite Edit</h2>

<p>This allows you to change text on any website. Simply click on the bookmarklet and then type where you want.</p>

<p><a href="javascript:document.body.contentEditable = 'true'; document.designMode='on'; void 0">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:document.body.contentEditable = 'true'; document.designMode='on'; void 0
</code></pre>

<h2 id="katamariblockedbydefault">Katamari (Blocked by default)</h2>

<p>This bookmarklet when clicked brings up a box that customizes your Katamari. Disabling realistic pickups means that you can pick up anything. Leaving it inabled means that you have to reach a certain size to pick up certain objects. This bookmarklet is blocked by default. Refer to the top of the page for more.</p>

<p><a href="javascript:var i,s,ss=['http://kathack.com/js/kh.js','http://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js'];for(i=0;i!=ss.length;i++){s=document.createElement('script');s.src=ss[i];document.body.appendChild(s);}void(0);">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:var i,s,ss=['http://kathack.com/js/kh.js','http://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js'];for(i=0;i!=ss.length;i++){s=document.createElement('script');s.src=ss[i];document.body.appendChild(s);}void(0);
</code></pre>

<h2 id="fontbombblockedbydefault">Fontbomb (Blocked by default)</h2>

<p>This allows you to blow up text and send it flying across the screen. When you click the bookmarklet there may be a slight delay. Just wait for a thing that slides down from the top of the screen. This bookmarklet is blocked by default. Refer to the top of this page for more.</p>

<p><a href="javascript:(function () {var s = document.createElement('script');s.setAttribute('src', 'http://fontbomb.ilex.ca/js/main.js');document.body.appendChild(s);}());">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function () {var s = document.createElement('script');s.setAttribute('src', 'http://fontbomb.ilex.ca/js/main.js');document.body.appendChild(s);}());
</code></pre>

<h2 id="killelement">Kill Element</h2>

<p>This allows you to delete elements such as ads. When you click on the Bookmarklet it will change your cursor to a + looking sign and then your ready to go. Be careful when clicking on ads to delete them as it might actually click on the ad and redirect you. </p>

<p><a href="javascript:for(var i=0; i&lt;(document.getElementsByTagName('a')).length; i++) {(document.getElementsByTagName('a')[i]).style.pointerEvents = 'none';}function handler(e) {e = e || window.event;var target = e.target || e.srcElement;target.style.display = 'none';document.removeEventListener('click', handler, false);cursor('default');for(var i=0; i&lt;(document.getElementsByTagName('a')).length; i++) {(document.getElementsByTagName('a')[i]).style.pointerEvents = 'initial';}}document.addEventListener('click', handler, false);cursor('crosshair');function cursor(cur) { document.body.style.cursor = cur; }">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:for(var i=0; i&lt;(document.getElementsByTagName('a')).length; i++) {(document.getElementsByTagName('a')[i]).style.pointerEvents = 'none';}function handler(e) {e = e || window.event;var target = e.target || e.srcElement;target.style.display = 'none';document.removeEventListener('click', handler, false);cursor('default');for(var i=0; i&lt;(document.getElementsByTagName('a')).length; i++) {(document.getElementsByTagName('a')[i]).style.pointerEvents = 'initial';}}document.addEventListener('click', handler, false);cursor('crosshair');function cursor(cur) { document.body.style.cursor = cur; }
</code></pre>

<h2 id="revealpassword">Reveal Password</h2>

<p>This bookmarklet when clicked on will reveal any passwords on the page. When I say that I mean it will clear those dot things.</p>

<p><a href="javascript:Array.prototype.slice.call(document.querySelectorAll('input[type=password]')).map(function(el){el.setAttribute('type','text')})">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:Array.prototype.slice.call(document.querySelectorAll('input[type=password]')).map(function(el){el.setAttribute('type','text')})
</code></pre>

<h2 id="piano">Piano</h2>

<p>This bookmarklet is probalbly one of the most complicated by far. This allows a working piano (playable) to appear anywhere complete with sound. Simply click the bookmarklet and it will appear at the bottom of your screen. The keys you press will appear at the base of the piano key. At the bottom left you will see tilt, pitch, and wave. I dont know what pitch and wave do, but tilt tilts the piano. On the bottom right you will see numbers 1-10 with a play button next to them. Those are saved presets of songs. Above that you will see a up arrow and down arrow, a X, and a rewind button with a play button next to it. The rewind button when clicked plays what you just played on the piano. The X button lets you delete any one of the presets including the rewind. The up arrow lets you create a preset of what you just played (What was in the rewind.) As far as I am aware there is no way to save the presets that you create. I do not know what the down arrow does currently.</p>

<p><a href='javascript:(function(){var js=document.body.appendChild(document.createElement("script"));js.onerror=function(){alert("Sorry, the script could not be loaded.")};js.src="https://rawgit.com/Krazete/bookmarklets/master/piano.js"})();'>Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function(){var js=document.body.appendChild(document.createElement("script"));js.onerror=function(){alert("Sorry, the script could not be loaded.")};js.src="https://rawgit.com/Krazete/bookmarklets/master/piano.js"})();
</code></pre>

<h2 id="alert">Alert</h2>

<p>This bookmarklet is the most simple. It simply opens a box that has text in it. The text is also customizable (Area between the quotes).</p>

<p><a href='javascript:alert("Heckle deckle dee, thats quite the fee.");'>Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:alert("Heckle deckle dee, that's quite the fee.");
</code></pre>

<h2 id="changefont">Change Font</h2>

<p>This allows you to change the font on a webpage. It works better on some than other, but it should work to some extent. The directions and avalible fonts are included in the bookmarklet.</p>

<p><a href='javascript:function font_c(){var f_name=prompt("Enter the name of font! (no caps) \n For list of fonts visit http://goo.gl/I06Lz");document.body.style.fontFamily=f_name;}font_c();'>Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:function font_c(){var f_name=prompt("Enter the name of font! (no caps) \n For list of fonts visit http://goo.gl/I06Lz");document.body.style.fontFamily=f_name;}font_c();
</code></pre>

<h2 id="fontname">Font Name</h2>

<p>This bookmarklet allows you to find the font that is on a webpage. Simply click the bookmarklet and then click on the text that you want to know. If you use this on anything google related (Docs, Slides, Google search, Scripts, ect.) then the font will be roboto. </p>

<pre><code class="js language-js">javascript:var d=document,b=d.body,s=d.createElement('style'),m;s.innerHTML='*{cursor:help !important;}';b.appendChild(s);b.addEventListener('click',l,0);function l(e){m=/"([^"]+)"|'([^']+)'|([^,]+)/.exec(window.getComputedStyle(e.target).fontFamily);alert('That font is '+(m[1]||m[2]||m[3]));b.removeChild(s);b.removeEventListener('click',l);e.preventDefault()}
</code></pre>

<h2 id="screenflip">Screen Flip</h2>

<p>This bookmarklet flips you screen 180 degrees (upside down.) </p>

<p><a href="javascript:(function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){document.body.style[prefix + 'transform'] = 'rotate(180deg)';});}())">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){document.body.style[prefix + 'transform'] = 'rotate(180deg)';});}())
</code></pre>

<h2 id="randomangle">Random Angle</h2>

<p>This allows you to select all elements on the webpage and tilt them at a random angle. You can press this bookmarklet more than once and get different angles.</p>

<p><a href="javascript:(function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){Array.prototype.slice.call(document.querySelectorAll('div,p,span,img,a,body')).map(function(el){el.style[prefix + 'transform'] = 'rotate(' + (Math.floor(Math.random() * 3) - 1) + 'deg)';});});}())">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){Array.prototype.slice.call(document.querySelectorAll('div,p,span,img,a,body')).map(function(el){el.style[prefix + 'transform'] = 'rotate(' + (Math.floor(Math.random() * 3) - 1) + 'deg)';});});}())
</code></pre>

<h2 id="fliptrap">Flip Trap</h2>

<p>This bookmarklet is similar to screen flip except it waits 5 seconds then waits for user input. That being typing or moving the mouse. It also has a animation.</p>

<p><a href="javascript:(function(){setTimeout(function(){document.onmousemove = document.onkeypress = function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){document.body.style[prefix + 'transition'] = prefix + 'transform 3s';document.body.style[prefix + 'transform'] = 'rotate(180deg)';});}}, 5000);}())">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function(){setTimeout(function(){document.onmousemove = document.onkeypress = function(){['', '-ms-', '-webkit-', '-o-', '-moz-'].map(function(prefix){document.body.style[prefix + 'transition'] = prefix + 'transform 3s';document.body.style[prefix + 'transform'] = 'rotate(180deg)';});}}, 5000);}())
</code></pre>

<h2 id="uglify">Uglify</h2>

<p>This simply uglifies your page. It changes random elements size and color. It also changes the font to Comic Sans MS. When you click anywhere on the page it starts spinning. The more you click the faster it goes.</p>

<p><a href="javascript:(function(){var elems=document.getElementsByTagName("*");for(var i = 0; i<elems.length;i++){elems[i].style.fontFamily="Comic Sans MS";elems[i].style.fontSize=Math.random()*75+"px";elems[i].style.color='#'+Math.random().toString(16).slice(2, 8);elems[i].style.backgroundColor='#'+Math.random().toString(16).slice(2,8)}})();document.onclick=function(){(function(){var d=0;setInterval(function(){document.body.style['-webkit-transform']= 'rotate('+ d +'deg)';d+=1},100)}());};">Drag me to bookmarks bar.</a></p>

<pre><code class="js language-js">javascript:(function(){var elems=document.getElementsByTagName("*");for(var i = 0; i&lt;elems.length;i++){elems[i].style.fontFamily="Comic Sans MS";elems[i].style.fontSize=Math.random()*75+"px";elems[i].style.color='#'+Math.random().toString(16).slice(2, 8);elems[i].style.backgroundColor='#'+Math.random().toString(16).slice(2,8)}})();document.onclick=function(){(function(){var d=0;setInterval(function(){document.body.style['-webkit-transform']= 'rotate('+ d +'deg)';d+=1},100)}());};
</code></pre>
