# Project-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet" type="text/css">
    <link href="media.style.css" type="text/css" rel="stylesheet">
     <link rel="stylesheet" type="text/css" href="https://use.fontawesome.com/releases/v5.0.7/css/all.css"> 
    <link href="https://fonts.googleapis.com/css?family=Raleway:100,200,300,regular,500,600,700,800,900,100italic,200italic,300italic,italic,500italic,600italic,700italic,800italic,900italic" rel="stylesheet"/>
    <script src="https://kit.fontawesome.com/a1153c9a51.js" crossorigin="anonymous"></script>
    <title>Booki</title>
</head>
<body>
 <header>
  <a href="Indexcopy.html" class="logo"><img src="images/logo/Booki@3x.png" alt="logo" class="logo"/></a>

     <!--NAVIGATION-->
     <nav class="nav_main">
         <a href="#accommodations" class="nav_link">Accommodations</a>
         <a href="#active" class="nav_link">Activities</a>  
    </nav>


        <div class="slogan"><h3>Find a place for your dream vacation</h3></div>
        <div class="sub_slogan"><p>Downtown or in Nature</p></div>
           
             <!--Search Bar-->
         <div class="search">
           <i class="fas fa-map-marker-alt"></i>
           <input type="search__text" placeholder="Marseilles, France">
          <button class="search__button"><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a><a href="#"><span class="search-btn-txt">Search</span></a></button>
         </div>
        

        <!--Filter Bar-->
        <section class="filter">
            <h2>Filters</h2>
            
            <div class="filter__wrap">
              <!--   button tags are flexbox  -->
              <button class="filter__btn" type="button">
               <i class="fa-solid fa-money-bill-wave filter__icon"></i>
               <a href="#"><span>Low Cost</span></a>
              </button>
             
             
             
              <button class="filter__btn" type="button">
               <i class="fa-solid fa-child filter__icon filter__icon"></i>
               <a href="#"><span>Family-Friendly</span></a>
              </button>
              
        
            
              <button class="filter__btn" type="button">
               <i class="fas fa-heart filter__icon"></i>
               <a href="#"><span>Romantic</span></a>
              </button>
              

              
              <button class="filter__btn" type="button">
               <i class="fa-solid fa-dog filter__icon"></i>        
               <a href="#"><span>Pets Allowed</span></a>
              </button>
              
            </div>

          </section>
        </header>

        <!--INFORMATION SECTION-->

        <section class="info">
        <a href="#"><i class="fas fa-info"></i></a>
          <h6 class="info__text">More than 500 accommodations are available in this city.</h6>
        </section>

          <main>

  
          
          <section class="accom-most-container">

            <!--ACCOMMADATION SECTION-->
            <a id="accommodations"></a>
            <div class="accom-container">
              <div class="accom__container__title"><strong>Accommodations in Marseille</strong></div>
              <div class="accom__container__wrap">
                <!--ACCOM WRAP-->
                <div class="accom__card" id="accom_1">
                  <a href="#"><img src="images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="Auberge la Cannebiere"/>
                  
                    <div class="accom__card__text">
                      <h3>Auberge la Cannebiere</h3>  
                      <p>Night starting at <span class="cost">25&#8364;</span></p>
                      <div class="rating">
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star unchecked"></span>  
                     </div>
                    </div>
                    </a>
                 </div>
                <!--Second Accom Card-->
               <div class="accom__card" id="accom_2">
                <a href="#"><img src="images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="Hotel Du Port"/>

                  <div class="accom__card__text">
                    <h3>Hôtel du port</h3>
                    <p>Night starting at <span class="cost">52&#8364;</span></p>
                  <div class="rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                  </div>
                  </div>
                    </a>
               </div>
              <!--THIRD ACCOM CARD-->
              <div class="accom__card" id="accom_3">
                <a href="#"><img src="images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="Les Mouettes Hotel"/>
      
                  <div class="accom__card__text">
                    <h3>Les mouettes Hôtel</h3> 
                    <p>Night starting at <span class="cost">76&#8364;</span></p>
                    <div class="rating">
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                       <span class="fa fa-star checked"></span>
                       <span class="fa fa-star unchecked"></span>
                       </div>
                    </div>
                     </a>
                  </div>
                 <!--FOURTH ACCOM CARD-->
                <div class="accom__card" id="accom_4">
                  <a href="#"><img id="la-mer" src="images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="Hotel de la mar"/>
                  
                    <div class="accom__card__text">
                      <h3>Hôtel de la mer</h3>
                      <p>Night starting at <span class="cost">46&#8364;</span></p>
                      <div class="rating">
                        <span class="fa fa-star checked"></span>
                        <span class="fa fa-star checked"></span>
                        <span class="fa fa-star checked"></span>
                        <span class="fa fa-star unchecked"></span>
                        <span class="fa fa-star unchecked"></span>
                        </div>
                    </div>
                    </a>
                  </div>
                <!--FIFTH ACCOM CARD-->
                <div class="accom__card" id="accom_5">
                  <a href="#">
                    <img src="images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="Auberge Le Panier"/>

                  <div class="accom__card__text">
                    <h3>Auberge Le Panier</h3> 
                    <p>Night starting at <span class="cost">23&#8364;</span></p>
                  <div class="rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star unchecked"></span>
                    </div>
                  </div>
                  </a>
                </div>
              <!--SIXTH ACCOM CARD-->
              <div class="accom__card" id="accom_6">
                <a href="#">
                  <img id="amina" src="images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg"  alt="Hôtel chez Amina"/>
                 
                  <div class="accom__card__text">
                  <h3>Hôtel chez Amina</h3>  
                  <p>Night starting at <span class="cost">96&#8364;</span></p>
                  <div class="rating">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  </div>
                 </div>
                </a>
              </div>
              <!--END OF ACCOM CARD WRAP-->
              </div>
              <button class="show_more">Show more</button>
           </div>
            
          
              
          <!--MOST POPULAR-->      
    
          <div class="most-pop">
            <div class="most-pop__heading">
              <h2>Most Popular</h2>
              <a href="#"><i class="fas fa-chart-line"></i></a>
             </div>
  
             <div class="most-card-wrap">
              
              <div class="pop__card" id="pop_card_1">
                <a href="#"></a>
                <img class="most__image" src="images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="Morning sun Hotel"/>
  
                <div class="most-text-wrap">
                  <h3>Morning Sun Hotel</h3>
                  <p>Night starting at <span class="cost">128&#8364;</span></p>
                  <div class="rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    </div>
                  </div>
                </div>
              
                <div class="pop__card" id="pop_card_2">
                  <a href="#"></a>
                  <img class="most__image" src="images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="Au coeur de l'eau Bed and Breakfast"/>
  
                  <div class="card_most_text_wrap">
                    <h3 id="au-coer">Au coeur de l'eau Bed and Breakfast</h3>
                    <p>Night starting at <span class="cost">71&#8364;</span></p>
                    <div class="rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star unchecked"></span>
                    </div>
                  </div>
               </div>
   
  
               <div class="pop__card" id="pop_card_3">
                <a href="#"></a>
                <img class="most__image" src="images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="Tout bleu et Blanc Hotel"/>
  
                <div class="card_most_text_wrap">
                  <h3>Tout bleu et Blanc Hotel</h3>
                  <p>Night starting at <span class="cost">68&#8364;</span></p>
                  <div class="rating">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star unchecked"></span>
                </div>
                </div>
                
                </div>
              
            
          </div>

          
          </div>

           
      </section>
     
      <!--ACTIVITIES-->
      <a id="active"></a>
    <section class="act">
    <p class="activities__title"><strong>Activities in Marseille</strong></p>
       <div class="activities">
       

         <a href="#" class="act__card" id="act_card_1"><img class="act_tall" id="img-1" src="images/activites/4_small/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="Old Port"/>
          <h3 class="card__title">Old Port</h3>
          </a>
          
          <div class="act__cards__wrap">
          <a href="#" class="act__card" id="act_card_2"><img class="act_small" id="img-2" src="images/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="Pomegues Fort"/>
            <h3 class="card__title">Pomegues fort</h3>
          </a>
          <a href="#" class="act__card" id="act_card_3"><img class="act_small" id="img-3" src="images/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="Frioul Island"/>
            <h3 class="card__title">Frioul Island</h3>
            </a>
          </div>
        

           <a href="#" class="act__card" id="act_card_4"><img class="act_tall" id="img-4" src="images/activites/4_small/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="Calanques National Park"/>
            <h3 class="card__title">Calanques National Park</h3>
          </a>
          <div class="act__cards__wrap">
          <a href="#" class="act__card" id="act_card_5"><img class="act_small" id="img-5" src="images/activites/4_small/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="Notre-Dame-de-la-Garde"/>
            <h3 class="card__title">Notre-Dame-de-la-Garde</h3>
          </a>
          <a href="#" class="act__card" id="act_card_6"><img class="act_small" id="img-6" src="images/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="Longchamp Park"/>
            <h3 class="card__title">Longchamp Park</h3>
            </a>
          </div>
          </div>
      
    </section>
    
       
    </main>
    
    <!--FOOTER-->
   <footer>
     <section>
       <div class="footer">
         <div class="footer_list">
         <h2>About</h2>
         <ul>
           <li><a href="#" class="foot_link">Site Map</a></li>
          <li><a href="#" class="foot_link">General Terms and Conditions</a></li>
          <li><a href="#" class="foot_link">Date and Privacy</a></li>
          </ul> 
       </div>
       <div class="footer_list">
        <h2>Our Accommodations</h2>
        <ul>
         <li><a href="#" class="foot_link">Quality Assessment</a></li>
         <li><a href="#" class="foot_link">You have a hotel?</a></li>
         </ul>
      </div>
      <div class="footer_list">
        <h2>Assistance</h2>
        <ul>
        <li><a href="#" class="foot_link">Help Desk</a></li>
        <li><a href="#" class="foot_link">Contact Us</a></li>
        </ul>
      </div>
    </div>
     </section> 
     
 </footer>
 
    
</body>
</html>