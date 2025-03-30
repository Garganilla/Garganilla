<!DOCTYPE html>
<html>

<head>
   <title>AOT</title>
    <style>

           .topnav {
             background-color:rgb(34, 34, 34);
             position: fixed; 
             top: 0;
             height: 70px;
             width: 1503px;
             margin-left: -20px;
        }

           .topnav a {
             float: left;
             color: white;
             padding: 25px 16px;
             font-size: 20px;
             font-family: Arial, Helvetica, sans-serif;
             margin-left: 95px;         
        }

           .logo {
             width: 75px;
             height: 40px;
             top: 16px;
             position: fixed;
        }

            header{
             background-image: url(cover2.png);
             background-size: cover;
             background-position: center;
             color: white;
             padding: 88px 20px;
             text-align: left;
        }
        
           .row {
             display: -webkit-box;
             display: -ms-flexbox;
             display: flex;
             -ms-flex-wrap: wrap;
             flex-wrap: wrap;
        }
          
           .container {
             margin-right: 150px;
             margin-left: 150px;
        }

            .col-lg-1{
             flex: 0 0 8.333333%;
             max-width: 8.333333%;
        }
        
            .col-lg-2{
             flex: 0 0 16.666666%;
             max-width: 16.666666%;
        }
        
            .col-lg-3{
             flex: 0 0 25%;
             max-width: 25%;
        }
        
            .col-lg-4{
             flex: 0 0 33.333333%;
             max-width: 33.333333%;
        }
        
            .col-lg-5{
             flex: 0 0 41.666666%;
             max-width: 41.666666%;
        }
        
            .col-lg-6{
             flex: 0 0 50%;
             max-width: 50%;
        }
        
            .col-lg-7{
             flex: 0 0 58.333333%;
             max-width: 58.333333%;
        }
        
           .col-lg-8{
             flex: 0 0 66.666666%;
             max-width: 66.666666%;
        }
        
            .col-lg-9{
             flex: 0 0 75%;
             max-width: 75%;
        }
       
             .col-lg-10{
             flex: 0 0 83.333333%;
             max-width: 83.333333%;
        }
        
            .col-lg-11{
             flex: 0 0 91.666666%;
             max-width: 91.666666%;
        }
        
            v.col-lg-12{
             flex: 0 0 100%;
             max-width: 100%;
        }
        
            .rowheight{
             height: 300px;
        }
        
           .paragraph{
             font-size:18px;
             font-family: Georgia, 'Times New Roman', Times, serif;
             text-align: left;
             color: white;
             line-height: 1.5;
        }
        
           .BG{
             background-color: black;
        }
        
           h1{
            margin-left: 140px;
            margin-bottom: 70px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 40px;
        }
        
           .name{
             text-align: center;
             font-family: Georgia, 'Times New Roman', Times, serif;
             font-size: 47px;
        }
        
           .abilities{
             margin-top: -40px;
             margin-left: 30px;
        }
        
           .margin2{
            margin-bottom: 10px;
        }
        
           .margin3{
            margin-bottom: 25px;
        }
        
            .titan{
                margin-left: 200px;
                margin-right: 70px;
                margin-top: 30px;
        }
        
           .ul{
                margin-left: 10px;
                margin-right: -24px;
        }
        
           .yeager{
                margin-left: 10px;
                margin-right: -26px
        }
        
           .yeager2{
                margin-left: 10px;
                margin-right: 5px;
        }       
        
            .ymir{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .ymir2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .ymir3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .yd{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -30px;
        }
        
            .yd2{
                margin-left: 25px;
                margin-top: -5px;
                margin-right: -30px;
        }
        

            .warhammer{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .warhammer2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .warhammer3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .hwd{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -30px;
        }
        
            .hwd2{
                margin-left: 25px;
                margin-top: 40px;
                margin-right: -30px;
        }
        
            .beast{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .beast2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .beast3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .zd{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -15px;
        }
        
            .jaw{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .jaw2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .jaw3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .jd{
                margin-left: 25px;
                margin-right: -20px;
                margin-top: -20px;
        }
        
            .jd2{
                margin-left: 25px;
                margin-right: -23px;
                margin-top: -5px;
        }
        
            .armored{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .armored2{
                margin-top: 100px;
                margin-left: 50px;
        }
        
              .armored3{
                margin-left: 15px;
                margin-right: 10px;
                margin-top: 50px;
        }
        
              .ad{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -30px;
        }
        
              .eren{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .eren2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .eren3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .ed{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -25px;
        }
        
            .cart{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .cart2{
                margin-top: 100px;
                margin-left: 50px;
        }
        
            .cart3{
                margin-left: 15px;
                margin-right: 10px;
                margin-top: 50px;
        }
        
            .pd{
                margin-left: 25px;
                margin-right: -24px;
                margin-top: -20px;
        }
        
            .pd2{
                margin-left: 25px;
                margin-right: -30px;
                margin-top: -5px;
        }
        
            .Colossal{
                padding-left: 75px;
                padding-right: 75px;
        }
        
            .Colossal2{
                margin-top: 50px;
                margin-left: 50px;
        }
        
            .Colossal3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .cd{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -20px;
        }
        
            .cd2{
                margin-left: 25px;
                margin-right: -30px;
                margin-top: -5px;
        }
        
            .female{
                padding-left: 75px;
                padding-right: 75px;
        }
            .female2{
                margin-top: 50px;
                margin-left: 50px
        }
        
            .female3{
                margin-left: 15px;
                margin-right: 10px;
        }
        
            .fd{
                margin-left: 25px;
                margin-top: -20px;
                margin-right: -15px;
            }
        
   </style>
</head>

<body>

    <header>
        
        <h1><b>Attack On Titan: All Nine Titans & Their Powers</b></h1>
        <nav class="topnav">
            <a>Attack on Titan</a>
        </nav>
            <img src="logo.jpg" alt="logo" class="logo">
        
    </header>
    <div class="row BG">
     <div class="col-lg-12">
       
               
     </div>
     <div class="col-lg-11 paragraph">
      <p class="titan"> <b>Titans</b> (巨人 Kyojin?, lit. "Giant(s)") were a species of giant man-eating humanoids that served as the catalyst for the events in the Attack on Titan series. The people inside the Walls were taught that they first appeared 107 years prior to year 850 and rapidly exterminated humanity to the point of near-extinction. In reality, they were transformed humans known as Subjects of Ymir and had existed for nearly 2,000 years.However, after Eren Yeager's death and Ymir's decision to relinquish her power, all the Titans returned to their human forms, thereby rendering the species nonexistent. </p>
            </div>
         </div>

         <!--2ndrow-->
        <div class="row BG">
     <div class="col-lg-12 ymir">
               
     </div>
     <div class="col-lg-12 ymir2">
<img src="ymir.png" width="460px" height="730">
   
    </div>

    <div class="col-lg-5 paragraph ymi3r">
        <p class="name">The Founding Titan</p>
    <p class="yd"> The Founding Titan is the first of the Nine Titans in Attack on Titan. It is also known as the Progenitor Titan.</p>

    <p class="yd2">Ymir Fritz became the Founding Titan as a young girl, around 2,000 years before the events of the story. She was a slave who encountered the "Source of all living matter" while trying to escape her captors.</p>
    <br></br> 
    <p class="abilities">Abilities: </p>
    <ul class="ul">
            <li class="margin2"> <b>Titan creation</b>: The power to turn Subjects of Ymir into Titans, including the Colossal Titan.</li>
            
            <li class="margin2"> <b>Titan control</b>: The ability to control the actions of Pure Titans</li>
            
            <li class="margin2"> <b> Memory manipulation</b>: The ability to manipulate and erase the memories of Subjects of Ymir </li>
            
            <li class="margin2"> <b>Body manipulation</b>: The ability to change the body composition of Subjects of Ymir </li>
            
            <li class="margin2"> <b>Telepathic communication</b>: The ability to communicate with Subjects of Ymir through the Paths, a series of mysterious channels</li>
            
            <li class="margin2"> <b>Clairvoyance</b>:The ability to see the future.</li>
         
        </ul>

            
            </div>
         </div>

         <!--3rdrow-->
         <div class="row" style="background-color: black;">
            <div class="col-lg-12 warhammer">
                      
            </div>
            <div class="col-lg-12 warhammer2">
       <img src="wh.jpg" width="460px" height="730px">
          
           </div>
       
           <div class="col-lg-5 paragraph warhammer3">
               <p class="name">The War Hammer Titan</p>
           <p class="hwd"> The War Hammer Titan, introduced in the Marley Arc, had a foreboding presence and lived up to its hype with its ability to alter environments and create powerful weapons.</p>
           
           <p class="hwd2">Unlike other Titans, the War Hammer Titan's user could manifest and control it from the ground instead of the traditional nape, allowing for remote operation and terrain-based offense.</p>
       
           <p class="hwd2">The War Hammer Titan had the highest offensive ability among the Nine Titans, able to create and manipulate hardened constructs, but had to use its structural hardening ability in moderation to avoid exhaustion.</p>
           <br></br> 
           <p class="abilities">Abilities: </p>
           <ul class="ul">
                   <li class="margin2"> <b>Create weapons</b>: The War Hammer Titan can create weapons like swords, spears, crossbows, whips, and its signature hammer.</li>
                   
                   <li class="margin2"> <b>Create spikes</b> The War Hammer Titan can create spikes from the ground to impale enemies.</li>
                   
                   <li class="margin2"> <b>Flood areas</b> The War Hammer Titan can flood areas with protrusions like spikes.</li>
                   
                   <li class="margin2"> <b>Create flexible weapons</b>: The War Hammer Titan can create flexible weapons like the string of a crossbow or the whips of a cat-o'-nine-tails.</li>
                   
                   <li class="margin2"> <b>Encase the human operator in a crystal</b> The War Hammer Titan can encase the human operator in a crystal casing, allowing them to control the Titan body.</li>
                
               </ul>
       
                   
                   </div>
                </div>
     
                <!--4throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 beast">
                              
                    </div>
                    <div class="col-lg-12 beast2">
               <img src="bt.png" width="460px" height="750px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph beast3">
                       <p class="name">The Beast Titan</p>
                   <p class="zd">In 842, Zeke and his family are treated like a real Marleyan family, while Zeke acquires the title of Marley warrior. One year later, Zeke Jaeger took the power of the Beast Titan from Tom Ksaver.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul">
                           <li class="margin3"> <b>Throwing objects</b>: Zeke Yeager's Beast Titan demonstrated precision and destructive force, crushing rocks and annihilating the Survey Corps during Shiganshina District battle and the Mid-East Allied Forces' naval fleet at Fort Slava.</li>
                           
                           <li class="margin3"> <b>Hardening</b>: Allows them to create a hardened, crystalline layer on their body, essentially acting as a defensive barrier against attacks, providing increased durability and protection against blades and other weapons; it can also be used offensively to create sharp, hardened protrusions for piercing attacks.</li>
                           
                           <li class="margin3"> <b>Turning humans into Titans</b>: Zeke Yeager can transform humans into mindless Titans by ingesting his spinal fluid and triggering their transformation through screaming, allowing him to control other Titans.</li>
                           
                           <li class="margin3"> Zeke Yeager can speak human language even while in Beast Titan form.</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--5throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 jaw">
                              
                    </div>
                    <div class="col-lg-12 jaw2">
               <img src="jt.png" width="460px" height="770px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph jaw3">
                       <p class="name">The Jaw Titan</p>
                   <p class="jd">The <b>Jaw Titan</b> was one of the Nine Titans with a ferociously powerful set of jaws and claws that were able to tear through almost anything. Due to its small size, it was known to be one of the fastest out of the Nine Titans.</p>
               
                   <p class="jd2">Ymir, a Survey Corps member, transformed into the Jaw Titan and knew about the world outside the Walls.</p>
                   
                   <p class="jd2">Porco Galliard, Eldian brother of Marcel Galliard, inherited the Titan after Paradis Island Operation.</p>
                   
                   <p class="jd2">Falco Grice's Jaw Titan had two sets of teeth, wings, tail, and a feathered body.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul">
                           <li class="margin2"> <b>Speed and agility</b>:  The Jaw Titan, characterized by its small size, agility, and quickness, can outmaneuver other Titans through its hit-and-run tactics.</li>
                           
                           <li class="margin3"> <b>Crushing strength</b>: The Jaw Titan possesses exceptional strength in its jaws and claws, capable of chewing through Titan armor and the crystal shell surrounding the War Hammer Titan.</li>
                           
                           <li class="margin3"> <b>Hardened claws</b>: The Jaw Titan utilizes powerful claws to rip through enemies and climb surfaces, causing severe damage to armored opponents.</li>
                           
                           <li class="margin3"> <b>Flight</b>: Falco's Jaw Titan has the ability to fly. Falco's name is a hint of what his Titan would be capable of, as it is derived from the Latin word for "falcon".</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--6throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 armored">
                              
                    </div>
                    <div class="col-lg-12 armored2">
               <img src="at.jpg" width="460px" height="795px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph armored3">
                       <p class="name">The Armored Titan</p>
                   <p class="ad">In the year 843, Reiner Braun was chosen to inherit the power of the Armored Titan. He would later make use of his Titan form in a war between Marley and an enemy nation, using his Armored Titan to take the brunt of enemy artillery fire.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul">
                           <li class="margin3"> <b>Hardening</b>: The Armored Titan can harden its skin, which protects vulnerable areas and deflects military weapons.</li>
                           
                           <li class="margin3"> <b>Claws</b>: The Armored Titan can create claws on its hands and feet to scale walls. </li>
                           
                           <li class="margin3"> <b>Battering</b>: The Armored Titan can use its body to demolish walls by ramming into them. </li>
                           
                           <li class="margin3"> <b>Destructive potential</b>: The Armored Titan is especially effective after gaining momentum and speed.</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--7throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 eren">
                              
                    </div>
                    <div class="col-lg-12 eren2">
               <img src="eren.jpg" width="460px" height="790px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph eren3">
                       <p class="name">The Attack Titan</p>
                   <p class="ed">The "Attack Titan" is one of the nine special Titans, possessing the unique ability to see memories of past and future inheritors, allowing the user to glimpse into the past and future of their bloodline, essentially giving them foresight and a deeper understanding of their lineage; it is often associated with a fight for freedom across generations, with Eren Yeager being the most prominent wielder of this Titan power in the story.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="yeager">
                           <li class="margin3"> <b>Hand to Hand combat</b>: The attack titan has a great hand to hand combat that control by the user.</li>
                           
                           <li class="margin3 yeager2"> <b>Hardening</b>: Like the female titan, attack titan can turned its whole body into a hardening crystal that eren use to plugged the inner and outer gate of wall maria.</li>
                           
                           <li class="margin3">Eren The attack titan, can see events that their future self will experience.</li>
                           
                           <li class="margin3">The user can also peer into the memories of future inheritors to some degree.</li>
                           
                           <li class="margin3">However, Eren Yeager can use the Founding Titan's ability even without being of royal blood. This happens when he touches Dina Fritz, a member of the royal family. With Ymir's help, Eren's Founding Titan could summon the Titans of previous Shifters to fight on his behalf. </li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--8throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 cart">
                              
                    </div>
                    <div class="col-lg-12 cart2">
               <img src="cart.jpg" width="460px" height="800px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph cart3">
                       <p class="name">The Cart Titan</p>
                   <p class="pd">Around the year 843, Pieck Finger was chosen to inherit the power of the Cart Titan. She would later make use of her Titan form during a war between Marley and an enemy nation, using her Cart Titan to drop off Bertolt Hoover at a site for transformation. </p>
               
                   <p class="pd2">The Cart Titan is quadrupedal and acts like a biological cart. It's often used to support other Titans and soldiers during battles.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul">
                           <li class="margin3"> <b>Stamina</b>: The character can maintain a Titan form for extended periods and can rapidly and repeatedly transform without the need for rest.</li>
                           
                           <li class="margin3"> <b>Speed</b>: Cart titan possesses incredible speed giving her the ability to move fast. </li>
                        
                           <li class="margin3"> <b>Carrying</b>: Can carry heavy armaments, including weapons, people, and supplies.</li>
                           
                           <li class="margin3"> <b>Biting</b>: Cart titan Has superior biting strength but not strong as jaw titan.</li>
                           
                           <li class="margin3"> <b>The Cart Titan's disadvantages</b>: Titans have lower defenses, slower regeneration capacity, and their inheritors may forget normal walking once they return to their human form from a very long time of titan form.</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--9throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 Colossal">
                              
                    </div>
                    <div class="col-lg-12 Colossal2">
               <img src="ct.jpg" width="460px" height="805px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph Colossal3">
                       <p class="name">The Colossal Titan</p>
                   <p class="cd">The Colossus Titan was one of the Nine Titans and the early main antagonist of the Attack on Titan series. It was notable for its incredible size and its ability to control both the steam emitted by its Titan body and the amount of energy released during its transformations.</p>
               
                   <p class="cd2">Colossal Titan is the tallest of all nine with a massive 60feet height. It was also the first Titans introduced in the anime. Bertholdt Hoover possessed Colossal Titan before Armin Arlet ate him, and became the new possessor. </p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul">
                           <li class="margin3"> <b>Steam emission</b>: The Colossal Titan can generate massive steam, which can burn and repel nearby individuals, and can also create a smoke screen. </li>
                           
                           <li class="margin3"> <b>Evaporation</b>: The Colossal Titan's ability to evaporate its entire body in seconds makes it susceptible to falling from great heights.</li>
                           
                           <li class="margin3"> <b>Explosive transformation</b>: The Colossal Titan's explosive transformation leads to massive destruction and a mushroom cloud, causing the destruction of entire cities. </li>
                           
                           <li class="margin3"> <b>Physical strength</b>: The Colossal Titan's immense size gives it unparalleled physical strength.</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>

                <!--10throw-->
                <div class="row" style="background-color: black;">
                    <div class="col-lg-12 female">
                              
                    </div>
                    <div class="col-lg-12 female2">
               <img src="ft.jpg" width="460px" height="795px">
                  
                   </div>
               
                   <div class="col-lg-5 paragraph female3">
                       <p class="name">The Female Titan</p>
                   <p class="fd">The Female Titan, Annie Leonhart, was a Nine Titan with the ability to mimic other Titans' attributes, harden skin, and attract Pure Titans through screams.</p>
                   <br></br> 
                   <p class="abilities">Abilities: </p>
                   <ul class="ul"> 
                           <li class="margin3"> <b>Agility and speed</b>: The Female Titan is agile and fast, making her a versatile combatant.</li>
                           
                           <li class="margin3"> <b>Hardening</b>: Ability to harden its skin enhances melee attacks and creates a crystal case, enabling it to deal powerful blows. </li>
                           
                           <li class="margin3"> <b>Mimicking other Titans</b>: This Titan can mimic the powers of other Titans by eating their flesh.</li>
                           
                           <li class="margin3"> <b>Screaming</b>: The Female Titan can scream to attract nearby Titans, but it can't control them.</li>
                           
                           <li class="margin3"> <b>Crystal cocoon</b>: The Female Titan can create a crystal cocoon around the user to prevent being killed and only the jaw titan and the power of founding titan can remove it.</li>
                           
                           <li class="margin3"> <b>Endurance</b>: The Female Titan's endurance and martial arts training allow it to overpower larger enemies.</li>

                           <li class="margin3"> <b>Unique mouth shape</b>: The Female Titan has a unique mouth shape with holes that ripped open when it swallowed.</li>
                        
                       </ul>
               
                           
                           </div>
                        </div>
    </body>
</html>
