---
about_this_resource_text: ''
course_id: 18-03sc-differential-equations-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: uNOyxQwIV8o
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Video-YouTube-Stream
  type: Video
  uid: 4da9535b34e271a1ddf4ea31a96fc07b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/uNOyxQwIV8o/default.jpg
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b43e2996c6e3722a07545a38165d7ab2
- id: 3Play-3PlayYouTubeid-MP4
  media_location: uNOyxQwIV8o
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 99dfebf188ccd291385ebcd8cf4c14b4
- id: uNOyxQwIV8o.srt
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-iv-first-order-systems/matrix-exponentials/decoupling/uNOyxQwIV8o.srt
  title: 3play caption file
  type: null
  uid: a111cd3b456c374dc9d277dfb5664d9c
- id: uNOyxQwIV8o.pdf
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-iv-first-order-systems/matrix-exponentials/decoupling/uNOyxQwIV8o.pdf
  title: 3play pdf file
  type: null
  uid: 7057a19232ecae7cecb4cc474001c427
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 15874277e66721ce9abbc5073d9f3a90
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 2798c4b711cdba9c89ad2acb71accd79
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id493274885
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Video-iTunes U-MP4
  type: Video
  uid: 22663e7a6f37ccfeb1d78eb6325ba027
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.03S06/mit-ocw-18.03-lec30-28apr2003-220k_512kb.mp4
  parent_uid: 3c731b47f01dcf0ecbf44050afa6fc18
  title: Video-Internet Archive-MP4
  type: Video
  uid: 983443d185951d0f3fe84273f11efa92
