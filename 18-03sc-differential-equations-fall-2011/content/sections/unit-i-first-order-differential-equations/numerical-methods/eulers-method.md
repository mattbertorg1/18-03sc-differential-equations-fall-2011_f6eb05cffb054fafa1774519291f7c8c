---
about_this_resource_text: ''
course_id: 18-03sc-differential-equations-fall-2011
embedded_media:
- id: 3Play-3PlayYouTubeid-MP4
  media_location: LbKKzMag5Rc
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 22ae4bf319aab3e9f2fc7c7ad2130d69
- id: LbKKzMag5Rc.srt
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-i-first-order-differential-equations/numerical-methods/eulers-method/LbKKzMag5Rc.srt
  title: 3play caption file
  type: null
  uid: 89fb903b653e4158d1b8d19372ab923a
- id: LbKKzMag5Rc.pdf
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-i-first-order-differential-equations/numerical-methods/eulers-method/LbKKzMag5Rc.pdf
  title: 3play pdf file
  type: null
  uid: 6c7842cb982440de22d2982250f448e6
- id: Caption-3Play YouTube id-SRT
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 79fd1dc81a85730e23c59c90c8b7840d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1498e541d62fdacb1d7c750b831dc593
- id: Video-YouTube-Stream
  media_location: LbKKzMag5Rc
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Video-YouTube-Stream
  type: Video
  uid: 752a210208c047c923b27c12c8fb6a74
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/LbKKzMag5Rc/default.jpg
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 106058fdddeae80afa8a559aa67d1383
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.03S06/mit-ocw-18.03-lec2-07feb2003-220k_512kb.mp4
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6b9155f6a0c99d77d5fdcfa46fde0161
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id493274885
  parent_uid: f55763ae30b0c64c95f5e06e58ed1fdc
  title: Video-iTunes U-MP4
  type: Video
  uid: 1fba9f94b906df65ba9a826686617c77
