<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>

  
* {
    margin: 0;
    padding: 0;
  }
  
  *::before
  *::after {
    box-sizing: inherit;
  }
  
  html {
    box-sizing: border-box;
    font-size: 62.5%;
    scroll-behavior: smooth;
  }
 
  .logo-image{
    width: 70px;
    height: 50px;
    border-radius: 100%;
    overflow: visible;
    margin-top: -20px;
}

  @media (max-width: 75em) {
    html {
      font-size: 60%;
    }
  }
  @media (max-width: 61.25em) {
    html {
      font-size: 58%;
    }
  }
  @media (max-width: 28.75em) {
    html {
      font-size: 55%;
    }
  }
 
  body {
    font-family: 'serif', sans-serif;
    font-size: 1.8em;
    font-weight: 400;
    line-height: 1.4;
    color: rgb(249, 247, 255);
  }
  
  h1,
  h2 {
    font-family: 'arial', serif;
    font-weight: 500;
    text-align: center;
  }
  p2 {font-family: 'arial', serif;
    display: flex;
    font-size: 2.7rem ;
    color: rgb(255, 255, 255);
    margin-top: auto;
    margin-bottom: -8rem;
    margin-left: auto;
    margin-right: 22rem;
    height: 100vh;
    width: 100%;
    text-align: justify;
    background-color:rgb(192, 0, 0);
     }

    p3 {font-family: 'arial', serif;
    display: flex;
    font-size: 2.7rem ;
    color: rgb(7, 7, 7);
    margin-top: auto;
    margin-bottom: -8rem;
    margin-left: auto;
    margin-right: 22rem;
    height: 100vh;
    width: 100%;
    text-align: justify;
    background-color:rgb(255, 255, 255);
        }
        
  h1 {
    font-size: 6rem;
  }
  
  h2,p2,p3,p4,p5 {
    font-size: 4rem;
  }
 
  p6{ font-family: 'arial', serif;
    font-size:2.2rem;
    color: black;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: auto;
    margin-right: 24rem;
    text-align: justify;
  }
  p9{ font-family: 'arial', serif;
    display: flex;
    font-size: 2.7rem ;
    color: black;
    margin-top: auto;
    margin-bottom: -8rem;
    margin-left: auto;
    margin-right: 22rem;
    height: 100vh;
    width: 90vw;
    text-align: justify;
  }

  p7{ font-family: 'arial', serif;
    font-size:3rem;
    color: black;
    margin-top: auto;
    margin-bottom: 50%;
    margin-left: 1rem;
    margin-right: auto;
    text-align: justify;
    width: 90vw;
    height: 100vh;
    flex-direction: column;
    justify-content: center;
  }

  ul {
    list-style: none;
  }
  
  a {
    text-decoration: none;
    color:black;
  }
  
  img {
    
    display: block;
    width: 100%;
  }
  
  .nav {
    display: flex;
    justify-content: left;
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    background: rgb(248, 248, 248);
    box-shadow: 0 2px 0 black;
    z-index: 10;
  }

  .nav-list {
    display: flex;
    margin-right: 2rem;
    margin: 0 2rem;
  }
  
    .nav {
      justify-content: left;
    }

  .nav-list a {
    display: block;
    font-size: 2rem;
    padding: 2rem;
  }
  
  .nav-list a:hover {
    background:rgb(128, 149, 141);
  }
  
  .welcome-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 100vh;
    background-color:rgb(192, 0, 0);
    background-image: linear-gradient(62deg, rgb(143, 24, 24) 100%);
  }
  
  .welcome-section > p {
    font-size: 3rem;
    font-weight: 200;
    font-style: italic;
  }
  
  .projects-section {
    text-align: left;
    padding: 10rem 2rem;
  }
  
  .projects-section-header {
    max-width: 540px;
    margin-top: 2rem;
    margin-bottom: auto;
    margin-right: auto;
    margin-left: auto;
  }

  .projects-section-header4 {
    max-width: 540px;
    margin-top: 4rem;
    margin-bottom: 8rem;
    margin-right: auto;
    margin-left: auto;
  }
  
  @media (max-width: 28.75em) {
    .projects-section-header, .projects-section-header4,.projects-section-header5 {
      font-size: 3rem;
    }
  }
  
  .projects-section-header1{
    text-align: right;
    color: black;
    max-width: 540px;
    margin-top: auto;
    margin-left:  auto;
    margin-right: 6%;
    margin-bottom: auto;
  }
  .projects-section-header5 {
    text-align: right;
    color: black;
    max-width: 540px;
    margin-top: 3rem;
    margin-left:  5rem;
    margin-right: auto;
    margin-bottom: 6rem;
    text-align: justify;
  }
  
  @media (max-width: 28.75em) {
    .projects-section-header1 {
      font-size: 4rem;
    }
  }

  div.projects-section-header1 {
    height: 10em;
    position: relative }  

    div.projects-section-header1 p3 {
      margin: 0;
      position: absolute;               
      top: 50%;                         
      transform: translate(0, -50%) }   

      .projects-section-header2 {
        text-align: left;
        color: rgb(255, 255, 255);
        max-width: 540px;
        margin-top: auto;
        margin-right: auto;
        margin-left: 6%;
        margin-bottom: auto;
      }
      
      @media (max-width: 28.75em) {
        .projects-section-header2 {
          font-size: 4rem;
        }
      }
    
      div.projects-section-header2 {
        height: 10em;
        position: relative }  
    
        div.projects-section-header2 p3 {
          margin: 0;
          position: absolute;               
          top: 50%;                         
          transform: translate(0, -50%) }  
  
     
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
    grid-gap: 6rem;
    width: 100%;
    max-width: 1280px;
    margin-top: -5% ;
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 6rem;
  }

  .projects-grid1 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 10rem;
    width: 30%;
    height:30%;
    display: block;
    margin-top: 4%;
    margin-left:  auto;
    margin-right: 6%;
    margin-bottom: auto;
  }

  .projects-grid2 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 10rem;
    width: 30%;
    height:30%;
    display: block;
    margin-top: 4%;
    margin-left:  6%;
    margin-right: auto;
    margin-bottom: auto;
  }
  .projects-grid6 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 10rem;
    width: 44%;
    height:44%;
    display: block;
    margin-top: 3%;
    margin-left:  6%;
    margin-right: auto;
    margin-bottom: auto;
  }
  
  
  @media (max-width: 30.625em) {
    .projects-section {
      padding: 6rem 1rem;
    }
  
    .projects-grid {
      grid-template-columns: 1fr;
    }
    .projects-grid1 {
      grid-template-columns: 1fr;
    }
  }
  
  .row {
    display: flex;
    margin-top: 5rem;
    margin-bottom: auto;
    margin-right: auto;
    margin-left: auto;
  }
  
  .column {
    flex: 33.33%;
    padding: 5px;
    text-align: left;
  }
 

  .caption {
    display: block;
}

  .project {
    background:white;
    box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
    border-radius: 2px;
  }
  
  .code {
    color: gray;
    transition: color 0.3s ease-out;
  }
  
  .project:hover .code {
    color: #ff7f50;
  }
  
  .project-image {
    height: calc(100% - 6.8rem);
    width: 100%;
    object-fit: cover;
  }
  
  .project-title {
    font-size: 2rem;
    padding: 2rem 0.5rem;
  }

  .contact-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 100%;
    height: 80vh;
    padding: 0 2rem;
    background: rgb(192, 0, 0);;
  }
  
  .contact-section-header > h2 {
    font-size: 2rem;
  }
  
  @media (max-width: 28.75em) {
    .contact-section-header > h2 {
      font-size: 2em;
    }
  }
  
  .contact-section-header > p {
    font-style: italic;
  }
  
  .contact-links {
    display: flex;
    justify-content: center;
    width: 100%;
    max-width: 980px;
    margin-top: 4rem;
    flex-wrap: wrap;
  }
  
  .contact-details {
    font-size: 2.4rem;
    text-shadow: 2px 2px 1px black;
    transition: transform 0.3s ease-out;
  }
  
  .contact-details:hover {
    transform: translateY(8px);
  }
  
  footer {
    font-weight: 300;
    display: flex;
    justify-content: space-evenly;
    padding: 2rem;
    background:white;
    border-top: 4px solid var(black);
  }
  
  footer > p {
    margin: 2rem;
  }
  
  @media (max-width: 30em) {
    footer {
      flex-direction: column;
      text-align: center;
    }
  }
        </style>
    </head>