inline_embed_id: 69110177decoupling21074238
layout: video
order_index: null
parent_uid: 740fe4ca9f7f5dafcec750013536f3c9
related_resources_text: ''
short_url: decoupling
technical_location: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/unit-iv-first-order-systems/matrix-exponentials/decoupling
template_type: popup
title: Decoupling
transcript: "<p><span m='8000'>Everything I say today is going to be for n-by-n systems,</span>\
  \ <span m='12000'>but for your calculations and the exams two-by-two will be</span>\
  \ <span m='17000'>good enough. Our system looks like that.</span> <span m='20000'>Notice\
  \ I am talking today about the homogeneous system,</span> <span m='25000'>not the\
  \ inhomogenous system. So, homogenous.</span> <span m='36000'>And we have so far\
  \ two basic methods of solving it.</span> <span m='40000'>The first one, on which\
  \ we spent the most</span> <span m='43000'>time, is the method of where you calculate\
  \ the eigenvalues of the</span> <span m='48000'>matrix, the eigenvectors, and put\
  \ them together to make</span> <span m='53000'>the general solution. So eigenvalues,</span>\
  \ <span m='56000'>e-vectors and so on. The second method,</span> <span m='60000'>which\
  \ I gave you last time, I called \"royal road,\" simply</span> <span m='64000'>calculates\
  \ the matrix e to the At and says that the</span> <span m='68000'>solution is e\
  \ to the At times x zero,</span> <span m='71000'>the initial condition. That is\
  \ very elegant.</span> <span m='74000'>The only problem is that to calculate the\
  \ matrix e to the</span> <span m='78000'>At, although sometimes you can do it by\
  \ its definition as an</span> <span m='82000'>infinite series, most of the time\
  \ the only way</span> <span m='86000'>to calculate the matrix e to the At is by\
  \ using the fundamental</span> <span m='90000'>matrix. In other words,</span> <span\
  \ m='93000'>the normal way of doing it is you have to calculate it as the</span>\
  \ <span m='97000'>fundamental matrix time normalized at zero.</span> <span m='100000'>So,\
  \ as I explained at the end of last time and you practiced</span> <span m='104000'>in\
  \ the recitations, you have to find the</span> <span m='106000'>fundamental matrix,\
  \ which, of course,</span> <span m='109000'>you have to do by eigenvalues and eigenvectors.</span>\
  \ <span m='112000'>And then you multiply it by its value at zero,</span> <span m='115000'>inverse.\
  \ And that, by magic,</span> <span m='117000'>turns out to be the same as the exponential\
  \ matrix.</span> <span m='122000'>But, of course, there has been no gain in</span>\
  \ <span m='125000'>simplicity or no gain in ease of calculation.</span> <span m='128000'>The\
  \ only difference is that the language has been changed.</span> <span m='132000'>Now,\
  \ today is going to be devoted to yet another method</span> <span m='136000'>which\
  \ saves no work at all and only amounts to a change of</span> <span m='141000'>language.\
  \ The only reason I give it to</span> <span m='143000'>you is because I have been\
  \ begged by various engineering</span> <span m='148000'>departments to do so --\
  \ -- because that is the language</span> <span m='153000'>they use. In other words,</span>\
  \ <span m='155000'>each person who solves systems, some like to use fundamental</span>\
  \ <span m='159000'>matrices, some just calculate, some immediately convert the</span>\
  \ <span m='164000'>system by elimination into a single higher order equation</span>\
  \ <span m='168000'>because they are more comfortable with that.</span> <span m='172000'>Some,\
  \ especially if they are writing papers,</span> <span m='175000'>they talk exponential\
  \ matrices. But there are a certain number</span> <span m='181000'>of engineers\
  \ and scientists who talk decoupling,</span> <span m='185000'>express the problem\
  \ and the answer in terms of decoupling.</span> <span m='189000'>And that is, therefore,\
  \ what I have to</span> <span m='192000'>explain to you today. So, the third method,</span>\
  \ <span m='196000'>today's method, I stress is really no more than</span> <span\
  \ m='200000'>a change of language. And I feel a little guilty</span> <span m='203000'>about\
  \ the whole business. Instead of going more deeply</span> <span m='209000'>into\
  \ studying these equations, what I am doing is like giving</span> <span m='213000'>a\
  \ language course and teaching you how to say hello and</span> <span m='217000'>good-bye\
  \ in French, German, Spanish,</span> <span m='220000'>and Italian. It is not going\
  \ very deeply</span> <span m='223000'>into any of those languages, but you are going\
  \ into the</span> <span m='227000'>outside world, where people will speak these</span>\
  \ <span m='230000'>things. Here is an introduction to the</span> <span m='232000'>language\
  \ of decoupling in which for some people is the exclusive</span> <span m='237000'>language\
  \ in which they talk about systems.</span> <span m='242000'>Now, I think the best\
  \ way to, well, in a general way,</span> <span m='246000'>what you try to do is\
  \ as follows.</span> <span m='249000'>You try to introduce new variables.</span>\
  \ <span m='253000'>You make a change of variables. I am going to do it two-by-two</span>\
  \ <span m='258000'>just to save a lot of writing out.</span> <span m='262000'>And\
  \ it's going to be a linear change of variables because we</span> <span m='267000'>are\
  \ interested in linear systems.</span> <span m='272000'>The problem is to find u\
  \ and v such that something wonderful</span> <span m='277000'>happens, such that\
  \ when you make the change of variables to</span> <span m='283000'>express this\
  \ system in terms of u and v it becomes decoupled.</span> <span m='289000'>And that\
  \ means the system turns into a system which looks like u</span> <span m='296000'>prime\
  \ equals k1 times u and v prime equals k2</span> <span m='301000'>times v. Such\
  \ a system is called</span> <span m='306000'>decoupled. Why?</span> <span m='308000'>Well,\
  \ a normal system is called coupled.</span> <span m='311000'>Let's write out what\
  \ it would be.</span> <span m='314000'>Well, let's not write that. You know what\
  \ it looks like.</span> <span m='318000'>This is decoupled because it is not really\
  \ a system at all.</span> <span m='323000'>It is just two first-order equations\
  \ sitting side by side</span> <span m='328000'>and having nothing whatever to do\
  \ with each other.</span> <span m='334000'>This is two problems from the first day\
  \ of the term.</span> <span m='338000'>It is not one problem from the next to last\
  \ day of the term,</span> <span m='344000'>in other words. To solve this all you\
  \ say is u</span> <span m='348000'>is equal to some constant times e to the k1 t\
  \ and v</span> <span m='354000'>equals another constant times e to the k2 t.</span>\
  \ <span m='360000'>Coupled means that the x and y occur in both equations on the</span>\
  \ <span m='364000'>right-hand side. And, therefore,</span> <span m='366000'>you\
  \ cannot solve separately for x and y, you must solve together</span> <span m='370000'>for\
  \ both of them. Here I can solve separately for</span> <span m='374000'>u and v\
  \ and, therefore, the system has been decoupled.</span> <span m='377000'>Now, obviously,\
  \ if you can do that it's an</span> <span m='380000'>enormous advantage, not just\
  \ to the ease of</span> <span m='383000'>solution, because you can write down the\
  \ solution immediately,</span> <span m='388000'>but because something physical must\
  \ be going on there.</span> <span m='393000'>There must be some insight. There ought\
  \ to be some physical</span> <span m='397000'>reason for these new variables. Now,\
  \ that is where I plan to</span> <span m='402000'>start with. My plan for the lecture\
  \ is</span> <span m='405000'>first to work out, in some detail,</span> <span m='408000'>a\
  \ specific example where decoupling is done to show how</span> <span m='412000'>that\
  \ leads to the solution. And then we will go back and</span> <span m='417000'>see\
  \ how to do it in general -- -- because you will see,</span> <span m='422000'>as\
  \ I do the decoupling in this particular example,</span> <span m='425000'>that that\
  \ particular method, though it is suggested,</span> <span m='429000'>will not work\
  \ in general. I would need a more general</span> <span m='433000'>method. But let's\
  \ first go to the</span> <span m='435000'>example. It is a slight modification of</span>\
  \ <span m='437000'>one you should have done in recitation.</span> <span m='440000'>I\
  \ don't think I worked one of these in the lecture,</span> <span m='443000'>but\
  \ to describe it I have to draw two views of it to make</span> <span m='447000'>sure\
  \ you know exactly what I am talking about.</span> <span m='452000'>Sometimes it\
  \ is called the two compartment ice cube tray</span> <span m='455000'>problem, a\
  \ very old-fashion type of ice cube tray.</span> <span m='458000'>Not a modern one\
  \ that is all plastic where there is no</span> <span m='462000'>leaking from one\
  \ compartment to another.</span> <span m='464000'>The old kind of ice cube trays,\
  \ there were compartments and</span> <span m='468000'>these were metal separated\
  \ and you leveled the liquid because</span> <span m='472000'>it could leak through\
  \ the bottom that didn't go right to the</span> <span m='476000'>bottom. If you\
  \ don't know what I am</span> <span m='478000'>talking about it makes no difference.</span>\
  \ <span m='482000'>This is the side view. This is meant to be twice as</span> <span\
  \ m='486000'>long. But, to make it quite clear,</span> <span m='489000'>I will draw\
  \ the top view of this thing.</span> <span m='492000'>You have to imagine this is\
  \ a rectangle, all the sides are</span> <span m='497000'>parallel and everything.\
  \ This is one and this is two.</span> <span m='501000'>All I am trying to say is\
  \ that the cross-sectional area of</span> <span m='506000'>these two chambers, this\
  \ one has twice the</span> <span m='509000'>cross-sectional area of this one.</span>\
  \ <span m='514000'>So I will write a two here and I will write a one there.</span>\
  \ <span m='517000'>Of course, it is this hole here through which everything leaks.</span>\
  \ <span m='522000'>I am going to let x be the height of this liquid,</span> <span\
  \ m='525000'>the water here, and y the height of the water</span> <span m='528000'>in\
  \ that chamber. Obviously, as time goes by,</span> <span m='531000'>they both reach\
  \ the same height because of somebody's law.</span> <span m='535000'>Now, what is\
  \ the system of differential equations that</span> <span m='539000'>controls this?\
  \ Well, the essential thing is</span> <span m='544000'>the flow rate through here.\
  \ That flow rate through the hole</span> <span m='551000'>in units, let's say, in\
  \ liters per second.</span> <span m='556000'>Just so you understand, I am talking\
  \ about the volume</span> <span m='562000'>of liquid. I am not talking about the</span>\
  \ <span m='567000'>velocity. That is proportional to the</span> <span m='571000'>area\
  \ of the hole. So the cross-sectional area of</span> <span m='577000'>the hole.\
  \ And it is also times the</span> <span m='580000'>velocity of the flow, but the\
  \ velocity of the flow</span> <span m='584000'>depends upon the pressure difference.</span>\
  \ <span m='587000'>And that pressure difference depends upon the difference in</span>\
  \ <span m='592000'>height. All those are various people's</span> <span m='595000'>laws.\
  \ So times the height difference.</span> <span m='600000'>Of course, you have to\
  \ get the sign right.</span> <span m='603000'>I have just pointed out the height\
  \ difference is</span> <span m='606000'>proportional to the pressure at the hole.</span>\
  \ <span m='610000'>And it is that pressure at the hole that determines the</span>\
  \ <span m='614000'>velocity with which the fluid flows through.</span> <span m='617000'>Where\
  \ does this all produce our equations?</span> <span m='621000'>Well, x prime is\
  \ equal to, therefore, some constant,</span> <span m='625000'>depending on the area\
  \ of the hole and this constant of</span> <span m='629000'>proportionality with\
  \ the pressure and the units and</span> <span m='633000'>everything else times the\
  \ pressure difference I am talking</span> <span m='637000'>about. Well, if fluid\
  \ is going to flow</span> <span m='643000'>in this direction that must mean the\
  \ y height is higher than the</span> <span m='649000'>x height. So, to make x prime\
  \ positive,</span> <span m='652000'>it should be y minus x here.</span> <span m='656000'>Now,\
  \ the y prime is different. Because, again,</span> <span m='661000'>the rate of\
  \ fluid flow is determined.</span> <span m='663000'>This time, if y prime is positive,\
  \ if this is rising,</span> <span m='668000'>as it will be in this case, it's because\
  \ the fluid is</span> <span m='672000'>flowing in that direction. It is because\
  \ x is higher than</span> <span m='676000'>y. So this should be the same</span>\
  \ <span m='678000'>constant x minus y. But notice that right-hand side</span> <span\
  \ m='683000'>is the rate at which fluid is flowing into this tank.</span> <span\
  \ m='687000'>That is not the rate at which y is changing.</span> <span m='692000'>It\
  \ is the rate at which 2y is changing.</span> <span m='694000'>Why isn't there a\
  \ constant here?</span> <span m='696000'>There is. It's one.</span> <span m='698000'>That\
  \ is the one, this one cross-section.</span> <span m='701000'>The area here is one\
  \ and the cross-sectional area here is</span> <span m='705000'>two. And that is\
  \ the reason for the</span> <span m='707000'>one here and the two here, because\
  \ we are interested in</span> <span m='711000'>the rate at which fluid is being\
  \ added to this,</span> <span m='714000'>which is only related to the height, the\
  \ rate at which the</span> <span m='718000'>height is rising if you take into account\
  \ the cross-sectional</span> <span m='723000'>area. So there is the system.</span>\
  \ <span m='727000'>In order to use nothing but integers here,</span> <span m='731000'>I\
  \ am going to take c equals to two, so I don't have to put in</span> <span m='737000'>halves.\
  \ The final system is x prime</span> <span m='741000'>equals minus 2x, you have\
  \ to write them in the</span> <span m='745000'>correct order, and y prime equals,</span>\
  \ <span m='749000'>the twos cancel because c is two, is x minus y.</span> <span\
  \ m='755000'>So there is our system. Now the problem is I want to</span> <span m='758000'>solve\
  \ it by decoupling it. I want, in other words,</span> <span m='762000'>to find new\
  \ variables, u and v, which are more natural</span> <span m='766000'>to the problem\
  \ than the x and y that are so natural to the</span> <span m='770000'>problem that\
  \ the new system will just consistently be two</span> <span m='774000'>side-by-side\
  \ equations instead of the single equation.</span> <span m='779000'>The question\
  \ is, what should u and v be?</span> <span m='781000'>Now, the difference between\
  \ what I am going to do now and</span> <span m='785000'>what I am going to do later\
  \ in the period is later in the</span> <span m='788000'>period I will give you a\
  \ systematic way of finding what u</span> <span m='792000'>and v should be. Now\
  \ we are going to psyche out</span> <span m='795000'>what they should be in the\
  \ way in which people who solve</span> <span m='798000'>systems often do. I am going\
  \ to use the fact that</span> <span m='801000'>this is not just an abstract system\
  \ of equations.</span> <span m='804000'>It comes from some physical problem.</span>\
  \ <span m='808000'>And I ask, is there some system of variables,</span> <span m='811000'>which\
  \ somehow go more deeply into the structure of what's</span> <span m='816000'>going\
  \ on here than the na\u012Bve variables, which simply tell me</span> <span m='821000'>how\
  \ high the two tank levels are?</span> <span m='824000'>That is the obvious thing\
  \ I can see, but there are some</span> <span m='828000'>variables that go more deeply.\
  \ Now, one of them is sort of</span> <span m='833000'>obvious and suggested both\
  \ the form of the equation and by</span> <span m='838000'>this. Simply, the difference\
  \ in</span> <span m='841000'>heights is, in some ways, a more natural variable because</span>\
  \ <span m='845000'>that is directly related to the pressure difference,</span> <span\
  \ m='849000'>which is directly related to the velocity of flow.</span> <span m='852000'>They\
  \ will differ by just constant.</span> <span m='854000'>I am going to call that\
  \ the second variable,</span> <span m='857000'>or the difference in height let's\
  \ call it.</span> <span m='860000'>That's x minus y. That is a very natural variable</span>\
  \ <span m='863000'>for the problem. The question is,</span> <span m='865000'>what\
  \ should the other one be? Now you sort of stare at that</span> <span m='871000'>for\
  \ a while until it occurs to you that something is constant.</span> <span m='875000'>What\
  \ is constant in this problem?</span> <span m='878000'>Well, the tank is sitting\
  \ there, that is constant.</span> <span m='882000'>But what thing, which might be\
  \ a variable,</span> <span m='885000'>clearly must be a constant? It will be the\
  \ total amount of</span> <span m='889000'>water in the two tanks. These things vary,</span>\
  \ <span m='892000'>but the total amount of water stays the same because it is a</span>\
  \ <span m='897000'>homogenous problem. No water is coming in from the</span> <span\
  \ m='902000'>outside, and none is leaving the tanks through a little hole.</span>\
  \ <span m='908000'>Okay. What is the expression for the</span> <span m='911000'>total\
  \ amount of water in the tanks?</span> <span m='914000'>x plus 2y. Therefore, that\
  \ is a natural</span> <span m='919000'>variable also. It is independent of this\
  \ one.</span> <span m='923000'>It is not a simple multiply of it.</span> <span m='926000'>It\
  \ is a really different variable.</span> <span m='931000'>This variable represents\
  \ the total amount of liquid in the</span> <span m='936000'>two tanks. This represents\
  \ the pressure up</span> <span m='940000'>to a constant factor. It is proportional\
  \ to the</span> <span m='945000'>pressure at the hole. Okay.</span> <span m='948000'>Now\
  \ what I am going to do is say this is my change of</span> <span m='953000'>variable.\
  \ Now let's plug in and see what</span> <span m='957000'>happens to the system when\
  \ I plug in these two variables.</span> <span m='964000'>And how do I do that? Well,\
  \ I want to substitute and</span> <span m='969000'>get the new system. The new system,</span>\
  \ <span m='973000'>or rather the old system, but what makes it new is in</span>\
  \ <span m='979000'>terms of u and v. What will that be?</span> <span m='982000'>Well,\
  \ u prime is x prime plus 2y prime.</span> <span m='990000'>But I know what x prime\
  \ plus 2y prime is because I</span> <span m='995000'>can calculate it for this.\
  \ What will it be?</span> <span m='1000000'>x prime plus 2y prime is negative 2x\
  \ plus twice y prime,</span> <span m='1005000'>so it's plus 2x, which is zero.</span>\
  \ <span m='1008000'>And how about these two? 2y minus twice this,</span> <span m='1012000'>because\
  \ I want this plus twice that, so it 2y minus 2y,</span> <span m='1017000'>again,\
  \ zero. The right-hand side becomes</span> <span m='1022000'>zero after I calculate\
  \ x prime plus 2y.</span> <span m='1026000'>So that is zero. That would just,</span>\
  \ <span m='1029000'>of course, clear. Now, that makes sense,</span> <span m='1032000'>of\
  \ course. Since the total amount is</span> <span m='1035000'>constant, that says\
  \ that u prime is zero.</span> <span m='1039000'>Okay. What is v prime?</span> <span\
  \ m='1041000'>v prime is x prime minus y prime.</span> <span m='1045000'>What is\
  \ that? Well, once again we have to</span> <span m='1051000'>calculate. x prime\
  \ minus y prime is minus</span> <span m='1056000'>2x minus x, which is minus 3x,\
  \ and 2y minus negative y,</span> <span m='1063000'>which makes plus 3y. All right.</span>\
  \ <span m='1066000'>What is the system? The system is u prime equals</span> <span\
  \ m='1072000'>zero and v prime equals minus three times x minus</span> <span m='1080000'>y.\
  \ But x minus y is v.</span> <span m='1087000'>In other words,</span> <span m='1089000'>these\
  \ new two variables decouple the system.</span> <span m='1094000'>And we got them,\
  \ as scientists often do,</span> <span m='1098000'>by physical considerations. These\
  \ variables go more deeply</span> <span m='1104000'>into what is going on in that\
  \ system of two tanks than simply</span> <span m='1111000'>the two heights, which\
  \ are too obvious as</span> <span m='1115000'>variables. All right.</span> <span\
  \ m='1118000'>What is the solution? Well, the solution is,</span> <span m='1122000'>u\
  \ equals a constant and v is equal to?</span> <span m='1125000'>Well, the solution\
  \ to this equation is a different</span> <span m='1130000'>arbitrary constant from\
  \ that one.</span> <span m='1133000'>These are side-by-side equations that have\
  \ nothing</span> <span m='1137000'>whatever to do with each other, remember?</span>\
  \ <span m='1142000'>Times e to the minus 3t.</span> <span m='1145000'>Now, there\
  \ are two options. Either one leaves the solution</span> <span m='1150000'>in terms\
  \ of those new variables, saying they are more natural to</span> <span m='1155000'>the\
  \ problem, but sometimes, of course, one wants the answer</span> <span m='1160000'>in\
  \ terms of the old one. But, if you do that,</span> <span m='1164000'>then you have\
  \ to solve that. In order to save a little time,</span> <span m='1169000'>since\
  \ this is purely linear algebra, I am going to write --</span> <span m='1176000'>Instead\
  \ of taking two minutes to actually do the calculation</span> <span m='1179000'>in\
  \ front of you, I will just write down what the</span> <span m='1182000'>answer\
  \ is --</span> <span m='1193000'>-- in terms of u and x and y. In other words,</span>\
  \ <span m='1196000'>this is a perfectly good way to leave the answer if you are</span>\
  \ <span m='1202000'>allowed to do it. But if somebody says they want</span> <span\
  \ m='1206000'>the answer in terms of x and y, well, you have to give them</span>\
  \ <span m='1210000'>what they are paying for. In terms of x and y,</span> <span\
  \ m='1213000'>you have first to solve those equations backwards for x and y</span>\
  \ <span m='1217000'>in terms of u and v in which case you will get x equals</span>\
  \ <span m='1221000'>one-third of u plus 2v.</span> <span m='1224000'>Use the inverse\
  \ matrix or just do elimination,</span> <span m='1227000'>whatever you usually like\
  \ to do.</span> <span m='1231000'>And the other one will be one-third of u minus\
  \ v.</span> <span m='1241000'>And then, if you substitute in,</span> <span m='1247000'>you\
  \ will see what you will get is one-third of c1.</span> <span m='1256000'>Sorry.\
  \ u is c1.</span> <span m='1275000'>c1 plus 2 c2 e to the negative 3t.</span> <span\
  \ m='1279000'>And this is one-third of c1 minus c2 e to the minus 3t.</span> <span\
  \ m='1284000'>And so, the final solution is,</span> <span m='1288000'>in terms of\
  \ the way we usually write out the answer,</span> <span m='1293000'>x will be what?\
  \ Well, it will be one-third c1</span> <span m='1298000'>times the eigenvector one,\
  \ one plus one-third times c2</span> <span m='1303000'>times the eigenvector two,\
  \ negative one times e to the</span> <span m='1309000'>minus 3t. That is the solution\
  \ written</span> <span m='1314000'>out in terms of x and y either as a vector in\
  \ the usual way or</span> <span m='1320000'>separately in terms of x and y. But,\
  \ notice,</span> <span m='1325000'>in order to do that you have to have these backwards\
  \ equations.</span> <span m='1330000'>In other words, I need the equations in that</span>\
  \ <span m='1333000'>form. I need the equations because</span> <span m='1336000'>they\
  \ tell me what the new variables are.</span> <span m='1339000'>But I also have to\
  \ have the equations the other way in order</span> <span m='1344000'>to get the\
  \ solution in terms of x and y, finally.</span> <span m='1347000'>Okay. That was\
  \ all an example.</span> <span m='1351000'>For the rest of the period, I would like\
  \ to show you the</span> <span m='1355000'>general method of doing the same thing\
  \ which does not depend upon</span> <span m='1360000'>being clever about the choice\
  \ of the new variables.</span> <span m='1363000'>And then, at the very end of the\
  \ period, I will apply the</span> <span m='1368000'>general method to this problem\
  \ to see whether we get the same</span> <span m='1372000'>answer or not. What is\
  \ the general method?</span> <span m='1375000'>Our problem is the decouple. Now,\
  \ the first thing is you</span> <span m='1380000'>cannot always decouple. To decouple\
  \ the eigenvalues</span> <span m='1385000'>must all be real and non-defective.</span>\
  \ <span m='1389000'>In other words, if they are repeated they must</span> <span\
  \ m='1393000'>be complete. You must have enough</span> <span m='1396000'>independent\
  \ eigenvectors. So they must be real and</span> <span m='1401000'>complete. If repeated,</span>\
  \ <span m='1403000'>they must be complete. They must not be defective.</span> <span\
  \ m='1410000'>As I told you at the time when we studied complete and</span> <span\
  \ m='1414000'>incomplete, the most common case in which this occurs is when the</span>\
  \ <span m='1420000'>matrix is symmetric. If the matrix is real and</span> <span\
  \ m='1424000'>symmetric then you can always decouple the system.</span> <span m='1429000'>That\
  \ is a very important theorem, particularly since many</span> <span m='1434000'>of\
  \ the equilibrium problems normally lead to symmetric</span> <span m='1439000'>matrices\
  \ and are solved by decoupling.</span> <span m='1444000'>Okay. So what are we looking\
  \ for?</span> <span m='1457000'>We are assuming this and we need it.</span> <span\
  \ m='1459000'>In general, otherwise, you cannot decouple if you have</span> <span\
  \ m='1463000'>complex eigenvalues and you cannot decouple if you have</span> <span\
  \ m='1467000'>defective eigenvalues.</span> <span m='1474000'>Well, what are we\
  \ looking for? We are looking for new</span> <span m='1479000'>variables. u, v equals\
  \ a1,</span> <span m='1482000'>b1, a2, b2 times the x, y.</span> <span m='1489000'>And\
  \ this matrix is called D, the decoupling matrix and is</span> <span m='1496000'>what\
  \ we are looking for. How do I choose those new</span> <span m='1501000'>variables\
  \ u and v when I don't have any physical considerations</span> <span m='1506000'>to\
  \ guide me as I did before? Now, the key is to look instead</span> <span m='1511000'>at\
  \ what you are going to need. Remember, we are changing</span> <span m='1515000'>variables.\
  \ And, as I told you from the</span> <span m='1518000'>first days of the term, when\
  \ you change variables look</span> <span m='1522000'>at what you are going to need\
  \ to substitute in to make the change</span> <span m='1527000'>of variables. Don't\
  \ just start writing</span> <span m='1532000'>equations. What we are going to need\
  \ to</span> <span m='1535000'>plug into that system and change it to the (u,</span>\
  \ <span m='1539000'>v) coordinates is not u and v in terms of x and y.</span> <span\
  \ m='1544000'>What we need is x and y in terms of u and v to do the</span> <span\
  \ m='1549000'>substitution. What we need is the inverse of</span> <span m='1552000'>this.\
  \ So, in order to do the</span> <span m='1555000'>substitution, what we need is\
  \ (x,</span> <span m='1558000'>y). Oops.</span> <span m='1560000'>Let's call them\
  \ prime. Let's call these a1,</span> <span m='1564000'>b1, a2, b2 because these\
  \ are going to be much more important</span> <span m='1569000'>to the problem than\
  \ the other ones.</span> <span m='1572000'>Okay. I am going to,</span> <span m='1573000'>I\
  \ should call this matrix D inverse, that would be a</span> <span m='1578000'>sensible\
  \ thing to call it. Since this is the important</span> <span m='1582000'>matrix,\
  \ this is the one we are going to need to do the</span> <span m='1587000'>substitution,\
  \ I am going to give it another</span> <span m='1591000'>letter instead. And the\
  \ letter that comes after</span> <span m='1597000'>D is E. Now, E is an excellent\
  \ choice</span> <span m='1600000'>because it is also the first letter of the word\
  \ eigenvector.</span> <span m='1606000'>And the point is the matrix E, which is\
  \ going to work,</span> <span m='1611000'>is the matrix whose columns are the two\
  \ eigenvectors.</span> <span m='1628000'>The columns are the two eigenvectors.</span>\
  \ <span m='1631000'>Now, even if you didn't know anything that would be</span> <span\
  \ m='1636000'>practically the only reasonable choice anybody could make.</span>\
  \ <span m='1641000'>What are we looking for? To make a linear change of</span> <span\
  \ m='1646000'>variables like this really means to pick new i and j vectors.</span>\
  \ <span m='1653000'>You know, from the first days of 18.02, what you want is a new</span>\
  \ <span m='1657000'>coordinate system in the plane. And the coordinate system in</span>\
  \ <span m='1661000'>the plane is determined as soon as you tell what the new i is</span>\
  \ <span m='1666000'>and what the new j is in the new system.</span> <span m='1668000'>To\
  \ establish a linear change of coordinates amounts to picking</span> <span m='1673000'>two\
  \ new vectors that are going to play the role of i and j</span> <span m='1677000'>instead\
  \ of the old i and the old j.</span> <span m='1681000'>Okay, so pick two vectors\
  \ which somehow are important to this</span> <span m='1687000'>matrix. Well, there\
  \ are only two,</span> <span m='1691000'>the eigenvectors. What else could they\
  \ possibly</span> <span m='1697000'>be? Now, what is the relation?</span> <span\
  \ m='1700000'>I say with this, what happens is I say that</span> <span m='1705000'>alpha\
  \ one corresponds, and alpha two,</span> <span m='1709000'>these are vectors in\
  \ the xy-system.</span> <span m='1715000'>Well, if I change the coordinates to u\
  \ and v,</span> <span m='1718000'>in the uv-system they will correspond to the vectors\
  \ one,</span> <span m='1722000'>zero. In other words,</span> <span m='1725000'>the\
  \ vector that we would normally call i in the u,</span> <span m='1728000'>v system.\
  \ And this one will correspond to</span> <span m='1732000'>the vector zero, one.</span>\
  \ <span m='1734000'>Now, if you don't believe that I will calculate it for you.</span>\
  \ <span m='1740000'>The calculation is trivial. Look.</span> <span m='1744000'>What\
  \ have we got? (x, y) equals a1,</span> <span m='1749000'>b1, a2, b2.</span> <span\
  \ m='1753000'>This is the column vector alpha one.</span> <span m='1758000'>This\
  \ is the column vector alpha two.</span> <span m='1762000'>Now, here is u and v.\
  \ Suppose I make u and v equal to</span> <span m='1770000'>one, zero, what happens\
  \ to x and y?</span> <span m='1775000'>Your matrix multiply. One, zero.</span> <span\
  \ m='1778000'>So a1 plus zero, b1 plus zero.</span> <span m='1785000'>It corresponds\
  \ to the column vector (a1, b1).</span> <span m='1790000'>And in the same way zero,\
  \ one corresponds to</span> <span m='1797000'>(a2, b2).</span> <span m='1805000'>Just\
  \ by matrix multiplication. And that shows that these</span> <span m='1812000'>correspond.\
  \ In the uv-system the two</span> <span m='1816000'>eigenvectors are now called\
  \ i and j.</span> <span m='1821000'>Well, that looks very promising, but the program\
  \ now</span> <span m='1827000'>is to do the substitution to substitute into the\
  \ system x</span> <span m='1834000'>prime equals Ax and see if it is decoupled in\
  \ the</span> <span m='1842000'>uv-coordinates. Now, I don't dare let you do</span>\
  \ <span m='1847000'>this by yourself because you will run into trouble.</span> <span\
  \ m='1851000'>Nothing is going to happen. You will just get a mess and</span> <span\
  \ m='1854000'>will say I must be missing something.</span> <span m='1857000'>And\
  \ that is because you are missing something.</span> <span m='1861000'>What you are\
  \ missing, and this is a good occasion to</span> <span m='1865000'>tell you, is\
  \ that, in general, three-quarters of</span> <span m='1869000'>the civilized world\
  \ does not introduce eigenvalues and</span> <span m='1874000'>eigenvectors the way\
  \ you learn them in 18.03.</span> <span m='1878000'>They use a different definition\
  \ that is identical.</span> <span m='1882000'>I mean it is equivalent. The concept\
  \ is the same,</span> <span m='1887000'>but it looks a little different.</span>\
  \ <span m='1891000'>Our definition is what? Well, what is an eigenvalue and</span>\
  \ <span m='1895000'>eigenvector? The basic thing is this</span> <span m='1897000'>equation.</span>\
  \ <span m='1906000'>This is a two-by-two matrix, right?</span> <span m='1908000'>This\
  \ is a column vector with two entries.</span> <span m='1911000'>The product has\
  \ to be a column vector with two entries,</span> <span m='1915000'>but both entries\
  \ are supposed to be zero so I will write it</span> <span m='1919000'>this way.\
  \ This way first defines what an</span> <span m='1923000'>eigenvalue is. It is something\
  \ that makes the</span> <span m='1926000'>determinant zero. And then it defines\
  \ what an</span> <span m='1929000'>eigenvector is. It is, then,</span> <span m='1931000'>a\
  \ solution to the system that you can get because the</span> <span m='1935000'>determinant\
  \ is zero. Now, that is not what most</span> <span m='1939000'>people do. What most\
  \ people do is the</span> <span m='1941000'>following. They write this equation</span>\
  \ <span m='1944000'>differently by having something on both sides.</span> <span\
  \ m='1949000'>Using the distributive law, what goes on the left side is A</span>\
  \ <span m='1953000'>alpha one. What is that?</span> <span m='1955000'>That is a\
  \ column vector with two entries.</span> <span m='1958000'>What goes on the right?\
  \ Well, lambda one times the</span> <span m='1962000'>identity times alpha one.\
  \ Now, the identity matrix times</span> <span m='1967000'>anything just reproduces\
  \ what was there.</span> <span m='1970000'>There is no difference between writing\
  \ the identity times alpha</span> <span m='1975000'>one and just alpha one all by\
  \ itself.</span> <span m='1980000'>So that is what I am going to do.</span> <span\
  \ m='1982000'>This is the definition of eigenvalue and eigenvector that</span> <span\
  \ m='1987000'>all the other people use. Most linear algebra books use</span> <span\
  \ m='1992000'>this definition, or most books use a different</span> <span m='1996000'>approach\
  \ and say, here is an eigenvalue and an</span> <span m='2000000'>eigenvector. And\
  \ it requires them to define</span> <span m='2003000'>them in the opposite order.\
  \ First what alpha one is and</span> <span m='2008000'>then what lambda one is.\
  \ See, I don't have any</span> <span m='2013000'>determinant now. So what is the\
  \ definition?</span> <span m='2016000'>And they like it because it has a certain\
  \ geometric flavor that</span> <span m='2020000'>this one lacks entirely. This is\
  \ good for solving</span> <span m='2023000'>differential equations, which is why\
  \ we are using it in</span> <span m='2027000'>18.03, but this has a certain geometric\
  \ content.</span> <span m='2030000'>This way thinks of A as a linear transformation\
  \ of the</span> <span m='2034000'>plane, a shearing of the plane. You take the plane\
  \ and do</span> <span m='2037000'>something to it. Or, you squish it like that.</span>\
  \ <span m='2042000'>Or, you rotate it. That's okay,</span> <span m='2044000'>too.\
  \ And the matrix defines a linear</span> <span m='2047000'>transformation to the\
  \ plane, every vector goes to another</span> <span m='2051000'>vector. The question\
  \ it asks is,</span> <span m='2054000'>is there a vector which is taken by this\
  \ linear</span> <span m='2058000'>transformation and just left alone or stretched,</span>\
  \ <span m='2061000'>is kept in the same direction but stretched?</span> <span m='2065000'>Or,\
  \ maybe its direction is reversed and it is stretched or</span> <span m='2069000'>it\
  \ shrunk. But, in general,</span> <span m='2073000'>if there are real eigenvalues\
  \ there will be such vectors that</span> <span m='2078000'>are just left in the\
  \ same direction but just stretched or</span> <span m='2083000'>shrunk. And what\
  \ is the lambda?</span> <span m='2086000'>The lambda then is the amount by which\
  \ they are stretched or</span> <span m='2091000'>shrunk, the factor. This way, first\
  \ we have to find</span> <span m='2095000'>the vector, which is left essentially\
  \ unchanged,</span> <span m='2099000'>and then the number here that goes with it\
  \ is the stretching</span> <span m='2104000'>factor or the shrinking factor. But\
  \ the end result is the pair</span> <span m='2111000'>alpha one and lambda one,\
  \ regardless of which order you</span> <span m='2115000'>find them, satisfied the\
  \ same equation.</span> <span m='2118000'>Now, a consequence of this definition\
  \ we are going to need</span> <span m='2122000'>in the calculation that I am going\
  \ to do in just a moment.</span> <span m='2126000'>Let me calculate that out. What\
  \ I want to do is calculate</span> <span m='2131000'>the matrix A times E. I am\
  \ going to need to calculate</span> <span m='2136000'>that. Now, what is that?</span>\
  \ <span m='2138000'>Remember, E is the matrix whose columns are the eigenvectors.</span>\
  \ <span m='2143000'>That is the matrix alpha one, alpha two.</span> <span m='2147000'>Now,\
  \ what is this? Well, in both Friday's lecture</span> <span m='2151000'>and Monday's\
  \ lecture, I used the fact that if you do</span> <span m='2155000'>a multiplication\
  \ like that it is the same thing as doing the</span> <span m='2161000'>multiplication\
  \ A alpha one and putting it in the first column.</span> <span m='2168000'>And then\
  \ A alpha two is the column vector that goes in the</span> <span m='2173000'>second\
  \ column. But what is this?</span> <span m='2176000'>This is lambda one alpha one.\
  \ And this is lambda two alpha</span> <span m='2182000'>two by this other definition\
  \ of eigenvalue and eigenvector.</span> <span m='2188000'>And what is this? Can\
  \ I write this in terms of</span> <span m='2194000'>matrices? Yes indeed I can.</span>\
  \ <span m='2196000'>This is the matrix alpha one, alpha two times this matrix</span>\
  \ <span m='2202000'>lambda one, lambda two, zero, zero.</span> <span m='2206000'>Check\
  \ it out. Lambda one plus zero,</span> <span m='2210000'>lambda one times this thing\
  \ plus zero, the first entry is</span> <span m='2216000'>exactly that. And the same\
  \ way the second</span> <span m='2221000'>column doing the same calculation is exactly\
  \ this.</span> <span m='2226000'>What is that? That is e times this matrix</span>\
  \ <span m='2230000'>lambda one, zero, zero, lambda two.</span> <span m='2234000'>Okay.\
  \ We are almost finished now.</span> <span m='2237000'>Now we can carry out our\
  \ work. We are going to do the</span> <span m='2242000'>substitution. I start with\
  \ a system.</span> <span m='2246000'>Remember where we are. I am starting with this\
  \ system.</span> <span m='2253000'>I am going to make the substitution x equal to\
  \ this</span> <span m='2259000'>matrix E, whose columns are the eigenvectors.</span>\
  \ <span m='2265000'>I am in introducing, in other words,</span> <span m='2269000'>new\
  \ variables u and v according to that thing.</span> <span m='2275000'>u is the column\
  \ vector, u and v.</span> <span m='2280000'>And x, as usual,</span> <span m='2283000'>is\
  \ the column vector x and y. So I am going to plug it in.</span> <span m='2288000'>Okay.\
  \ Let's plug it in.</span> <span m='2290000'>What do I get? I take the derivative.</span>\
  \ <span m='2293000'>E is a constant matrix so that makes E times u prime,</span>\
  \ <span m='2297000'>is equal to A times, x is E times u again.</span> <span m='2301000'>Now,\
  \ at this point,</span> <span m='2304000'>you would be stuck, except I calculated\
  \ for you A</span> <span m='2308000'>times E is E times that funny diagonal matrix\
  \ with the</span> <span m='2312000'>lambdas. So this is E times that funny</span>\
  \ <span m='2318000'>matrix of the lambdas, the eigenvalues,</span> <span m='2321000'>and\
  \ still the u at the end of it.</span> <span m='2325000'>So where are we? E times\
  \ u prime equals E times</span> <span m='2330000'>this thing. Well, multiply both\
  \ sides by E</span> <span m='2334000'>inverse and you can cancel them out.</span>\
  \ <span m='2339000'>And so the end result is that after you have made the</span>\
  \ <span m='2344000'>substitution in terms of the new variables u, what you get is\
  \ u</span> <span m='2350000'>prime equals lambda one, lambda two, zero,</span> <span\
  \ m='2354000'>zero times u. Let's write that out in terms</span> <span m='2358000'>of\
  \ a system. This is u prime is equal to,</span> <span m='2362000'>well, this is\
  \ u, v here.</span> <span m='2364000'>It is lambda one times u plus zero times v.</span>\
  \ <span m='2370000'>And the other one is v prime equals zero times u plus lambda</span>\
  \ <span m='2380000'>two times v. We are decoupled.</span> <span m='2385000'>In just\
  \ one sentence you would say --</span> <span m='2392000'>In other words, if you\
  \ were reading a book that</span> <span m='2395000'>sort of assumed you knew what\
  \ was going on,</span> <span m='2399000'>all it would say is as usual. That is to\
  \ make you feel bad.</span> <span m='2404000'>Or, as is well-known to make you feel\
  \ even worse.</span> <span m='2408000'>Or, the system is decoupled by choosing as\
  \ the new basis for</span> <span m='2413000'>the system the eigenvectors of the\
  \ matrix and in terms of the</span> <span m='2418000'>resulting new coordinates,\
  \ the decoupled system will be</span> <span m='2423000'>the following where the\
  \ constants are the eigenvalues.</span> <span m='2429000'>And so the solution will\
  \ be u equals c1 times e to the lambda1</span> <span m='2433000'>t and v is equal\
  \ to c2 times e to the</span> <span m='2438000'>lambda2 t.</span> <span m='2440000'>Of\
  \ course, if you want it back in terms now of x and y,</span> <span m='2444000'>you\
  \ will have to go back to here, to these equations and</span> <span m='2448000'>then\
  \ plug in for u and v what they are.</span> <span m='2451000'>And then you will\
  \ get the answer in terms of x and y.</span> <span m='2455000'>Okay. We have just\
  \ enough time to</span> <span m='2459000'>actually carry out this little program.</span>\
  \ <span m='2464000'>It takes a lot longer to derive than it does actually to do,</span>\
  \ <span m='2470000'>so let's do it for this system that we were talking about</span>\
  \ <span m='2476000'>before. Decouple the system,</span> <span m='2479000'>x, y prime\
  \ equals the matrixes negative two,</span> <span m='2484000'>two, one, negative\
  \ one.</span> <span m='2496000'>Okay. What do I do?</span> <span m='2497000'>Well,\
  \ I first have to calculate the eigenvalues in the</span> <span m='2502000'>eigenvectors,\
  \ so the Ev's and Ev's.</span> <span m='2505000'>The characteristic equation is\
  \ lambda squared.</span> <span m='2509000'>The trace is negative three, but you\
  \ have to change the</span> <span m='2514000'>sign. The determinant is two minus</span>\
  \ <span m='2517000'>two, so that is zero. There is no constant term here.</span>\
  \ <span m='2522000'>It is zero. That is the characteristic</span> <span m='2525000'>equation.\
  \ The roots are obviously lambda</span> <span m='2528000'>equals zero, lambda equals\
  \ negative three.</span> <span m='2532000'>And what are the eigenvectors that go\
  \ with that?</span> <span m='2535000'>With lambda equals zero goes the eigenvector,</span>\
  \ <span m='2539000'>minus two. Well, I subtract zero here,</span> <span m='2542000'>so\
  \ the equation I have to solve is minus 2 a1 plus --</span> <span m='2548000'>I\
  \ am not going to write 2 a2, which is what you have been</span> <span m='2552000'>writing\
  \ up until now. The reason is because I ran</span> <span m='2556000'>into trouble\
  \ with the notation and I had to use,</span> <span m='2560000'>as the eigenvector,\
  \ not a1, a2 but a1,</span> <span m='2563000'>b1. So it should be a b1 here,</span>\
  \ <span m='2566000'>not the a2 that you are used to.</span> <span m='2568000'>The\
  \ solution, therefore, is alpha one equals</span> <span m='2572000'>one, one. And\
  \ for lambda equals negative</span> <span m='2575000'>three, the corresponding eigenvector\
  \ this time will be --</span> <span m='2582000'>Now I have to subtract negative\
  \ three from here,</span> <span m='2586000'>so negative two minus negative three\
  \ makes one.</span> <span m='2590000'>That is a1 plus 2 b1 equals zero,</span> <span\
  \ m='2595000'>a logical choice for the eigenvector here.</span> <span m='2599000'>The\
  \ second eigenvector would be make b1 equal to one,</span> <span m='2604000'>let's\
  \ say, and then a1 will be negative two.</span> <span m='2608000'>Okay. Now what\
  \ do we have to do?</span> <span m='2612000'>Now, what we want is the matrix E.</span>\
  \ <span m='2615000'>The matrix E is the matrix of eigenvectors,</span> <span m='2618000'>so\
  \ it is the matrix one, one, negative two,</span> <span m='2622000'>one.</span>\
  \ <span m='2624000'>The next thing we want is what the new variables u and v are.</span>\
  \ <span m='2630000'>For that, we will need E inverse.</span> <span m='2632000'>How\
  \ do you calculate the inverse of a two-by-two matrix?</span> <span m='2639000'>You\
  \ switch the two diagonal elements, there I have switched</span> <span m='2644000'>them,\
  \ and you leave the other two where they are but change</span> <span m='2649000'>their\
  \ sign. So it is two up here and</span> <span m='2653000'>negative one there. Maybe\
  \ I should make this one</span> <span m='2657000'>purple and then that one purple\
  \ to indicate that I have switched</span> <span m='2663000'>them. I am not done\
  \ yet.</span> <span m='2665000'>I have to divide by the determinant.</span> <span\
  \ m='2670000'>What is the determinant? It is one minus negative two,</span> <span\
  \ m='2676000'>which is three, so I have to divide by three.</span> <span m='2682000'>I\
  \ multiply everything here by one-third.</span> <span m='2687000'>Okay. And what\
  \ is the decoupled</span> <span m='2691000'>system? The new variables are u equals</span>\
  \ <span m='2696000'>one-third.</span> <span m='2708000'>In other words, the new\
  \ variables are given by</span> <span m='2711000'>D. It is u, v equals one,</span>\
  \ <span m='2713000'>two, negative one, one times one-third times x,y.</span> <span\
  \ m='2719000'>That is the expression for u,</span> <span m='2721000'>v in terms\
  \ of x and y. It's this matrix D,</span> <span m='2725000'>the decoupling matrix\
  \ which is the one that is used.</span> <span m='2730000'>And that gives this system\
  \ u equals one-third of x plus 2y</span> <span m='2737000'>on top. And what is the\
  \ v entry?</span> <span m='2744000'>v is one-third of minus x plus y.</span> <span\
  \ m='2751000'>Now, are those the same variables that I used before?</span> <span\
  \ m='2768000'>Yes. This is my new and better you,</span> <span m='2770000'>the one\
  \ I got by just blindly following the method instead of</span> <span m='2774000'>looking\
  \ for physical things with physical meaning.</span> <span m='2777000'>It differs\
  \ from the old one just by a constant factor.</span> <span m='2781000'>Now, that\
  \ doesn't have any effect on the resulting equation</span> <span m='2785000'>because\
  \ if the old one is u prime equals zero the new one is</span> <span m='2789000'>one-third\
  \ u prime equals zero. It is still the same equation,</span> <span m='2794000'>in\
  \ other words. And how about this one?</span> <span m='2796000'>This one differs\
  \ from the other one by the factor minus</span> <span m='2800000'>one-third. If\
  \ I multiply that v through by</span> <span m='2803000'>minus one-third, I get this\
  \ v.</span> <span m='2805000'>And, therefore, that too does not affect the</span>\
  \ <span m='2807000'>second equation. I simply multiply both sides by</span> <span\
  \ m='2811000'>minus one-third. The new v still satisfies the</span> <span m='2814000'>equation\
  \ minus three times v.</span> </p>"
type: course
uid: 3c731b47f01dcf0ecbf44050afa6fc18

---
None