inline_embed_id: 66186522eulersmethod18233548
layout: video
order_index: null
parent_uid: 54d03b408dd2738559db03f6f1ebac22
related_resources_text: ''
short_url: eulers-method
technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-i-first-order-differential-equations/numerical-methods/eulers-method
template_type: popup
title: Euler's Method
transcript: '<p><span m="20000">The topic for today is --</span> <span m="32000">Today
  we''re going to talk, I''m postponing the linear</span> <span m="35000">equations
  to next time. Instead, I think it''s a good</span> <span m="38000">idea, since in
  real life, most of the differential</span> <span m="42000">equations are solved
  by numerical methods to introduce</span> <span m="45000">you to those right away.
  Even when you see the compute</span> <span m="49000">where you saw the computer
  screen, the solutions being</span> <span m="53000">drawn. Of course, what really
  was</span> <span m="55000">happening was that the computer was calculating the solutions</span>
  <span m="59000">numerically, and plotting the points.</span></p><p><span m="63000">So,
  this is the main way, numerically,</span> <span m="65000">it is the main way differential
  equations are actually solved,</span> <span m="69000">if they are of any complexity
  at all.</span></p><p><span m="72000">So, the problem is, that initial value problem,</span>
  <span m="75000">let''s write up the first-order problem the way we talked about</span>
  <span m="80000">it on Wednesday. And now, I''ll specifically add</span> <span m="83000">to
  that, the starting point that you used when you did the</span> <span m="87000">computer
  experiments. And, I''ll write the starting</span> <span m="92000">point this way.
  So, y of x0 should be y0.</span></p><p><span m="95000">So, this is the initial</span>
  <span m="98000">condition, and this is the first-order differential</span> <span
  m="102000">equation. And, as you know,</span> <span m="104000">the two of them together
  are called an IVP,</span> <span m="108000">an initial value problem, which means
  two things,</span> <span m="111000">the differential equation and the initial value
  that you want</span> <span m="116000">to start the solution at. Okay, now, the method
  we are</span> <span m="123000">going to talk about, the basic method of which many</span>
  <span m="128000">others are merely refinements in one way or another,</span> <span
  m="134000">is called Euler''s method. Euler, who did,</span> <span m="139000">of
  course, everything in analysis, as far as I know,</span> <span m="145000">didn''t
  actually use it to compute solutions of</span> <span m="150000">differential equations.
  His interest was theoretical.</span></p><p><span m="156000">He used it as a method
  of proving the existence theorem,</span> <span m="160000">proving that solutions
  existed. But, nowadays,</span> <span m="164000">it''s used to calculate the solutions
  numerically.</span></p><p><span m="167000">And, the method is very simple to describe.</span></p><p><span
  m="171000">It''s so naive that you probably think that if you that living</span>
  <span m="175000">300 years ago, you would have discovered it</span> <span m="179000">and
  covered yourself with glory for all eternity.</span></p><p><span m="184000">So,
  here is our starting point, (x0, y0).</span></p><p><span m="187000">Now, what information
  do we have?</span></p><p><span m="190000">At that point all we have is the little
  line element,</span> <span m="194000">whose slope is given by f of (x, y).</span></p><p><span
  m="198000">So, if I start the solution,</span> <span m="201000">the only way the
  solution could possibly go would be to start</span> <span m="206000">off in that
  direction, since I have no other</span> <span m="210000">information. At least it
  has the correct</span> <span m="215000">direction at (x0, y0).</span></p><p><span
  m="216000">But, of course, it''s not likely to have the</span> <span m="220000">correct
  direction anywhere else. Now, what you do,</span> <span m="223000">then, is choose
  a step size. I''ll try just two steps of the</span> <span m="228000">method. That''s,
  I think,</span> <span m="230000">good enough. Choose a uniform step size,</span>
  <span m="233000">which is usually called h. And, you continue that solution</span>
  <span m="237000">until you get to the next point, which will be x0 + h,</span> <span
  m="242000">as I''ve drawn it on the picture.</span></p><p><span m="246000">So, we
  get to here. We stop at that point,</span> <span m="249000">and now you recalculate
  what the line element is here.</span></p><p><span m="252000">Suppose, here, the
  line element,</span> <span m="255000">now, through this point goes like that.</span></p><p><span
  m="258000">Well, then, that''s the new direction that you should start</span> <span
  m="262000">out with going from here. And so, the next step of the</span> <span m="266000">process
  will carry you to here. That''s two steps of Euler''s</span> <span m="270000">method.
  Notice it produces a broken</span> <span m="273000">line approximation to the solution.</span></p><p><span
  m="276000">But, in fact, you only see that broken line</span> <span m="279000">if
  you are at a computer if you are looking at the computer</span> <span m="283000">visual,
  for example, whose purpose is to illustrate</span> <span m="287000">for you Euler''s
  method. In actual practice,</span> <span m="290000">what you see is, the computer
  is simply</span> <span m="293000">calculating this point, that point, and the succession</span>
  <span m="297000">of points. And, many programs will just</span> <span m="299000">automatically
  connect those points by a smooth looking curve</span> <span m="304000">if that''s
  what you prefer to see.</span></p><p><span m="308000">Well, that''s all there is
  to the method.</span></p><p><span m="311000">What we have to do now is derive the
  equations for the</span> <span m="315000">method. Now, how are we going to do</span>
  <span m="318000">that? Well, the essence of it is how</span> <span m="321000">to
  get from the nth step to the n plus first</span> <span m="326000">step? So, I''m
  going to draw a picture</span> <span m="329000">just to illustrate that. So, now
  we are not at x0.</span></p><p><span m="334000">But let''s say we''ve already gotten
  to (xn,</span> <span m="337000">yn). How do I take the next step?</span></p><p><span
  m="340000">Well, I take the line element, and it goes up like that,</span> <span
  m="344000">let''s say, because the slope is this.</span></p><p><span m="347000">I''m
  going to call that slope A sub n.</span></p><p><span m="351000">Of course, A sub
  n is the value of the right hand side at the</span> <span m="356000">point (xn,
  yn), and we will need that in the</span> <span m="359000">equation, -- -- but I
  think it will be a</span> <span m="363000">little bit clearer if I just give it
  a capital letter at this</span> <span m="368000">point. Now, this is the new point,</span>
  <span m="370000">and all I want to know is what are its coordinates?</span></p><p><span
  m="374000">Well, the x n plus one is there.</span></p><p><span m="377000">The y
  n plus one is here.</span></p><p><span m="379000">Clearly I should draw this triangle,
  complete the triangle.</span></p><p><span m="383000">This side of the triangle,
  the hypotenuse has slope An.</span></p><p><span m="387000">This side of the triangle
  has length h.</span></p><p><span m="390000">h is the step size. Perhaps I''d better
  indicate</span> <span m="393000">that, actually put that up so that you know the
  word step.</span></p><p><span m="399000">It''s the step size on the x-axis, how
  far you have to go</span> <span m="404000">to get from each x to the next one.</span></p><p><span
  m="407000">What''s this? Well, if that slope has this,</span> <span m="411000">the
  slope An, this is h.</span></p><p><span m="413000">Then this must be h times An,
  the length of that side,</span> <span m="418000">in order that the ratio of the
  height to this width should be</span> <span m="423000">An. And, that gives us the
  method.</span></p><p><span m="427000">How do I get from, clearly, to get from xn
  to x n</span> <span m="432000">plus one, I simply add h.</span></p><p><span m="436000">So,
  that''s the trivial part of it.</span></p><p><span m="439000">The interesting thing
  is, how do I get the new</span> <span m="444000">y n plus one? And so, the best
  way to write</span> <span m="448000">it as, that y n plus one minus yn divided by
  h,</span> <span m="452000">well, sorry, y n plus one minus yn is this</span> <span
  m="456000">line, the same as the line h times An.</span></p><p><span m="463000">So,
  that''s the way to write it. Or, since the computer is</span> <span m="467000">interested
  in calculating y n plus one itself,</span> <span m="472000">put this on the other
  side. You take the old yn,</span> <span m="476000">the previous one, and to it,
  you add h times An.</span></p><p><span m="480000">And, what, pray tell,</span> <span
  m="483000">is An? Well, the computer has to be</span> <span m="487000">told that
  An is the value of f. So, now, with that,</span> <span m="491000">let''s actually
  write the Euler program, not the program,</span> <span m="495000">but the Euler--
  the Euler method equations,</span> <span m="499000">let''s just call it the Euler
  equations.</span></p><p><span m="502000">What will they be? First of all,</span>
  <span m="504000">the new x is the old x plus h.</span></p><p><span m="508000">The
  new y is just what I''ve written there,</span> <span m="511000">the old y plus h
  times a certain number,</span> <span m="514000">An, and finally,</span> <span m="518000">An
  has the value-- It''s the slope of the line</span> <span m="523000">element here,
  and therefore by definition,</span> <span m="527000">that''s f of (xn,yn).</span></p><p><span
  m="530000">So, if these three equations which define Euler''s method.</span></p><p><span
  m="535000">I assume in 1.00 you must be asked to, at some point,</span> <span m="540000">as
  an exercise in the term at one point to program the</span> <span m="545000">computer
  in C or whatever they''re using,</span> <span m="548000">Java, now, I guess, to
  do Euler''s method.</span></p><p><span m="554000">And, these would be the recursive
  equations that you</span> <span m="560000">would put in to do that. Okay, let''s
  try an example,</span> <span m="567000">then. So, what would be a good color</span>
  <span m="572000">for Euler? Well, a purple.</span></p><p><span m="575000">I assume
  nobody can see purple. Is that correct?</span></p><p><span m="580000">Can anyone
  in the back of the room see that that''s purple?</span></p><p><span m="586000">Okay.
  Sit closer.</span></p><p><span m="588000">So, let''s calculate. The example,</span>
  <span m="592000">I''ll use a simple example, but it''s not entirely trivial.</span></p><p><span
  m="600000">My example is going to be the equation, x squared minus y</span> <span
  m="603000">squared on the right hand side.</span></p><p><span m="607000">And, let''s
  start with y of zero equals one,</span> <span m="610000">let''s say. And so, this
  is my initial</span> <span m="613000">value problem, that pair of equations.</span></p><p><span
  m="616000">And, I have to specify a step size.</span></p><p><span m="618000">So,
  let''s take the step size to 0.1.</span></p><p><span m="620000">You choose the step
  size, or the computer does.</span></p><p><span m="624000">We''ll have to talk about
  that in a few minutes.</span></p><p><span m="627000">Now, what do you do? Well,
  I say this is a</span> <span m="631000">nontrivial equation because this equation,
  as far as I know,</span> <span m="636000">cannot be solved in terms of elementary
  functions.</span></p><p><span m="639000">So, this equation would be, in fact, a
  very good candidate</span> <span m="643000">for a numerical method like Euler''s.</span></p><p><span
  m="646000">And, you had to use it, or maybe it was the other way</span> <span m="650000">around,
  I forget. On your problem set,</span> <span m="653000">you drew a picture of the
  direction field and answered</span> <span m="657000">some questions about the isoclines,
  how the solutions</span> <span m="661000">behave. Now, the main thing I want you</span>
  <span m="664000">to get, this is not just for Euler''s, talking about Euler''s</span>
  <span m="668000">equations. But in general,</span> <span m="670000">for the calculations
  you have to do in this course,</span> <span m="673000">it''s extremely important
  to be systematic because if you are</span> <span m="677000">not systematic, you
  know, if you just scribble,</span> <span m="680000">scribble, scribble, scribble,
  scribble,</span> <span m="682000">you can do the work, but it becomes impossible
  to</span> <span m="685000">find mistakes. You must do the work in a form</span>
  <span m="688000">in which it can be checked, which you can look over it and</span>
  <span m="692000">find, and try to see where mistakes are if,</span> <span m="695000">in
  fact, there are any. So, I strongly suggest,</span> <span m="699000">this is not
  a suggestion, this is a command,</span> <span m="703000">that you make a little
  table to do Euler''s method by hand,</span> <span m="708000">I''d only ask you for
  a step or two, but since I''m just trying</span> <span m="713000">to make sure you
  have some idea of these equations and where</span> <span m="718000">they come from.
  So, first, the value of n,</span> <span m="722000">then the value of xn, then the
  value of the yn,</span> <span m="726000">and then, a couple of more columns which
  tell you how to do</span> <span m="731000">the calculation. You are going to need
  the value</span> <span m="735000">of the slope, and it''s probably a good idea,</span>
  <span m="738000">also, because otherwise you''ll forget it, to put in h An</span>
  <span m="743000">because that occurs in the formula.</span></p><p><span m="746000">All
  right, let''s start doing it.</span></p><p><span m="750000">The first value of n
  is zero. That''s the starting point.</span></p><p><span m="754000">At the starting
  point, (x0, y0), x has the value zero,</span> <span m="758000">and y has the value
  one, so, zero and one.</span></p><p><span m="762000">In other words, starting, I''m
  carrying out</span> <span m="765000">exactly what I drew pictorially only now I''m
  doing it</span> <span m="769000">arithmetically using a table and substituting into
  the formulas.</span></p><p><span m="775000">Okay, the next thing we have to calculate
  is An.</span></p><p><span m="780000">Well, since An is the value of the right hand
  side,</span> <span m="783000">at the point zero one, you have to plug that in.</span></p><p><span
  m="787000">The right-hand side is x squared minus y squared.</span></p><p><span
  m="791000">So, it''s 0 squared minus 1 squared.</span></p><p><span m="794000">The
  value of the slope,</span> <span m="797000">there, is minus one, negative one.</span></p><p><span
  m="800000">Now, I have to multiply that by H.</span></p><p><span m="802000">h is
  0.1. So, it''s negative,</span> <span m="804000">I''ll never learn that. The way
  you learn to talk in</span> <span m="808000">kindergarten is the way you learn to
  talk the rest of your</span> <span m="812000">life, unfortunately. In kindergarten,</span>
  <span m="817000">we said minus. Negative 0.1.</span></p><p><span m="820000">n is
  one now. What''s the value of xn?</span></p><p><span m="825000">Well, to the old
  value I add 1/10.</span></p><p><span m="828000">What''s the value of y? Well, at
  this point,</span> <span m="833000">you have to do the calculation. It''s the old
  value of y.</span></p><p><span m="839000">To get this new value, it''s the old value
  plus this</span> <span m="845000">number. Well, that''s this plus that</span> <span
  m="851000">number is nine-tenths. An, now I have to calculate the</span> <span m="856000">new
  slope at this point. Okay, that is one-tenth squared</span> <span m="863000">minus
  nine-tenths squared. That''s 0.01 minus 0.81,</span> <span m="868000">which makes
  minus 0.80, I hope.</span></p><p><span m="878000">Check it on your calculators.
  Whip them out and press the</span> <span m="883000">buttons. I now multiply that
  by h,</span> <span m="886000">which means it''s going to be minus 0.08, perhaps
  with a zero</span> <span m="891000">after. I didn''t tell you how many</span> <span
  m="894000">decimal places. Let''s carry it out to two</span> <span m="898000">decimal
  places. I think that will be good</span> <span m="902000">enough. And finally,</span>
  <span m="905000">the last step, 2, here, add another one-tenth,</span> <span m="910000">so
  the value of x is now two-tenths.</span></p><p><span m="915000">And finally, what''s
  the value of y?</span></p><p><span m="918000">Well, I didn''t tell you where to
  stop.</span></p><p><span m="922000">Let''s stop at y of 0.2 because there''s no</span>
  <span m="928000">more room on the blackboard. About approximately how big is</span>
  <span m="934000">that? In other words,</span> <span m="936000">this is, then, this
  is going to be the old y</span> <span m="941000">plus this number, which seems to
  be 0.82 to me.</span></p><p><span m="948000">So, the answer is, the new value is
  0.82.</span></p><p><span m="951000">Okay, we got a number. We did what we are supposed
  to</span> <span m="955000">do. We got a number.</span></p><p><span m="956000">Next
  question? Now, let''s ask a few questions.</span></p><p><span m="960000">One of
  the first, most basic things is,</span> <span m="963000">you know, how right is
  this? How can I answer such a</span> <span m="967000">question if I have no explicit
  formula for that solution?</span></p><p><span m="971000">That''s the basic problem
  with numerical calculation.</span></p><p><span m="975000">In other words, I have
  to wander around in the</span> <span m="978000">dark to some extent, and yet have
  some idea when</span> <span m="981000">I''ve arrived at the place that I want to
  go.</span></p><p><span m="984000">Well, the first question I''d like to answer,</span>
  <span m="988000">is this too high or too low? Is Euler, sorry,</span> <span m="992000">he''ll
  forgive me in heaven, I will use him.</span></p><p><span m="996000">By this, I mean,
  is the result,</span> <span m="998000">let me just say something first, and that
  I''ll criticize</span> <span m="1003000">it. Is Euler too high or too low?</span></p><p><span
  m="1006000">In other words, is the result of using Euler''s</span> <span m="1010000">method,
  i.e. is this number too high or too</span> <span m="1013000">low? Is it higher than
  the right</span> <span m="1016000">answer, what it should be? Or, is it lower than
  the right</span> <span m="1022000">answer? Or, God forbid,</span> <span m="1025000">is
  it exactly right? Well, it''s almost never exactly</span> <span m="1029000">right.
  That''s not an option.</span></p><p><span m="1032000">Now, how will we answer that
  question?</span></p><p><span m="1036000">Well, let''s answer it geometrically.</span></p><p><span
  m="1039000">Basically, if the solution were a straight line,</span> <span m="1044000">then
  the Euler method would be exactly right all the time.</span></p><p><span m="1049000">But,
  it''s not a line. Then it''s a curve.</span></p><p><span m="1054000">Well, the critical
  question is, is it curved?</span></p><p><span m="1058000">Is the solution? So, here''s
  a solution.</span></p><p><span m="1061000">Let''s call it y1 of x, and let''s say
  here</span> <span m="1065000">was the starting point. Here, the solution is convex.</span></p><p><span
  m="1069000">And, here the solution is concave, right?</span></p><p><span m="1072000">Concave
  up or concave down, if you learn those words,</span> <span m="1077000">but I think
  those have, by now, I hope pretty well</span> <span m="1081000">disappeared from
  the curriculum. Call it, if you haven''t up</span> <span m="1086000">until now,
  what mathematicians call it, convex is that,</span> <span m="1090000">and the other
  one is concave. Well, how do Euler''s solutions</span> <span m="1093000">look? Well,
  I''ll just sketch.</span></p><p><span m="1095000">I think from this you can see
  already, when you start out on</span> <span m="1099000">the Euler''s solution, it''s
  going to go like that.</span></p><p><span m="1102000">Now you are too low. Well,
  let''s suppose after that,</span> <span m="1105000">the line element here is approximately
  the same as what</span> <span m="1108000">it is there, or roughly parallel.</span></p><p><span
  m="1112000">After all, they are not too far apart.</span></p><p><span m="1114000">And,
  the direction field is continuous.</span></p><p><span m="1117000">That is, the directions
  don''t change drastically from one</span> <span m="1120000">point to another. But
  now, you see it''s still too</span> <span m="1123000">low. It''s even lower as it</span>
  <span m="1125000">pathetically tries to follow. It''s losing territory,</span> <span
  m="1129000">and that''s basically because the curve is convex.</span></p><p><span
  m="1132000">Exactly the opposite what would happen if the curve were</span> <span
  m="1135000">concave, if the solution curve were concave.</span></p><p><span m="1140000">Now
  it''s too high, and it''s not going to be able</span> <span m="1144000">to correct
  that as long as the solution curve stays concave.</span></p><p><span m="1149000">Well,
  that''s probably too optimistic.</span></p><p><span m="1153000">It''s probably more
  like this. So, in other words,</span> <span m="1157000">in this case, if the curve
  is convex,</span> <span m="1161000">Euler is going to be too high, sorry, too low.</span></p><p><span
  m="1165000">Let''s put E for Euler. How about that?</span></p><p><span m="1170000">Euler
  is too low. If it''s concave,</span> <span m="1172000">then Euler is too high. Okay,
  that''s great.</span></p><p><span m="1176000">There''s just one little problem left,
  namely,</span> <span m="1180000">if we don''t have a formula for the solution,</span>
  <span m="1184000">and we don''t have a computer that''s busy drawing the picture</span>
  <span m="1189000">for us, in which case we wouldn''t need any of this</span> <span
  m="1194000">anyway, how are we supposed to tell if it''s convex or concave?</span></p><p><span
  m="1201000">Back to calculus. Calculus to the rescue!</span></p><p><span m="1204000">When
  is a curve convex? A curve is convex if its second</span> <span m="1208000">derivative
  is positive because the first to be convex means the</span> <span m="1212000">first
  derivative is increasing all the time.</span></p><p><span m="1216000">And therefore,
  the second derivative,</span> <span m="1218000">which is the derivative of the first
  derivative,</span> <span m="1222000">should be positive. Just the opposite here;</span>
  <span m="1225000">the curve, the slope is, the first derivative,</span> <span m="1229000">is
  decreasing all the time and therefore the second derivative</span> <span m="1233000">is
  negative. So, all we have to do is decide</span> <span m="1238000">what the second
  derivative of the solution is.</span></p><p><span m="1241000">We should probably
  call it a solution.</span></p><p><span m="1243000">y of x is a little too vague.</span></p><p><span
  m="1246000">y1 means the solution started at this point.</span></p><p><span m="1249000">So,
  in fact, probably it would have been</span> <span m="1252000">better from the beginning
  to call that y1,</span> <span m="1254000">except there''s no room, y1, let''s say.</span></p><p><span
  m="1257000">That means the solution which started out at the point,</span> <span
  m="1261000">(0, 1). So, I''m still talking about at</span> <span m="1264000">a solution
  like that. All right, so I want to know if</span> <span m="1268000">this is positive,
  the second derivative is</span> <span m="1270000">positive at the starting point,
  zero, or it''s negative.</span></p><p><span m="1274000">Now, again, how you can
  regulate the second derivative,</span> <span m="1277000">if you don''t know what
  the solution is explicitly,</span> <span m="1280000">then the answer is you can
  do it from the differential</span> <span m="1284000">equation itself. How do I do
  that?</span></p><p><span m="1286000">Well: easy. y prime equals x squared minus</span>
  <span m="1289000">y squared. Okay, that tells me how to</span> <span m="1294000">calculate
  y prime if I know the value of x and y,</span> <span m="1299000">in other words,
  the 0.01.</span></p><p><span m="1301000">What would be the value of y double prime?</span></p><p><span
  m="1305000">Well, differentiate the equation.</span></p><p><span m="1308000">It''s
  two x minus two y y prime.</span></p><p><span m="1312000">Don''t forget to use the
  chain rule.</span></p><p><span m="1315000">So, if I want to calculate at (0, 1),
  in other words,</span> <span m="1320000">if my starting point is that curve convex
  or concave,</span> <span m="1324000">well, let''s calculate. y of zero equals one.</span></p><p><span
  m="1330000">Okay, what''s y prime of zero?</span></p><p><span m="1332000">Well,
  I don''t have to repeat</span> <span m="1335000">that calculation. Using this, I''ve
  already</span> <span m="1338000">calculated that it was negative one.</span></p><p><span
  m="1340000">And now, the new thing, what''s y double prime of zero?</span></p><p><span
  m="1344000">Well, it is this.</span></p><p><span m="1346000">I''ll write it out.
  It''s two times zero minus two</span> <span m="1349000">times negative y, which
  is one,</span> <span m="1351000">two times one times y prime, which is negative
  one.</span></p><p><span m="1356000">You want to see we are pulling</span> <span
  m="1361000">ourselves up by our own boot straps, which is impossible.</span></p><p><span
  m="1365000">But, it is not impossible because we are doing it.</span></p><p><span
  m="1369000">So, what''s the answer? Zero here, two,</span> <span m="1372000">I''ve
  calculated without having the foggiest idea of what the</span> <span m="1377000">solution
  is or how it looks. I''ve calculated that its second</span> <span m="1383000">derivative
  at the starting point is two.</span></p><p><span m="1387000">Therefore, my solution
  is convex at the starting point.</span></p><p><span m="1393000">And therefore, this
  Euler approximation,</span> <span m="1397000">if I don''t carry it out too far,
  will be too low.</span></p><p><span m="1402000">So, it''s convex Euler, too low.</span></p><p><span
  m="1405000">Now, you could argue, yeah, well, what about this?</span></p><p><span
  m="1412000">[LAUGHTER] So, you could go like this,</span> <span m="1416000">and
  then you can see it catches up.</span></p><p><span m="1419000">Well, of course,
  if the curve changes from</span> <span m="1424000">convex to concave, then it''s
  really impossible to</span> <span m="1429000">make any prediction at all. That''s
  a difficulty.</span></p><p><span m="1434000">So, all this analysis is only if you
  stay very nearby.</span></p><p><span m="1442000">However, I wanted to show you,
  the main purpose of it in my</span> <span m="1446000">mind was to show you how do
  you use, it''s these equations,</span> <span m="1451000">how to use the differential
  equation itself to get</span> <span m="1454000">information about the solutions,
  without actually being able to</span> <span m="1459000">calculate the solutions?
  Now, so that''s the method,</span> <span m="1463000">and that''s how to find out
  something about it.</span></p><p><span m="1467000">And now, what I''d like to talk
  about is errors.</span></p><p><span m="1472000">How do I handle, right?</span></p><p><span
  m="1474000">So, in a sense, I''ve started the error</span> <span m="1478000">analysis.
  In other words,</span> <span m="1480000">the error, by definition, the error is
  this difference, e.</span></p><p><span m="1486000">So, in other words,</span> <span
  m="1488000">what I''m asking here, is the error positive?</span></p><p><span m="1492000">It
  depends which we measure it. Usually, you take this minus</span> <span m="1499000">that.
  So, here, the error would be</span> <span m="1503000">considered positive, and here
  it would be considered</span> <span m="1507000">negative, although I''m sure there''s
  a book somewhere in the</span> <span m="1513000">world, which does the opposite.
  Most hedge by just using the</span> <span m="1518000">absolute value of the error
  plus a statement that the method is</span> <span m="1523000">producing answers which
  are too low or too high.</span></p><p><span m="1527000">The question, then, is,
  naturally,</span> <span m="1530000">this is not the world''s best method.</span></p><p><span
  m="1535000">It''s not as bad as it seems. It''s not the world''s best</span> <span
  m="1538000">method because that convexity and concavity means that you are</span>
  <span m="1542000">automatically introducing a systematic error.</span></p><p><span
  m="1545000">If you can predict which way the error is going to be by just</span>
  <span m="1549000">knowing whether the curve is convex or concave,</span> <span m="1551000">it''s
  not what you want. I mean, you want to at least</span> <span m="1555000">have a
  chance of getting the right answer,</span> <span m="1557000">whereas this is telling
  you you''re definitely going to get</span> <span m="1561000">the wrong answer. All
  it tells you is,</span> <span m="1563000">and it''s telling you whether your answer
  is going to be too</span> <span m="1567000">high or too low. We''ve like a better
  chance of</span> <span m="1572000">getting the right answer. Now, so the question
  is,</span> <span m="1577000">how do you get a better method? A search is for a better</span>
  <span m="1583000">method. Now, the first method,</span> <span m="1586000">which
  will occur, I''m sure, to anyone who looks</span> <span m="1590000">at that picture,
  is, look, if you want this</span> <span m="1595000">yellow line to follow the white
  one, the white solution,</span> <span m="1600000">more accurately, for heaven''s
  sake,</span> <span m="1603000">don''t take such big steps. Take small steps,</span>
  <span m="1610000">and then it will follow better. All right, let''s draw a</span>
  <span m="1619000">picture. Excuse me.</span></p><p><span m="1622000">My little box
  of treasures, here.</span></p><p><span m="1628000">[LAUGHTER] So, use a smaller
  step size.</span></p><p><span m="1633000">And the picture, roughly, which is going
  to</span> <span m="1637000">justify that, will look like this.</span></p><p><span
  m="1641000">If the solution curve looks like this, then with a big step</span> <span
  m="1646000">size, I''m liable to have something that looks like that.</span></p><p><span
  m="1653000">But, if I take a smaller step size, suppose I halve the step</span>
  <span m="1658000">size. How''s it going to look,</span> <span m="1660000">then?
  Well, I better switch to a</span> <span m="1663000">different color. If I halve
  the step size,</span> <span m="1667000">I''ll get a littler, goes like that.</span></p><p><span
  m="1670000">And now it''s following closer. Of course, I''m stacking the</span>
  <span m="1675000">deck, but see how close it follows?</span></p><p><span m="1680000">I''m
  definitely not to be trusted on this.</span></p><p><span m="1682000">Okay, let''s
  do the opposite, make really big steps.</span></p><p><span m="1685000">Suppose instead
  of the yellow ones I used the green one of</span> <span m="1688000">double step
  size. Well, what would have happened</span> <span m="1691000">then? Well, I''ve
  started out,</span> <span m="1693000">but now I''ve gone all the way to there.</span></p><p><span
  m="1695000">And now, on my way up, of course, it has a little</span> <span m="1698000">further
  to go. But, if for some reason,</span> <span m="1701000">I stop there, you could
  see,</span> <span m="1702000">I would be still lower. In other words,</span> <span
  m="1704000">the bigger the steps size, the more the error.</span></p><p><span m="1709000">And,
  where are the errors that we are talking about?</span></p><p><span m="1713000">Well,
  the way to think of the errors, this is the error,</span> <span m="1718000">that
  number the error. You can make it positive,</span> <span m="1722000">negative, or
  just put it automatically an absolute value</span> <span m="1727000">sign around
  it. That''s not so important.</span></p><p><span m="1731000">So, in other words,
  the conclusion is,</span> <span m="1734000">that the error e, the difference between
  the true</span> <span m="1739000">value that I should have gotten, and the Euler
  value that the</span> <span m="1744000">calculation produced, that the error e,</span>
  <span m="1748000">depends on the step size. Now, how does it depend on the</span>
  <span m="1754000">step size? Well, it''s impossible to give</span> <span m="1757000">an
  exact formula, but there''s an approximate</span> <span m="1760000">answer, which
  is, by and large,</span> <span m="1762000">true. So, the answer is,</span> <span
  m="1764000">e is going to be a function of h.</span></p><p><span m="1767000">What
  function? Well, asymptotically,</span> <span m="1770000">which is another way of
  putting quotation marks around,</span> <span m="1774000">what did I say? It''s going
  to be a constant,</span> <span m="1777000">some constant, times H.</span></p><p><span
  m="1780000">[LAUGHTER] It looks like this,</span> <span m="1812000">and for this
  reason it''s called a first order,</span> <span m="1817000">the Euler is a first-order
  method.</span></p><p><span m="1821000">And now, first-order does not refer to the
  first order of the</span> <span m="1828000">differential equation. It''s not the
  first order</span> <span m="1834000">because it''s y prime equals f of (x, y).</span></p><p><span
  m="1838000">The first order means the fact</span> <span m="1841000">that h occurs
  to the first power.</span></p><p><span m="1844000">The way people usually say this
  is since the normal way of</span> <span m="1849000">decreasing the step size, as
  you''ll see as is you try to</span> <span m="1853000">use a computer visual that
  deals with the Euler method,</span> <span m="1858000">which I highly recommend,
  by the way, so highly</span> <span m="1862000">recommended that you have to do it,
  is that the way to say it,</span> <span m="1867000">each new step halves the step
  size.</span></p><p><span m="1872000">That''s the usual way to do it. If you halve
  the step size,</span> <span m="1880000">since this is a constant, if I halve the
  step size,</span> <span m="1887000">I halve the error, approximately.</span></p><p><span
  m="1893000">Halve the step size, halve the error.</span></p><p><span m="1896000">That
  tells you how the error varies with step size for</span> <span m="1902000">Euler''s
  method. Please understand,</span> <span m="1906000">that''s what people say, and
  please understand the</span> <span m="1911000">grammatical construction. Since everyone
  in the math</span> <span m="1916000">department has a cold these days except me
  for the moment,</span> <span m="1923000">everyone goes around chanting this mantra.</span></p><p><span
  m="1929000">This is totally irrelevant. This whole mantra,</span> <span m="1933000">feed
  a cold, starve a fever.</span></p><p><span m="1935000">And if you asked them what
  it means, they say eat a lot if you</span> <span m="1941000">have a cold. And if
  you have a fever,</span> <span m="1944000">don''t eat very much, which is not what
  it means at</span> <span m="1948000">all. Grammatically,</span> <span m="1950000">it''s
  exactly the same construction as this.</span></p><p><span m="1953000">What this
  means is if you halve the step size,</span> <span m="1957000">you will halve the
  error. That''s what feed a cold,</span> <span m="1960000">starve a fever means.
  And, remember this for the rest</span> <span m="1964000">of your life. If you feed
  a cold,</span> <span m="1966000">if you eat too much when you have a cold, you will
  get a</span> <span m="1970000">fever and end up still having to starve yourself
  because,</span> <span m="1974000">of course, nobody, when you have a fever,</span>
  <span m="1977000">nobody feels like eating, so they don''t eat anything.</span></p><p><span
  m="1982000">All right, you got that? Good.</span></p><p><span m="1986000">I want
  all of you to go home and tell that to your mothers.</span></p><p><span m="1994000">You
  know, that''s the way we always used to speak.</span></p><p><span m="2001000">Grimmer
  ones: spare the rod,</span> <span m="2005000">spoil the child does not mean that
  you should not hit your</span> <span m="2013000">kid. It means that if you fail
  to</span> <span m="2019000">hit your kid, he or she will be spoiled,</span> <span
  m="2024000">whatever that means. So, you don''t want to do that.</span></p><p><span
  m="2030000">I guess the mantra today would be, I don''t know.</span></p><p><span
  m="2036000">Okay, so the first line of defense is simply to keep having</span> <span
  m="2043000">the step size in Euler. And, what people do is,</span> <span m="2048000">if
  they don''t want to use anything better than Euler''s</span> <span m="2051000">method,
  is you keep having the step size until the curve</span> <span m="2055000">doesn''t
  seem to change anymore. And then you say,</span> <span m="2058000">well, that must
  be the solution.</span></p><p><span m="2060000">And, I asked you on the problems
  set,</span> <span m="2062000">how much would you continue to have to halve the step
  size in</span> <span m="2066000">order for that good thing to happen?</span></p><p><span
  m="2070000">However, there are more efficient methods which get the</span> <span
  m="2075000">results faster. So if that''s our good method,</span> <span m="2079000">let''s
  call this our still better method.</span></p><p><span m="2083000">The better methods
  aim at being better.</span></p><p><span m="2087000">They keep the same idea as Euler''s
  method,</span> <span m="2091000">but they say, look, let''s try to improve that</span>
  <span m="2095000">slope, An. In other words,</span> <span m="2099000">since the
  slope, An, that we start with is</span> <span m="2101000">guaranteed to be wrong
  if the curve is convex or concave,</span> <span m="2105000">can we somehow correct
  it? So, for example,</span> <span m="2108000">instead of immediately aiming there,
  can''t we somehow aim it</span> <span m="2112000">so that by luck, we just, at the
  next step just</span> <span m="2115000">lands us back on the curve again?</span></p><p><span
  m="2117000">In other words, with sort of looking for the</span> <span m="2120000">short
  path, a shortcut path, which by good luck will end us</span> <span m="2124000">up
  back on the curve again. And, all the simple</span> <span m="2127000">improvements
  on the Euler method, and they are the most</span> <span m="2131000">stable in ways
  to solve differential equations</span> <span m="2134000">numerically, aim at finding
  a better slope.</span></p><p><span m="2139000">So, they find a better value for
  a better slope,</span> <span m="2143000">find a better value than An. Try to improve
  that slope that</span> <span m="2148000">you found. Now, once you have the idea</span>
  <span m="2152000">that you should look for a better slope,</span> <span m="2155000">it''s
  not very difficult to see what, in fact,</span> <span m="2159000">you should try.
  Again, I think most of you</span> <span m="2163000">would say, hey, I would have
  thought of that.</span></p><p><span m="2167000">And, you would be closer in time,
  since these methods were</span> <span m="2171000">only found about around the turn
  of the last century is when I</span> <span m="2175000">place them, mostly by some
  German mathematicians interested</span> <span m="2180000">in solving equations numerically.</span></p><p><span
  m="2182000">All right, so what is the better method?</span></p><p><span m="2185000">Our
  better slope, what should we look for in our</span> <span m="2188000">better slope?
  Well, the simplest procedure</span> <span m="2193000">is, once again, we are starting
  from there,</span> <span m="2196000">and the Euler slope would be the same as a
  line element.</span></p><p><span m="2201000">So, the line element looks like this.</span></p><p><span
  m="2204000">And, our yellow slope, A, and I''ll still continue to</span> <span m="2208000">call
  it An, goes like that, gets to here.</span></p><p><span m="2211000">Okay, now if
  it were convex, if the curve were convex,</span> <span m="2215000">this would be
  too low. And therefore,</span> <span m="2218000">the next step would be, I''m going
  to draw this next</span> <span m="2222000">step in pink. Well, let''s continue in
  here,</span> <span m="2227000">would be going up like that. I''ll call this Bn,</span>
  <span m="2230000">just because it''s the next step of Euler''s method.</span></p><p><span
  m="2234000">It could be called An prime or something like that.</span></p><p><span
  m="2239000">But this will do. And now what you do is,</span> <span m="2242000">let
  me put an arrow on it to indicate parallelness,</span> <span m="2246000">go back
  to the beginning, draw this parallel to Bn.</span></p><p><span m="2251000">So, here
  is Bn. Again, just a line of that same</span> <span m="2255000">slope. And now,
  what you should use as</span> <span m="2258000">the simplest improvement on Euler''s
  method,</span> <span m="2262000">is take the average of these two because that''s
  more likely</span> <span m="2268000">to hit the curve than An will, which is sure
  to be too low if</span> <span m="2274000">the curve is convex. In other words,</span>
  <span m="2277000">use this instead. Use that.</span></p><p><span m="2279000">So,
  this is our better slope. Okay, what will we call that</span> <span m="2286000">slope?
  We don''t have to call it</span> <span m="2288000">anything. What were the equations
  for the</span> <span m="2291000">method be? Well, x n plus one</span> <span m="2294000">is
  gotten by adding the step size.</span></p><p><span m="2297000">So, here''s my step
  size just as it was before.</span></p><p><span m="2300000">Just as it was before,
  the new thing is how to get the</span> <span m="2305000">new value of y. So, y n
  plus one</span> <span m="2308000">should be the old yn, plus h times not this crummy</span>
  <span m="2312000">slope, An, but the better, the pink slope.</span></p><p><span
  m="2317000">What''s the formula for the pink slope?</span></p><p><span m="2319000">Well,
  let''s do it in two steps. It''s the average of An and Bn.</span></p><p><span m="2324000">Hey,
  but you didn''t tell me, or I didn''t tell you what Bn</span> <span m="2328000">was.
  So, you now must tell the</span> <span m="2330000">computer, oh yes, by the way,
  you remember that</span> <span m="2334000">An was what it always was. The interesting
  thing is,</span> <span m="2338000">what is Bn? Well, to get Bn,</span> <span m="2341000">Bn
  is the slope of the line element at this new point.</span></p><p><span m="2345000">Now,
  what am I going to call that new point?</span></p><p><span m="2348000">I don''t
  want to call this y value, y n plus one,</span> <span m="2352000">because that''s,
  it''s this up here that''s going</span> <span m="2356000">to be the y n plus one.
  All this is,</span> <span m="2358000">is a temporary value used to make another
  calculation,</span> <span m="2362000">which will then be combined with the previous
  calculations</span> <span m="2367000">to get the right value. Therefore, give it
  a temporary</span> <span m="2371000">name. That point, we''ll call it,</span> <span
  m="2374000">it''s not going to be the final, the real y n plus one.</span></p><p><span
  m="2378000">We''ll call it y n plus one</span> <span m="2380000">twiddle, y n plus
  one temporary. And, what''s the formula for it?</span></p><p><span m="2384000">Well,
  it''s just going to be what the original Euler formula;</span> <span m="2388000">it''s
  going to be y n plus what you would have gotten if you had</span> <span m="2392000">calculated,
  in other words, it''s the point that the Euler</span> <span m="2396000">method produced,
  but it''s not,</span> <span m="2397000">finally, the point that we want.</span></p><p><span
  m="2401000">Now, do I have to say anything else?</span></p><p><span m="2404000">Yeah,
  I didn''t tell the computer what Bn was.</span></p><p><span m="2408000">Okay, Bn
  is the slope of the direction field at the point n</span> <span m="2414000">plus
  one. And the computer knows what</span> <span m="2419000">that is. And, this point,</span>
  <span m="2421000">y n plus one temporary.</span></p><p><span m="2424000">So, you
  make a temporary choice of this, calculate that number,</span> <span m="2431000">and
  then go back, and as it were,</span> <span m="2434000">correct that value to this
  value by using this better</span> <span m="2439000">slope. Now, that''s all there
  is to the</span> <span m="2444000">method, except I didn''t give you its name.</span></p><p><span
  m="2448000">Well, it has three names, four names in fact.</span></p><p><span m="2452000">Which
  one shall I give you? I don''t care.</span></p><p><span m="2456000">Okay, the shortest
  name is Heun''s method.</span></p><p><span m="2460000">But nobody pronounces that
  correctly.</span></p><p><span m="2465000">So, it''s Heun''s method. It''s called,</span>
  <span m="2469000">also, the Improved Euler method.</span></p><p><span m="2473000">It''s
  called Modified Euler, very expressive word,</span> <span m="2479000">Modified Euler''s
  method. And, it''s also called RK2.</span></p><p><span m="2485000">I''m sure you''ll
  like that name best.</span></p><p><span m="2491000">It has a Star Wars sort of sound.</span></p><p><span
  m="2493000">RK stands for Runge-Kutta, and the reason for the two is</span> <span
  m="2498000">not that it uses, well, it is that it uses two</span> <span m="2502000">slopes,
  but the real reason for the two is that it is a</span> <span m="2506000">second-order
  method. So, that''s the most important</span> <span m="2510000">thing to put down
  about it. It''s a second-order method,</span> <span m="2515000">whereas Euler''s
  was only a first-order method.</span></p><p><span m="2520000">So, Heun''s method,
  or RK2, let''s write it,</span> <span m="2523000">is the shortest thing to write,
  is a second-order method,</span> <span m="2528000">meaning that the error varies
  with the step size like some</span> <span m="2533000">constant, it will not be the
  same as the constant for Euler''s</span> <span m="2539000">method, times h squared.</span></p><p><span
  m="2542000">That''s a big saving because it now means that if you halve the</span>
  <span m="2548000">step size, you''re going to decrease the error by a factor</span>
  <span m="2553000">of one quarter. You will quarter the error.</span></p><p><span
  m="2558000">Now, you say, hey, why should anyone use</span> <span m="2560000">anything
  else? Well, think a little second.</span></p><p><span m="2564000">The real thing
  which determines how slowly one of these methods</span> <span m="2568000">run is
  you look at the hardest step of the method and ask how</span> <span m="2573000">long
  does the computer take, how many of those hardest steps</span> <span m="2577000">are
  there? Now, the answer is,</span> <span m="2579000">the hardest step is always the
  evaluation of the function</span> <span m="2584000">because the functions that are
  common use are not x squared</span> <span m="2588000">minus y squared. They take
  half a page and have,</span> <span m="2594000">as coefficients, you know, ten decimal
  place</span> <span m="2597000">numbers, whatever the engineers doing it, whatever
  their</span> <span m="2602000">accuracy was. So, the thing that controls how</span>
  <span m="2605000">long a method runs is how many times the slope,</span> <span m="2609000">the
  function, must be evaluated.</span></p><p><span m="2613000">For Euler, I only have
  to evaluate it once.</span></p><p><span m="2617000">Here, I have to evaluate it
  twice.</span></p><p><span m="2620000">Now, roughly speaking, the number of function</span>
  <span m="2624000">evaluations will each give you the exponent.</span></p><p><span
  m="2628000">The method that''s called Runge-Kutta fourth order will</span> <span
  m="2633000">require four evaluations of slope, but the accuracy will be</span> <span
  m="2639000">like h to the fourth: very accurate.</span></p><p><span m="2645000">You
  halve the step size, and it goes down by a factor of</span></p><p><span m="2650000">16.
  Great. But you had to evaluate the slope four times.</span></p><p><span m="2654000">Suppose,
  instead, you halve four times this thing.</span></p><p><span m="2659000">And, what
  would you have done? You would have decreased it to</span> <span m="2664000">1/16th
  to what it was. You still would increase the</span> <span m="2669000">number of
  function evaluations you needed by four,</span> <span m="2674000">and you would
  have decreased the error by a 16th.</span></p><p><span m="2680000">So, in some sense,
  it really doesn''t matter</span> <span m="2683000">whether you use a very fancy
  method, which requires more</span> <span m="2687000">function evaluations. That''s
  true.</span></p><p><span m="2690000">The error goes down faster, but you are having
  to more work</span> <span m="2694000">to get it. So, anyway, nothing is free.</span></p><p><span
  m="2697000">Now, there is an RK4. I think I''ll skip that,</span> <span m="2701000">since
  I wouldn''t dare to ask you any questions about it.</span></p><p><span m="2706000">But,
  let me just mention it, at least, because it''s the</span> <span m="2710000">standard.
  It uses four evaluations.</span></p><p><span m="2713000">It''s the standard method,
  if you don''t want to do</span> <span m="2717000">anything fancier. It''s rather
  inefficient,</span> <span m="2720000">but it''s very accurate, standard method,</span>
  <span m="2723000">accurate, and you''ll see when you use the programs,</span> <span
  m="2727000">it''s, in fact, a program which is drawing</span> <span m="2730000">those
  curves, the numerical method which</span> <span m="2733000">draws all those curves
  that you believe in on the computer</span> <span m="2738000">screen is the RK4 method.
  The Runge-Kutta,</span> <span m="2743000">I should give them their names. Runge-Kutta,</span>
  <span m="2747000">fourth-order method. Two mathematicians,</span> <span m="2751000">I
  believe both German mathematicians around the turn</span> <span m="2755000">of the
  last century, Runge-Kutta fourth-order method</span> <span m="2760000">requires
  four slopes, requires you to calculate four</span> <span m="2765000">slopes. I won''t
  bother telling you what</span> <span m="2769000">you do, but it''s a procedure like
  that.</span></p><p><span m="2771000">It''s just a little bit more elaborate.</span></p><p><span
  m="2774000">And you take two of these, you make up a weighted average</span> <span
  m="2777000">for the super slope. You use weighted average.</span></p><p><span m="2780000">What
  should I divide that by to get the right...?</span></p><p><span m="2783000">Six.</span></p><p><span
  m="2784000">Why six? Well, because if all these</span> <span m="2786000">numbers
  were the same, I''d want it to come out to be</span> <span m="2789000">whatever
  that common value was. Therefore, in a weighted</span> <span m="2795000">average,
  you must always divide by the sum of the coefficients.</span></p><p><span m="2800000">So,
  this is the super-slope. And, if you plug that</span> <span m="2804000">super-slope
  into here, you will be using the</span> <span m="2807000">Runge-Kutta method, and
  get the best possible</span> <span m="2811000">results. Now, I wanted to spend the
  last</span> <span m="2814000">three minutes talking about pitfalls of numerical</span>
  <span m="2818000">computation in general. One pitfall I am leaving you on</span>
  <span m="2824000">the homework to discover for yourself.</span></p><p><span m="2828000">Don''t
  worry, it won''t cause you any grief.</span></p><p><span m="2832000">It''ll just
  destroy your faith in these things for the rest of</span> <span m="2838000">your
  life, which is probably a good thing.</span></p><p><span m="2842000">So, pitfalls,
  number one, you find,</span> <span m="2845000">you''ll find. Let me talk,</span>
  <span m="2847000">instead, briefly about number two, which I am not giving you</span>
  <span m="2853000">an exercise in. Number two is illustrated by</span> <span m="2857000">the
  following equation. What could be simpler?</span></p><p><span m="2860000">This is
  a very bad equation to try to solve numerically.</span></p><p><span m="2864000">Now,
  why? Well, because if I separate</span> <span m="2867000">variables, why don''t
  I save a little time?</span></p><p><span m="2869000">I''ll just tell you what the
  solution is, okay?</span></p><p><span m="2873000">You obviously separate variables.</span></p><p><span
  m="2875000">Maybe you can do it in your head.</span></p><p><span m="2877000">The
  solution will be, the solutions will have an</span> <span m="2880000">arbitrary
  constant in them, and they won''t be very</span> <span m="2883000">complicated.
  They will be one over c minus x.</span></p><p><span m="2888000">C is an arbitrary
  constant,</span> <span m="2890000">and as you give different values, you get,</span>
  <span m="2893000">now, what do those guys look like?</span></p><p><span m="2895000">Okay,
  so here I am. I start out at the point,</span> <span m="2898000">one. And, I start
  out,</span> <span m="2899000">I tell the computer, compute for me the value of the</span>
  <span m="2903000">solution at one starting out at one.</span></p><p><span m="2905000">And,
  it computes and computes a little while.</span></p><p><span m="2908000">But the
  solution, how does this curve actually</span> <span m="2911000">look? So, in other
  words,</span> <span m="2914000">suppose I say that y of zero equals one.</span></p><p><span
  m="2918000">Find me y of two. In other words,</span> <span m="2921000">take a nice
  small step size. Use the Runge-Kutta</span> <span m="2924000">fourth-order method.
  Calculate a little bit,</span> <span m="2928000">and tell me, I just want to know
  what y of</span> <span m="2931000">two is. Well, what is y of two?</span></p><p><span
  m="2933000">Well, unfortunately, how does that curve look?</span></p><p><span m="2936000">The
  curve looks like this. At that point,</span> <span m="2941000">it drops to infinity
  in a manner of speaking,</span> <span m="2944000">and then sort of comes back up
  again like that.</span></p><p><span m="2947000">What is the value of y? This is
  the point,</span> <span m="2951000">one. What is the value of y of two?</span></p><p><span
  m="2953000">Is it here?</span></p><p><span m="2955000">Is it this? Well, I don''t
  know,</span> <span m="2957000">but I do know that the computer will not find it.</span></p><p><span
  m="2960000">The computer will follow this along, and get lost in eternity,</span>
  <span m="2965000">in infinity, and see no reason whatever why</span> <span m="2968000">it
  should start again on this branch of the curve.</span></p><p><span m="2974000">Okay,
  well, can''t we predict that that''s going to happen</span> <span m="2978000">somehow,
  avoid what I should have.</span></p><p><span m="2980000">The whole difficulty is,
  this is called a singular</span> <span m="2984000">point. The solution has a singularity,</span>
  <span m="2987000">in other words, a single place where it goes to</span> <span m="2991000">infinity
  or becomes discontinuous,</span> <span m="2993000">maybe as a jump discontinuity.
  It has a singularity at x</span> <span m="2997000">equals c. This, in particular,</span>
  <span m="3000000">at x equals one here, but from the differential</span> <span m="3004000">equation,
  where is that c? There is no way of predicting</span> <span m="3010000">it. Each
  solution,</span> <span m="3011000">in other words, to this differential equation,</span>
  <span m="3015000">has its own, private singularity,</span> <span m="3017000">which
  only it knows about, and where it''s going to blow</span> <span m="3021000">up,
  and there''s no way of telling from the differential</span> <span m="3025000">equation
  where that''s going to be.</span></p><p><span m="3028000">That''s one of the things
  that makes numerical calculation</span> <span m="3032000">difficult, when you cannot
  predict where things are going</span> <span m="3037000">to go bad in advance.</span></p>'
type: course
uid: f55763ae30b0c64c95f5e06e58ed1fdc

---
None