</html>

<nav id="navbar" class="nav">
  <ul class="nav-list">
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Work</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a class="navbar-brand" href="/">
        <div class="logo-image">
              <img src="https://scontent.fpnq6-1.fna.fbcdn.net/v/t1.0-9/103098380_146256010327894_5951680097354366272_n.jpg?_nc_cat=101&_nc_sid=09cbfe&_nc_ohc=im_PK8lbHdEAX-Q2spU&_nc_ht=scontent.fpnq6-1.fna&oh=682736fa2d45a31ab959f1176769ccde&oe=5F22B89A" class="center">
        </div>
  </a></li>
  </ul>
</nav>

<section id="welcome-section" class="welcome-section">
  <h1>EMPEZAR GROUP</h1>
</section>

<section id="projects" class="projects-section">
    <div class="projects-grid">
        <img
          src="https://wavesight.com/wp-content/uploads/2016/03/portindia-1600x800.jpg " width="100"
        />
   </div>

  <h2 class="projects-section-header"><a><b>Delivering Excellence in Logistics Solutions</b></a></h2><br><br><br><br>

  <h2 class="projects-section-header1"></h2>
  <p2 > <div class="projects-grid1" > <img src="https://github.com/aavichari24/hello1/blob/master/00.JPG?raw=true" /></div>
    <div class="projects-section-header2"  > The only integrated Logistics Solution Provider at Mundra </div>
  </p2>

  <h2 class="projects-section-header1"></h2>
  <p3 > <div class="projects-grid2" style="float:left"><img src="https://github.com/aavichari24/hello1/blob/master/12.JPG?raw=true "/></div>
    <div class="projects-section-header1" style="float:right"> The largest SEZ based warehouse in Mundra SEZ</div>
  </p3>

  <h2 class="projects-section-header2"></h2>
  <p2 > <div class="projects-grid1" > <img src="https://github.com/aavichari24/hello1/blob/master/33.JPG?raw=true" /> </div>
    <div class="projects-section-header2" >  The most commercially viable &nbsp;&nbsp;&nbsp;&nbsp;CFS in Mundra SEZ</div>
  </p2>

  <h2 class="projects-section-header1"></h2>
  <p3 > <div class="projects-grid2" style="float:left"><img src=" https://github.com/aavichari24/hello1/blob/master/yy.JPG?raw=true" /></div>
    <div class="projects-section-header1" style="float:right"> The largest transportation fleet within mundra SEZ</div>
  </p3>
  
  <h2 class="projects-section-header2"></h2>
  <p2 > <div class="projects-grid1" > <img src="https://github.com/aavichari24/hello1/blob/master/yz.JPG?raw=true " /> </div>
    <div class="projects-section-header2" > The Largest Empty Container Yard </div>
  </p2>

  <h2 class="projects-section-header1"></h2>
  <p3 > <div class="projects-grid2" style="float:left"><img src="https://github.com/aavichari24/hello1/blob/master/xy1.JPG?raw=true " /></div>
    <div class="projects-section-header1" style="float:right"> Pathbreaking Technology Solutions </div>
  </p3>

  <h2 class="projects-section-header2"></h2>
  <p2 > <div class="projects-grid1" > <img src="https://github.com/aavichari24/hello1/blob/master/xy2.JPG?raw=true" /> </div>
    <div class="projects-section-header2" > One of the Most Reputed Custom House Brokers </div>
  </p2>

  <h2 class="projects-section-header1"></h2>
  <p3 > <div class="projects-grid1" style="float:left"><img src="https://github.com/aavichari24/hello1/blob/master/xy3.JPG?raw=true" /></div>
    <div class="projects-section-header1" style="float:right"> Service and Compilance  </div>
  </p3>

  <h2 class="projects-section-header"><a><b>  Mundra, the right port for many reasons</b></a></h2>
  <p5 > <div class="row">
    <div class="column">
      <img src="https://github.com/aavichari24/hello1/blob/master/1xy.JPG?raw=true" alt="Snow" style="width:89%">
      </div> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <div class="column">
      <img src="https://github.com/aavichari24/hello1/blob/master/Screenshot_2020-07-10-00-52-07-615.jpeg?raw=true" alt="Forest" style="width:60%" > <p6>Mundra is a
         natural gateway to the cargo hubs in northern and western india-bringing down logistics costs</p6> </div>
    <div class="column">
      <img src="https://github.com/aavichari24/hello1/blob/master/Screenshot_2020-07-10-00-52-32-343.jpeg?raw=true" alt="Mountains" style="width:60%"><p6>6 Railway lines for handling 
        container trains & 10 Railway lines for bulk cargo offer unmatched connectivity. </p6></div>
      <div class="column">
    <img src="https://github.com/aavichari24/hello1/blob/master/Screenshot_2020-07-10-00-53-11-328.jpeg?raw=true" alt="Mountains" style="width:60%"><p6>A Deep Draft,
          all wether report & india's largest commercial port.Mundra can berth the largest post panamax vessel and can handle four million TEU's </p6></div>
  </div>
  </p5>

 <h2 class="projects-section-header4"><a><b> Brief History </b></a></h2>
  <p7> <div class="projects-section-header"></div>The Empezar Group was incorporated in 2008 and since then has spread its wings into various lines of the logistics industry - Port 
    Transportation, Empty Container Yard, Warehousing, Customs Cargo Clearance, Freight Forwarding, Technology Solutions and Total Logistics.<br>
    Empezar has a vision to become a leading integrated logistics solutions provider, on the backbone of a powerful technological platform to deliver customer delight.
    In a short span, Empezar has built robust relationships with Shipping Lines and Clients alike. We have operations in Mundra & Hazira; and offices at Gandhidham, Mumbai and Delhi.</div> </p7>

    <h2 class="projects-section-header" > <br><br><a><b> SEZ Warehousing </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://www.cratexgroup.com/wp-content/uploads/2015/10/container-yard-624x416.jpg" /></div>
      <div class="projects-section-header5" style="float:right">The concept of warehousing of goods in a duty-free area (SEZ) has emerged as a key factor in logistics and global supply
         chain system servicing.<br>Mundra has rapidly emerged as a leading international trading hub, owing to superior infrastructure and its strategic location – cargo consolidation
          and distribution to the Indian sub continent, South East Asia, Middle East, CIS and Africa.  </div>
    </p9>

    <h2 class="projects-section-header" > <br><br><a><b> Container Freight Station </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://www.envisionesl.com/wp-content/uploads/2017/08/container-freight-station.jpg" /></div>
      <div class="projects-section-header5" style="float:right">An approved Container Freight Station and a Bonded Warehouse, along with our other services help us provide Total Logistics
         Solutions to clients.<br>Today we are partnering with some of the largest players across industries Heavy Machinery, Cosmetics, Paper, Bitumen, Oil, Timber to name a few. Our systems
          driven approach ensures the highest level of services to ensure customer delight.  </div>
    </p9>

    <h2 class="projects-section-header" > <br><br><a><b> Transportation </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://miro.medium.com/max/700/1*S47EwOoB8VvE82Xc3HxlBg.jpeg" /></div>
      <div class="projects-section-header5" style="float:right">Our company handles the local transportation of container and body trucks for export and import movement of our esteemed clients.
         We are able to offer this kind of service to all parts of India through our network of esteemed agents and sub-agents<br>Our dedicated team of supervisors and trained mechanics ensure a
         high uptime of our fleet.  </div>
    </p9>

    <h2 class="projects-section-header" > <br><br><a><b> Custom house Broker </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://4.imimg.com/data4/AA/AA/GLADMIN-/img_external-gallery-services1-500x500.jpg" /></div>
      <div class="projects-section-header5" style="float:right">We operate as Licensed Custom House Agents at all western ports of India. We are also present at various ICDs and CFS’ situated at all major locations.
        We are capable of handling cargo consisting liquid, bulk, break bulk, project cargo & containerized cargo.<br>We have customs-approved trained & experienced staff to deal with customs port related matters and to provide excellent services.</div>
    </p9>

    <h2 class="projects-section-header" > <br><br><a><b> Empty Container Yard </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://moderngroup.com.pk/wp-content/uploads/2017/03/EQ.jpg" /></div>
      <div class="projects-section-header5" style="float:right">The largest and most efficiently run Empty Container Yard in Mundra SEZ. A one of its kind technological interface ensures transparency of rates, on time performance and adherence to the highest quality standards.<br>With world class infrastructure, a large trained workforce and systems which support Location tracking, Barcoding and Real Times Updates for customers – Empezar is the preferred partner for some of the largest shipping lines in the country.</div>
    </p9>

    <h2 class="projects-section-header" > <br><br><a><b> Technology Solutions </b></a></h2><br>
    <p9 > <div class="projects-grid6"><img src="https://informationcube.files.wordpress.com/2014/10/small-business-technology-solutions.jpg?w=700&h=466" /></div>
      <div class="projects-section-header5" style="float:right">Empezar has a large in-house technology team that has built a reputation for creating pathbreaking software solutions for the logistics Industry. Our solutions have led up to a 50% increase in efficiencies for some clients.<br>We are working with global shipping lines and reputed logistics players to build systems that dramatically change the way they do business.</div>
    </p9>



  <section id="contact" class="contact-section">
    <div class="contact-section-header">
      <h2> Built on twin pillars of 'Transperancy' & 'Trust'</h2>
      <p></p>
    </div>
    <div class="contact-links">
      <a href="nnoob503@gmail.com" class="btn contact-details">
      <i class="fas fa-at"></i> Send a mail</a>  <br>&nbsp;&nbsp;&nbsp;&nbsp;
      <a href="tel:9637243572" class="btn contact-details"
      ><i class="fas fa-mobile-alt"></i> Call me</a>&nbsp;&nbsp;&nbsp;&nbsp;
      <a
      id="profile-link"
      href="https://github.com/aavichari24"
      target="_blank"
      class="btn contact-details"
      ><i class="fab fa-github"></i> GitHub</a>
  </div>
</section>

<footer>
  <p> <a>**This is just a fake portfolio.</a>
    
  </p>
  <p>
    <a href="https://www.wikipedia.org" target="_blank"
      >wikipedia </a>
  </p>
</footer>
</html>
