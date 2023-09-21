<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body >

  
    <!-- navigation bar -->

  <header>


    <nav class="nav collapsible">
      <a class="nav__brand" href="#"><img src="images/logo.svg" alt=""></a>
      <svg class="icon icon--white nav__toggler">
        <use xlink:href="#src-7"></use>
    </svg>
    <ul class="list nav__list collapsible__content">
      <li class="nav__item"><a href="#">Hosting</a></li>
      <li class="nav__item"><a href="#">VPS</a></li>
      <li class="nav__item"><a href="#">Domain</a></li>
      <li class="nav__item"><a href="#">Pricing</a></li>
    </ul>
    </nav>

  
  </header>

    <!-- navigation bar ends -->

<!-- hero component -->

<section class="block block--dark block--skewed-left hero">
        
  <div class="container grid grid--1x2" data-aos="fade-right">
    <header class="block__header hero__content ">
      <h1 class="block__heading">Cloud Hosting for Pros</h1>
      <p class="hero__tagline">Deploy your websites in less than 60 seconds.</p>
      <a href="#" class="btn btn--accent btn--stretched">Get Started</a>
    </header>
    <picture data-aos="fade-up">
      <source type="image/webp" srcset="images/banner.webp 1x,images/banner@2x.webp 2x">
      <source type="image/png" srcset="images/banner.png 1x,images/banner@2x.png 2x">
      <img class="hero__image" src="images/banner.png" alt="">
    </picture>
  </div>
</section>

<!-- hero component ends -->

<!-- Domain block -->

<section class="block container block-domain" data-aos="fade-up">
  <header class="block__header">
    <h2>Starting at $9 per month</h2>
    <p>Lorem ipsum dolor, sit amet consectetur
       adipisicing elit. Temporibus, sit.</p>
  </header>
  <div class="input-group"> 
    <input type="text" class="input" placeholder="Enter domain name here">
    <button class="btn btn--accent">
        <!-- <svg class="icon icon--white">
            <use xlink:href="#src-9"></use>
        </svg> -->
        <img src="images/search.svg" class="icon icon--white">
    Search</button>
  </div>
  <ul class="list block-domain__prices">
    <li><span class="badge badge--secondary">.com $9</span></li>
    <li>.sg $10</li>
    <li>.space $11</li>
    <li>.info $14</li>
    <li>.net $10</li>
    <li>.xyz $10</li>
  </ul>
</section>


<!-- Domain block ends -->

<!-- plans block starts -->

<section class="block container block-plans" data-aos="fade-up">
  <div class="grid grid--1x3">
   
      <div class="plan">
          <div class="card card--secondary">
              <header class="card__header">
                  <h3 class="plan__name">Entry</h3>
                  <span class="plan__price">$14</span>
                  <span class="plan__billing-cycle">/month/</span>
                  <span class="badge badge--secondary badge--small">10% OFF</span>
                  <span class="plan__description">East start on the cloud</span>
  
              </header>
              <div class="card__body">
                <ul class="list list--tick">
                  <li class="list__item">Item 1</li>
                  <li class="list__item">Item 2</li>
                  <li class="list__item">Item 3</li>
                  <li class="list__item">Item 4</li>
              </ul>
              <button class="btn btn--outline btn--block">Buy Now</button>
              </div>
          </div>
      </div>
    
    
      <div class="plan plan--popular">
        <div class="card card--secondary">
          <header class="card__header">
            <h3 class="plan__name">Entry</h3>
            <span class="plan__price">$14</span>
            <span class="plan__billing-cycle">/month</span>
            <span class="badge badge--secondary badge--small">10% OFF</span>
            <span class="plan__description">Easy start on the class</span>
          </header>
          <div class="card__body">
            <ul class="list list--tick">
              <li class="list__item">Unlimited Websites</li>
              <li class="list__item">Unlimited Bandwidth</li>
              <li class="list__item">100GB SSD Storage</li>
              <li class="list__item">3 GB RAM</li>
          </ul>
          <button class="btn btn--outline btn--block">Buy Now</button>
          </div>
        </div>
      </div>
    
      
        <div class="plan">
            <div class="card card--secondary">
                <header class="card__header">
                    <h3 class="plan__name">Entry</h3>
                    <span class="plan__price">$14</span>
                    <span class="plan__billing-cycle">/month/</span>
                    <span class="badge badge--secondary badge--small">10% OFF</span>
                    <span class="plan__description">East start on the cloud</span>
  
                </header>
                <div class="card__body">
                  <ul class="list list--tick">
                    <li class="list__item">Item 1</li>
                    <li class="list__item">Item 2</li>
                    <li class="list__item">Item 3</li>
                    <li class="list__item">Item 4</li>
                </ul>
                <button class="btn btn--outline btn--block">Buy Now</button>
                </div>
            </div>
        </div>
        
  </div>
</section>


<!-- plans block ends -->


<!-- Features block starts -->

<section class="block container">
  <header class="block__header" data-aos="fade-up">
    <h2>Host on the Cloud to Keep Growing</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, vero?</p>
  </header>

  <article class="grid grid--1x2 feature">
    <div class="feature__content" data-aos="zoom-in-right">

      <span class="icon-container">
        <svg class="icon icon--primary">
            <use xlink:href="#src-4"></use>
        </svg>
    </span>

    <h3 class="feature__heading">Super Easy to Use</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ullam quidem deleniti distinctio, numquam animi ratione natus deserunt ducimus eveniet.</p>
    <a href="#" class="link-arrow">Learn More</a>
  </div>
  <picture data-aos="zoom-in-left">
    <source type="image/webp"
    srcset="images/easy.webp 1x,images/easy@2x.webp 2x">
    <source type="image/jpg"
    srcset="images/easy.jpg 1x,images/easy@2x.jpg 2x">
    <img class="feature__image" src="images/easy@2x.jpg" alt="">
  </picture>

  </article>

  <article class="grid grid--1x2 feature">
    <div class="feature__content" data-aos="zoom-in-left">

      <span class="icon-container">
        <svg class="icon icon--primary">
            <use xlink:href="#src-4"></use>
        </svg>
    </span>

    <h3 class="feature__heading">Simply Fast Websites</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ullam quidem deleniti distinctio, numquam animi ratione natus deserunt ducimus eveniet.</p>
    <a href="#" class="link-arrow">Learn More</a>
  </div>
  <picture data-aos="zoom-in-right">
    <source type="image/webp"
    srcset="images/fast.webp 1x,images/fast@2x.webp 2x">
    <source type="image/jpg"
    srcset="images/fast.jpg 1x,images/fast@2x.jpg 2x">
    <img class="feature__image" src="images/fast@2x.jpg" alt="">
  </picture>

  </article>



<article class="grid grid--1x2 feature">
  <div class="feature__content" data-aos="zoom-in-right">

    <span class="icon-container">
      <svg class="icon icon--primary">
          <use xlink:href="#src-4"></use>
      </svg>
  </span>

  <h3 class="feature__heading">WordPress Made Easy</h3>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ullam quidem deleniti distinctio, numquam animi ratione natus deserunt ducimus eveniet.</p>
  <a href="#" class="link-arrow">Learn More</a>
</div>
<picture data-aos="zoom-in-left">
  <source type="image/webp"
  srcset="images/wordpress.webp 1x,images/wordpress@2x.webp 2x">
  <source type="image/jpg"
  srcset="images/wordpress.jpg 1x,images/wordpress@2x.jpg 2x">
  <img class="feature__image" src="images/wordpress@2x.jpg" alt="..">
</picture>

</article>

<article class="grid grid--1x2 feature">
  <div class="feature__content" data-aos="zoom-in-left">

    <span class="icon-container">
      <svg class="icon icon--primary">
          <use xlink:href="#src-4"></use>
      </svg>
  </span>

  <h3 class="feature__heading">24x7 Customer Support</h3>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ullam quidem deleniti distinctio, numquam animi ratione natus deserunt ducimus eveniet.</p>
  <a href="#" class="link-arrow">Learn More</a>
</div>
<picture data-aos="zoom-in-right">
  <source type="image/webp"
  srcset="images/support.webp 1x,images/support@2x.webp 2x">
  <source type="image/jpg"
  srcset="images/support.jpg 1x,images/support@2x.jpg 2x">
  <img class="feature__image" src="images/support@2x.jpg" alt="..">
</picture>

</article>

</section>

<!-- Features block ends -->

<!-- Showcase starts -->

<section class="block block--dark block--skewed-right block-showcase">
  <header class="block__header">
    <h2>User-friendly Control Panel</h2>
  </header>
  <div class="container grid grid--1x2">
    <picture  class="block-showcase__image" data-aos="fade-right">
      <source type="image/webp" srcset="images/ipad.webp 1x,images/ipad@2x.webp 2x">   
      <source type="image/jpg" srcset="images/ipad.jpg 1x,images/ipad@2x.jpg 2x">
      <img src="images/ipad.png" alt="">
  </picture>
  <ul class="list" data-aos="fade-up">
    <li>
      <div class="media">
        <div class="media__image">
            <svg class="icon icon--primary">
                <use xlink:href="#src-2"></use>
            </svg>
        </div>
        <div class="media__body">
          <h3 class="media__title">Easy Start & Managed Updates</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni nihil quia, aliquam libero nemo nesciunt!</p>
        </div>
      </div> 
    </li>
    <li>
      <div class="media">
        <div class="media__image">
            <svg class="icon icon--primary">
                <use xlink:href="#src-5"></use>
            </svg>
        </div>
        <div class="media__body">
          <h3 class="media__title">Easy Start & Managed Updates</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni nihil quia, aliquam libero nemo nesciunt!</p>
        </div>
      </div>
    </li>
    <li>
      <div class="media">
        <div class="media__image">
            <svg class="icon icon--primary">
                <use xlink:href="#src-13"></use>
            </svg>
        </div>
        <div class="media__body">
          <h3 class="media__title">Easy Start & Managed Updates</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni nihil quia, aliquam libero nemo nesciunt!</p>
        </div>
      </div>
    </li>
  </ul>
  </div>
</section>

<!-- Showcase ends -->

<!-- Testimonial starts -->
<section class="block">
  <header class="block__header" data-aos="zoom-in">
    <h2>What our Customers are Saying?</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos voluptatem ullam deserunt maxime repudiandae. Temporibus ex ipsum iste porro libero?</p>

  </header>
  <div class="container">
    <div class="card testimonial" data-aos="fade-up">
      <div class="grid grid--1x2">
        <div class="testimonial__image">
          <img
           src="images/testimonial.jpg" 
           alt="A happy smiling customer">
           <span class="icon-container icon-container--accent">
            <svg class="icon icon--white icon--small">
                <use xlink:href="#src-8"></use>
            </svg>
           </span>
        </div>
        
        <blockquote class="quote">
          <p class="quote__text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Itaque consectetur soluta laudantium culpa vel impedit ut officiis numquam voluptatem laboriosam.</p>
          <footer>
            <div class="media">
              <div class="media__image">
                  <svg class="icon icon--primary quote__line">
                      <use xlink:href="#src-6"></use>
                  </svg>
              </div>
              <div class="media__body">
                <h3 class="media__title quote__author">John Ratna</h3>
                <p class="quote__organization">Microsoft</p>
              </div>
            </div> 
          </footer>
        </blockquote>
      </div>
    </div>
  </div>
</section>

<!-- Testimonail ends -->

<!-- Callout starts -->

<div class="callout callout--primary">
  <div class="grid grid--1x2">
    <div class="callout__content">
      <h2 class="callout__heading">Ready to Get Started</h2>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Alias labore illum saepe doloremque voluptates, neque dolorum expedita a sed sit ratione eligendi. Reprehenderit corporis soluta accusantium fugit. Atque, dolor magni.
        Facilis quisquam debitis, repellendus voluptatem nisi eveniet, nam officia laboriosam amet ipsa optio repellat corporis molestiae minima eligendi quos, recusandae eaque quibusdam repudiandae! Ipsam eveniet debitis voluptate consequuntur quasi voluptatum.
        Officiis assumenda pariatur veritatis provident consectetur cumque illo libero a repudiandae dignissimos quis ad laboriosam quidem voluptatibus, culpa ea eum voluptatem eos quam doloremque ipsam voluptates autem nulla! Eos, aliquam?
      </p>
    </div>
    <a href="#" class="btn btn--secondary btn--stretched">Get Started</a>
  </div>
</div>

<!-- Callout ends -->



<!-- Footer starts -->

    

<footer class="block block--dark footer">
  <div class="container grid footer__sections">

    <section class="collapsible collapsible--expanded footer__section">
      <header class="collapsible__header">
        <h2 class="collapsible__heading footer__heading">Products</h2>
       
          <svg class="icon icon--white collapsible__chevron collapsible__color">
              <use xlink:href="#src-1"></use>
          </svg>
        
      </header>
      <div class="collapsible__content">
        <ul class="list">
          <li><a href="">Website Hosting</a></li>
          <li><a href="">Free Automated Wordpress</a></li>
          <li><a href="">Migrations</a></li>
        </ul>  
      </div>
    </section>

    <section class="collapsible footer__section">
      <header class="collapsible__header">
        <h2 class="collapsible__heading footer__heading">company</h2>
       
          <svg class="icon icon--white collapsible__chevron collapsible__color">
              <use xlink:href="#src-1"></use>
          </svg>
        
      </header>
      <div class="collapsible__content">
        <ul class="list">
          <li><a href="">About</a></li>
          <li><a href="">Affiliates</a></li>
          <li><a href="">Blog</a></li>
        </ul> 
      </div>
    </section>

    <section class="collapsible footer__section">
      <header class="collapsible__header">
        <h2 class="collapsible__heading footer__heading">support</h2>
       
          <svg class="icon icon--white collapsible__chevron collapsible__color">
              <use xlink:href="#src-1"></use>
          </svg>
        
      </header>
      <div class="collapsible__content">
        <ul class="list">
          <li><a href="">Contact</a></li>
          <li><a href="">Knowledge Base</a></li>
          <li><a href="">FAQ</a></li>
        </ul>   
      </div>
    </section>

    <section class="collapsible footer__section">
      <header class="collapsible__header">
        <h2 class="collapsible__heading footer__heading">domains</h2>
       
          <svg class="icon icon--white collapsible__chevron collapsible__color">
              <use xlink:href="#src-1"></use>
          </svg>
        
      </header>
      <div class="collapsible__content">
        <ul class="list">
          <li><a href="">Domain Checker</a></li>
          <li><a href="">Domain Transfer</a></li>
          <li><a href="">Free Domain</a></li>
        </ul>   
      </div>
    </section>

    <section class="footer__brand">
      <img src="images/logo.svg" alt="">
      <p class="footer__copyright">Copyright 2023 John Ratna Kumar</p>
    </section>

  </div>
</footer>

<!-- Footer ends -->






    <!-- svg sprite linking -->
<div class="end">
    <svg xmlns="http://www.w3.org/2000/svg"><symbol viewBox="0 0 51 51" id="src-1"><defs><style>.cls-1 { fill: rgb(57, 57, 57); }.cls-2 { fill: rgb(255, 255, 255); }</style></defs><circle class="cls-1" cx="25.5" cy="25.5" r="25.5"/><rect class="cls-2" x="24.4" y="27.9" width="1.6" height="15.24" rx="0.8" transform="matrix(0.78, -0.63, 0.63, 0.78, -21.26, 15.39)"/><rect class="cls-2" x="33.3" y="27.9" width="1.6" height="15.24" rx="0.8" transform="translate(24 -21.9) rotate(37.3)"/></symbol><symbol viewBox="0 0 460.78906 501.656" id="src-2"><g><g><path d="M342.512,328h-200c-2.122,0-4.156,0.844-5.656,2.344l-96,96l11.312,11.312L145.824,344h187.888    c-1.664,9.496-6.888,24-23.2,24h-88v16h88c31.64,0,40-31.4,40-48C350.512,331.582,346.93,328,342.512,328z"/></g></g><g><g><path d="M444.168,274.344c-3.124-3.123-8.188-3.123-11.312,0l-72,72l11.312,11.312l65.712-65.712    c10.828,14.37,8.629,34.68-5.024,46.4L339.2,432H174.512c-2.122,0-4.156,0.844-5.656,2.344l-56,56l11.312,11.312L177.824,448    h164.688c2.122,0,4.156-0.844,5.656-2.344l96-96C473.96,319.864,457.192,287.368,444.168,274.344z"/></g></g><g><g><path d="M262.512,0c-83.947,0-152,68.053-152,152s68.053,152,152,152c83.909-0.093,151.907-68.091,152-152    C414.512,68.053,346.459,0,262.512,0z M262.512,288c-75.111,0-136-60.889-136-136s60.89-136,136-136    c75.076,0.084,135.916,60.924,136,136C398.512,227.111,337.623,288,262.512,288z"/></g></g><g><g><path d="M262.512,40c-61.856,0-112,50.144-112,112s50.145,112,112,112c61.828-0.066,111.934-50.172,112-112    C374.512,90.144,324.368,40,262.512,40z M270.512,247.666V224h-16v23.666c-46.637-3.848-83.817-41.028-87.666-87.666h23.666v-16    h-23.666c3.849-46.637,41.029-83.817,87.666-87.666V80h16V56.343c46.612,3.893,83.764,41.045,87.657,87.657h-23.657v16h23.666    C354.33,206.637,317.15,243.817,270.512,247.666z"/></g></g><g><g><path d="M284.18,162.33c1.494-3.129,2.333-6.631,2.333-10.33c0-10.449-6.68-19.334-16-22.629V96h-16v33.371    c-9.32,3.295-16,12.18-16,22.629c-0.001,13.255,10.745,24,23.999,24c3.711,0,7.225-0.843,10.362-2.347l23.977,23.977    l11.314-11.314L284.18,162.33z M262.512,160c-4.418,0-8-3.582-8-8c0-4.418,3.582-8,8-8c4.418,0,8,3.582,8,8    C270.512,156.418,266.93,160,262.512,160z"/></g></g><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/></symbol><symbol viewBox="0 0 61.99867 62" id="src-3"><g id="Computer-Engineer-Coding-Programing-Configulation"><path d="m13.293 14.293-3 3a1 1 0 0 0 0 1.414l3 3 1.414-1.414-2.293-2.293 2.293-2.293z"/><path d="m14.228 17h8.544v2h-8.544z" transform="matrix(.351 -.936 .936 .351 -4.85 29.002)"/><path d="m23.707 21.707 3-3a1 1 0 0 0 0-1.414l-3-3-1.414 1.414 2.293 2.293-2.293 2.293z"/><path d="m10 26h4v2h-4z"/><path d="m16 26h10v2h-10z"/><path d="m12 30h4v2h-4z"/><path d="m18 30h10v2h-10z"/><path d="m30 30h2v2h-2z"/><path d="m12 34h4v2h-4z"/><path d="m18 34h10v2h-10z"/><path d="m30 34h2v2h-2z"/><path d="m61.142 13.01-2.682-.383a10.86 10.86 0 0 0 -.679-1.639l1.625-2.166a1 1 0 0 0 -.093-1.307l-2.828-2.828a1 1 0 0 0 -1.306-.093l-2.167 1.624a10.9 10.9 0 0 0 -1.639-.678l-.383-2.682a1 1 0 0 0 -.99-.858h-4a1 1 0 0 0 -.99.858l-.383 2.682a10.855 10.855 0 0 0 -1.639.678l-2.167-1.624a1 1 0 0 0 -1.306.093l-2.828 2.828a1 1 0 0 0 -.093 1.307l1.625 2.166a10.86 10.86 0 0 0 -.679 1.639l-2.682.383a1 1 0 0 0 -.858.99v4a1 1 0 0 0 .858.99l2.682.383a10.86 10.86 0 0 0 .679 1.639l-1.625 2.166a1 1 0 0 0 .093 1.307l2.828 2.828a1 1 0 0 0 1.306.093l2.167-1.624a10.855 10.855 0 0 0 1.639.678l.383 2.682a1 1 0 0 0 .99.858h4a1 1 0 0 0 .99-.858l.383-2.682a10.9 10.9 0 0 0 1.639-.678l2.167 1.624a1 1 0 0 0 1.306-.093l2.828-2.828a1 1 0 0 0 .093-1.307l-1.625-2.166a10.86 10.86 0 0 0 .679-1.639l2.682-.383a1 1 0 0 0 .858-.99v-4a1 1 0 0 0 -.858-.99zm-1.142 4.123-2.463.352a1 1 0 0 0 -.827.742 8.923 8.923 0 0 1 -.977 2.357 1 1 0 0 0 .061 1.111l1.492 1.99-1.6 1.6-1.991-1.492a1 1 0 0 0 -1.11-.06 8.859 8.859 0 0 1 -2.356.975 1 1 0 0 0 -.744.828l-.352 2.464h-2.266l-.351-2.463a1 1 0 0 0 -.744-.828 8.859 8.859 0 0 1 -2.356-.975 1 1 0 0 0 -1.11.06l-1.991 1.492-1.6-1.6 1.492-1.99a1 1 0 0 0 .061-1.111 8.923 8.923 0 0 1 -.977-2.357 1 1 0 0 0 -.827-.742l-2.464-.353v-2.266l2.463-.352a1 1 0 0 0 .827-.742 8.923 8.923 0 0 1 .977-2.357 1 1 0 0 0 -.061-1.111l-1.492-1.99 1.6-1.6 1.991 1.492a1 1 0 0 0 1.11.06 8.859 8.859 0 0 1 2.356-.975 1 1 0 0 0 .744-.828l.352-2.464h2.266l.351 2.463a1 1 0 0 0 .744.828 8.859 8.859 0 0 1 2.356.975 1 1 0 0 0 1.11-.06l1.991-1.492 1.6 1.6-1.492 1.99a1 1 0 0 0 -.061 1.111 8.923 8.923 0 0 1 .977 2.357 1 1 0 0 0 .827.742l2.464.353z"/><path d="m48 10a6 6 0 1 0 6 6 6.006 6.006 0 0 0 -6-6zm0 10a4 4 0 1 1 4-4 4 4 0 0 1 -4 4z"/><path d="m52 40h-48v-25a3 3 0 0 1 3-3h28v-2h-28a5.006 5.006 0 0 0 -5 5v30a5.006 5.006 0 0 0 5 5h12.867l-.75 6h-2.117a2 2 0 0 0 -2 2v2a2 2 0 0 0 2 2h22a2 2 0 0 0 2-2v-2a2 2 0 0 0 -2-2h-2.117l-.75-6h12.867a5.006 5.006 0 0 0 5-5v-16h-2zm-13 20h-22v-2h22zm-4.133-4h-13.734l.75-6h12.234zm14.133-8h-42a3 3 0 0 1 -3-3v-3h48v3a3 3 0 0 1 -3 3z"/><path d="m46 44h2v2h-2z"/></g></symbol><symbol viewBox="0 0 496 495.9987" id="src-4"><g id="Out_line" data-name="Out line"><path d="m184 304h-112a8.00008 8.00008 0 0 0 -8 8v96a8.00008 8.00008 0 0 0 8 8h112a8.00008 8.00008 0 0 0 8-8v-96a8.00008 8.00008 0 0 0 -8-8zm-8 96h-96v-80h96z"/><path d="m96 336h32v16h-32z"/><path d="m128 368h32v16h-32z"/><path d="m380 64h-244v-40a7.99985 7.99985 0 0 0 -12.87793-6.34082l-104 80a8 8 0 0 0 0 12.68164l104 80a7.99985 7.99985 0 0 0 12.87793-6.34082v-40h216a64.07239 64.07239 0 0 1 64 64v144a63.89737 63.89737 0 0 1 -48 61.99341v-181.99341a8.00008 8.00008 0 0 0 -8-8h-336a8.00008 8.00008 0 0 0 -8 8v256a8.00008 8.00008 0 0 0 8 8h356a116.13134 116.13134 0 0 0 116-116v-200a116.13134 116.13134 0 0 0 -116-116zm-28 176v192h-112v-192zm-208 0v32h-32v-32zm-112 0h64v40a8.00008 8.00008 0 0 0 8 8h48a8.00008 8.00008 0 0 0 8-8v-40h64v192h-192zm448 140a100.113 100.113 0 0 1 -100 100h-348v-32h328a8.00008 8.00008 0 0 0 8-8v-9.605a79.86446 79.86446 0 0 0 64-78.395v-144a80.09041 80.09041 0 0 0 -80-80h-224a8.00008 8.00008 0 0 0 -8 8v31.75293l-82.87891-63.75293 82.87891-63.75293v31.75293a8.00008 8.00008 0 0 0 8 8h252a100.113 100.113 0 0 1 100 100z"/><path d="m320 400h16v16h-16z"/><path d="m288 400h16v16h-16z"/><path d="m256 400h16v16h-16z"/></g></symbol><symbol viewBox="0 0 512.004 512.00134" id="src-5"><g><g><path d="m504.5 480.837h-38.97v-240.347c0-4.142-3.357-7.5-7.5-7.5s-7.5 3.358-7.5 7.5v240.347h-49.648l-.002-318.357h49.65v43.01c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-50.51c0-4.142-3.357-7.5-7.5-7.5h-64.65c-4.143 0-7.5 3.358-7.5 7.5v43.012h-57.148c-4.143 0-7.5 3.358-7.5 7.5v43.008h-57.15c-4.143 0-7.5 3.358-7.5 7.5v43.008h-57.15c-4.143 0-7.5 3.358-7.5 7.5v43.008h-57.15c-4.143 0-7.5 3.358-7.5 7.5v38.964h-57.152c-4.143 0-7.5 3.358-7.5 7.5v20.89c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-13.39h49.65v69.857h-49.65v-21.467c0-4.142-3.357-7.5-7.5-7.5s-7.5 3.358-7.5 7.5v21.467h-31.467v-473.337c0-4.142-3.357-7.5-7.5-7.5s-7.5 3.358-7.5 7.5v38.967h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.65h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.65h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.65h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.651h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.65h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v49.65h-8.663c-4.143 0-7.5 3.358-7.5 7.5s3.357 7.5 7.5 7.5h8.663v38.967c0 4.142 3.357 7.5 7.5 7.5h38.967v8.663c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.66h49.65v8.66c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.663h49.65v8.663c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.663h49.65v8.663c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.663h49.65v8.663c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.663h49.65v8.663c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.66h49.65v8.66c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-8.663h38.97c4.143 0 7.5-3.358 7.5-7.5s-3.357-7.498-7.5-7.498zm-362.22-116.321h49.65v116.321h-49.65zm64.651-50.508h49.65v166.829h-49.65zm64.65-50.508h49.65v217.337h-49.65zm64.65-50.508h49.648v267.846h-49.648z"/><path d="m86.1 338.44c6.323 0 12.267-2.46 16.734-6.927l112.91-112.91c2.929-2.929 2.929-7.678 0-10.606-2.93-2.929-7.678-2.929-10.607 0l-112.909 112.909c-1.635 1.634-3.811 2.534-6.128 2.534-2.311 0-4.482-.9-6.116-2.533-1.64-1.64-2.543-3.817-2.543-6.13 0-2.311.901-4.484 2.543-6.123l263.521-263.52c2.145-2.145 2.786-5.371 1.625-8.173-1.16-2.803-3.896-4.63-6.929-4.63h-23.61c-4.775 0-8.66-3.889-8.66-8.67 0-4.775 3.885-8.66 8.66-8.66h62.63c4.775 0 8.66 3.885 8.66 8.66v62.63c0 4.781-3.885 8.67-8.66 8.67s-8.66-3.889-8.66-8.67v-23.611c0-3.034-1.827-5.768-4.63-6.929-2.804-1.161-6.027-.518-8.174 1.626l-125.88 125.88c-2.929 2.929-2.929 7.678 0 10.606 2.93 2.929 7.678 2.929 10.607 0l113.076-113.076v5.503c0 13.052 10.614 23.67 23.66 23.67s23.66-10.618 23.66-23.67v-62.63c0-13.046-10.614-23.66-23.66-23.66h-62.63c-13.046 0-23.66 10.614-23.66 23.66 0 13.052 10.614 23.67 23.66 23.67h5.504l-250.714 250.713c-4.475 4.469-6.939 10.412-6.939 16.733 0 6.32 2.463 12.264 6.937 16.737 4.466 4.467 10.405 6.927 16.722 6.927z"/></g></g></symbol><symbol viewBox="0 0 50 2" id="src-6">
  <path fill="#63c3ef" d="M0 0h50v2H0z"/>
</symbol><symbol viewBox="0 0 24 24" id="src-7"><g><path d="m21.5 24h-19c-1.379 0-2.5-1.122-2.5-2.5v-19c0-1.378 1.121-2.5 2.5-2.5h19c1.379 0 2.5 1.122 2.5 2.5v19c0 1.378-1.121 2.5-2.5 2.5zm-19-23c-.827 0-1.5.673-1.5 1.5v19c0 .827.673 1.5 1.5 1.5h19c.827 0 1.5-.673 1.5-1.5v-19c0-.827-.673-1.5-1.5-1.5z"/></g><g><path d="m16.5 8h-9c-.276 0-.5-.224-.5-.5s.224-.5.5-.5h9c.276 0 .5.224.5.5s-.224.5-.5.5z"/></g><g><path d="m16.5 12.5h-9c-.276 0-.5-.224-.5-.5s.224-.5.5-.5h9c.276 0 .5.224.5.5s-.224.5-.5.5z"/></g><g><path d="m16.5 17h-9c-.276 0-.5-.224-.5-.5s.224-.5.5-.5h9c.276 0 .5.224.5.5s-.224.5-.5.5z"/></g></symbol><symbol viewBox="0 0 508.04666 473.4747" id="src-8"><g><g><path d="M0.108,352.536c0,66.794,54.144,120.938,120.937,120.938c66.794,0,120.938-54.144,120.938-120.938    s-54.144-120.937-120.938-120.937c-13.727,0-26.867,2.393-39.168,6.61C109.093,82.118,230.814-18.543,117.979,64.303    C-7.138,156.17-0.026,348.84,0.114,352.371C0.114,352.426,0.108,352.475,0.108,352.536z"/><path d="M266.169,352.536c0,66.794,54.144,120.938,120.938,120.938s120.938-54.144,120.938-120.938S453.9,231.599,387.106,231.599    c-13.728,0-26.867,2.393-39.168,6.61C375.154,82.118,496.875-18.543,384.04,64.303C258.923,156.17,266.034,348.84,266.175,352.371    C266.175,352.426,266.169,352.475,266.169,352.536z"/></g></g><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/></symbol><symbol viewBox="0 0 21.883308 23.725098" id="src-9"><defs><style>.cls-1 { fill: rgb(236, 246, 252); }</style></defs><path class="cls-1" d="M11,17.9a8.7,8.7,0,0,0,.8,4.8,1,1,0,0,0,1.2.4.8.8,0,0,0,.4-1.2,8.3,8.3,0,0,1-.7-3.8,7.6,7.6,0,0,1,15.2,1.1A7.7,7.7,0,0,1,16.1,25a.8.8,0,0,0-1.2.2.9.9,0,0,0,.2,1.3A10,10,0,0,0,19.6,28a9.3,9.3,0,0,0,6.1-1.7l5.5,6.4a.9.9,0,0,0,.6.3.7.7,0,0,0,.7-.2.9.9,0,0,0,.1-1.2L27,25.2a8.9,8.9,0,0,0,2.6-5.8A9.3,9.3,0,1,0,11,17.9Z" transform="translate(-10.9 -9.3)"/></symbol><symbol viewBox="0 0 452.78906 485.656" id="src-10"><g><g><path d="M334.512,312h-200c-2.122,0-4.156,0.844-5.656,2.344l-96,96l11.312,11.312L137.824,328h187.888    c-1.664,9.496-6.888,24-23.2,24h-88v16h88c31.64,0,40-31.4,40-48C342.512,315.582,338.93,312,334.512,312z"/></g></g><g><g><path d="M436.168,258.344c-3.124-3.123-8.188-3.123-11.312,0l-72,72l11.312,11.312l65.712-65.712    c10.828,14.37,8.629,34.68-5.024,46.4L331.2,416H166.512c-2.122,0-4.156,0.844-5.656,2.344l-56,56l11.312,11.312L169.824,432    h164.688c2.122,0,4.156-0.844,5.656-2.344l96-96C465.96,303.864,449.192,271.368,436.168,258.344z"/></g></g><g><g><path d="M390.512,112H361.76c-2.193-7.348-5.139-14.45-8.792-21.192l20.344-20.344c3.123-3.124,3.123-8.188,0-11.312    L339.36,25.208c-3.124-3.123-8.188-3.123-11.312,0l-20.344,20.344c-6.741-3.658-13.843-6.607-21.192-8.8V8c0-4.418-3.582-8-8-8    h-48c-4.418,0-8,3.582-8,8v28.752c-7.349,2.193-14.451,5.142-21.192,8.8l-20.344-20.344c-3.124-3.123-8.188-3.123-11.312,0    l-33.952,33.944c-3.123,3.124-3.123,8.188,0,11.312l20.352,20.344c-3.655,6.742-6.604,13.844-8.8,21.192h-28.752    c-4.418,0-8,3.582-8,8v48c0,4.418,3.582,8,8,8h28.752c2.193,7.348,5.139,14.45,8.792,21.192l-20.344,20.344    c-3.123,3.124-3.123,8.188,0,11.312l33.952,33.952c3.174,3.001,8.138,3.001,11.312,0l20.344-20.352    c6.742,3.655,13.844,6.604,21.192,8.8V280c0,4.418,3.582,8,8,8h48c4.418,0,8-3.582,8-8v-28.752    c7.348-2.194,14.449-5.14,21.192-8.792l20.344,20.344c1.5,1.5,3.534,2.344,5.656,2.344s4.156-0.844,5.656-2.344l33.944-33.952    c3.123-3.124,3.123-8.188,0-11.312l-20.344-20.344c3.655-6.742,6.604-13.844,8.8-21.192h28.752c4.418,0,8-3.582,8-8v-48    C398.512,115.582,394.93,112,390.512,112z M382.513,160h-26.888c-3.709,0.001-6.931,2.551-7.784,6.16    c-2.366,9.945-6.309,19.447-11.68,28.144c-1.95,3.157-1.473,7.241,1.152,9.864l19.032,19.024l-22.64,22.64l-19.024-19.04    c-2.623-2.625-6.707-3.102-9.864-1.152c-8.695,5.378-18.197,9.325-28.144,11.688c-3.609,0.853-6.159,4.075-6.16,7.784V272h-32    v-26.88c-0.001-3.709-2.551-6.931-6.16-7.784c-9.947-2.363-19.449-6.31-28.144-11.688c-3.157-1.95-7.241-1.473-9.864,1.152    l-19.024,19.04l-22.64-22.64l19.032-19.04c2.625-2.623,3.102-6.707,1.152-9.864c-5.371-8.698-9.314-18.199-11.68-28.144    c-0.853-3.609-4.075-6.159-7.784-6.16h-26.888v-32H153.4c3.709-0.001,6.931-2.551,7.784-6.16    c2.366-9.945,6.309-19.446,11.68-28.144c1.95-3.157,1.473-7.241-1.152-9.864L152.68,64.8l22.632-22.624l19.032,19.032    c2.623,2.625,6.707,3.102,9.864,1.152c8.693-5.379,18.196-9.323,28.144-11.68c3.609-0.853,6.159-4.075,6.16-7.784V16h32v26.896    c0.002,3.711,2.555,6.934,6.168,7.784c9.948,2.357,19.451,6.301,28.144,11.68c3.157,1.95,7.241,1.473,9.864-1.152l19.024-19.032    L356.345,64.8l-19.032,19.032c-2.625,2.623-3.102,6.707-1.152,9.864c5.371,8.698,9.314,18.199,11.68,28.144    c0.853,3.609,4.075,6.159,7.784,6.16h26.888V160z"/></g></g><g><g><path d="M254.512,96c-26.51,0-48,21.49-48,48s21.491,48,48,48c26.499-0.026,47.974-21.501,48-48    C302.512,117.49,281.022,96,254.512,96z M254.512,176c-17.673,0-32-14.327-32-32c0-17.673,14.327-32,32-32    c17.673,0,32,14.327,32,32C286.512,161.673,272.185,176,254.512,176z"/></g></g><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/></symbol><symbol viewBox="0 0 502.0029 502.00137" id="src-11"><g fill="rgb(0,0,0)"><path d="m460.646 10h-416.708c-18.714 0-33.938 15.521-33.938 34.6v420.122c0 19.078 15.224 34.6 33.89 34.6 3.139.025 315.346 2.492 438.5 2.679h.03a19.282 19.282 0 0 0 13.827-5.813 19.917 19.917 0 0 0 5.753-14.418l-7.421-437.793c-.33-18.735-15.553-33.977-33.933-33.977zm-416.708 12h416.708c11.879 0 21.719 9.954 21.935 22.184l6.511 384.244-96.777-99.462a33.563 33.563 0 0 0 -54.35-3.721l-45.03 53.805a21.4 21.4 0 0 1 -18.452 7.764 21.636 21.636 0 0 1 -17.013-10.959l-81.253-140.576a33.583 33.583 0 0 0 -56.1-3.578l-98.117 113.313v-300.414c0-12.462 9.841-22.6 21.938-22.6zm443.767 465.764a7.377 7.377 0 0 1 -5.282 2.236h-.011c-123.12-.187-435.288-2.654-438.474-2.679-12.1 0-21.938-10.138-21.938-22.6v-101.375l107.321-123.946.271-.337a21.585 21.585 0 0 1 36.236 2.221l81.252 140.576a33.576 33.576 0 0 0 55.057 4.892l45.03-53.805a21.57 21.57 0 0 1 35.25 2.83l.356.591 106.615 109.572.612 36.028a8.007 8.007 0 0 1 -2.295 5.796z"/><path d="m284.988 218.5c29.7 0 53.864-24.671 53.864-54.995s-24.164-54.995-53.864-54.995-53.863 24.671-53.863 54.995 24.163 54.995 53.863 54.995zm0-97.99c23.084 0 41.864 19.287 41.864 42.995s-18.78 43-41.864 43-41.863-19.288-41.863-42.995 18.775-42.996 41.863-42.996z"/></g></symbol><symbol viewBox="0 0 14 8" id="src-12">
  <defs>
    <style>.cls-1 { fill: none;stroke-width: 2px; fill-rule: evenodd; }</style>
  </defs>
  <path id="Shape_10_copy_5" data-name="Shape 10 copy 5" class="cls-1" d="M2,4L6,8l8-8"/>
</symbol><symbol viewBox="0 0 511.99063 512" id="src-13"><g><g><g><path d="M41.073,152.466c-1.425-3.903-5.074-6.551-9.226-6.696c-4.175-0.132-7.977,2.245-9.669,6.039     C7.468,184.791,0.009,219.844,0.009,255.99c0,48.964,13.875,96.559,40.124,137.639c25.548,39.983,61.564,72.053,104.158,92.743     c1.418,0.69,2.941,1.025,4.454,1.025c2.474,0,4.921-0.9,6.836-2.629c3.085-2.785,4.172-7.164,2.747-11.068L41.073,152.466z      M20.408,255.99c0-24.264,3.652-47.994,10.883-70.837l98.5,269.854C61.706,412.039,20.408,337.973,20.408,255.99z"/><path d="M345.376,480.765l-75.473-206.771c-1.471-4.028-5.3-6.702-9.58-6.702c-0.032,0-0.064,0-0.096,0     c-4.318,0.041-8.143,2.796-9.55,6.88l-73.753,214.293c-0.907,2.633-0.697,5.523,0.581,7.998c1.278,2.475,3.513,4.319,6.185,5.106     C207.225,508.492,231.555,512,256.001,512c29.053,0,57.656-4.883,85.015-14.514c2.907-1.024,5.195-3.307,6.226-6.212     c1.031-2.905,0.692-6.121-0.922-8.747C345.897,481.836,345.594,481.272,345.376,480.765z M256.001,491.602     c-18.944,0-37.814-2.291-56.238-6.818l60.841-176.773l63.36,173.59C301.937,488.241,279.126,491.602,256.001,491.602z"/><path d="M373.292,403.888c4.314,0,8.167-2.717,9.612-6.788l27.138-76.438c13.018-33.396,19.346-60.555,19.346-83.022     c0-33.87-10.023-51.413-18.869-66.891c-0.054-0.094-0.109-0.189-0.167-0.283c-0.982-1.597-1.959-3.175-2.926-4.737     c-10.569-17.065-19.698-31.803-19.698-47.571c0-16.074,11.879-33.424,31.069-33.424c0.317,0,0.804,0.041,1.321,0.085     c0.404,0.034,0.805,0.067,1.209,0.093c4.329,0.281,8.341-2.2,10.038-6.179c1.696-3.979,0.699-8.597-2.492-11.52     C381.573,23.87,320.18,0,256.001,0C169.666,0,89.708,43.127,42.115,115.365c-2.031,3.083-2.238,7.022-0.541,10.3     c1.696,3.277,5.032,5.383,8.72,5.505c6.281,0.208,11.719,0.314,16.16,0.314c23.686,0,58.376-2.55,65.182-3.068     c1.089,1.962,1.193,6.64,0.137,8.39c-2.685,0.3-14.319,1.553-26.893,2.209c-3.185,0.166-6.108,1.811-7.902,4.449     c-1.794,2.636-2.251,5.961-1.235,8.984l80.48,239.565c1.395,4.153,5.286,6.951,9.668,6.951c0.004,0,0.008,0,0.011,0     c4.386-0.005,8.278-2.813,9.665-6.973l53.793-161.323c0.738-2.214,0.696-4.613-0.122-6.8l-29.269-78.243     c-1.416-3.782-4.928-6.373-8.959-6.608c-11.584-0.675-22.772-1.988-24.791-2.231c-0.919-1.946-0.707-6.437,0.377-8.368     c7.002,0.524,42.099,3.064,64.336,3.064c23.69,0,58.382-2.55,65.184-3.068c1.09,1.961,1.196,6.641,0.139,8.389     c-2.677,0.3-14.328,1.554-26.896,2.211c-3.193,0.166-6.123,1.821-7.916,4.469c-1.792,2.648-2.239,5.983-1.207,9.009     l83.404,244.49c1.401,4.108,5.25,6.879,9.59,6.906C373.25,403.888,373.27,403.888,373.292,403.888z M303.83,158.48     c8.698-0.708,14.988-1.437,15.375-1.483c11.726-1.386,19.321-12.743,18.061-27.005c-1.206-13.633-10.034-22.696-21.423-22.014     c-0.065,0.004-0.133,0.008-0.198,0.013c-0.395,0.031-39.714,3.092-64.716,3.092c-23.477,0-63.551-3.063-63.953-3.093     c-0.061-0.005-0.122-0.009-0.184-0.012c-11.588-0.695-20.652,9.083-21.489,23.228c-0.836,14.126,6.861,24.914,18.351,25.817     c1.624,0.197,9.756,1.164,19.509,1.907l25.701,68.706l-43.012,128.993l-66.564-198.143c8.736-0.709,15.053-1.442,15.444-1.488     c11.724-1.386,19.316-12.747,18.055-27.012c-1.207-13.629-10.032-22.697-21.419-22.007c-0.065,0.004-0.133,0.008-0.198,0.013     c-0.374,0.031-35.884,2.795-60.879,3.071c44.547-57.103,112.646-90.666,185.71-90.666c51.924,0,101.868,16.978,142.757,48.187     c-18.452,8.187-31.428,27.326-31.428,49.574c0,21.573,11.053,39.419,22.755,58.312c0.927,1.497,1.864,3.01,2.806,4.541     c8.29,14.509,16.097,28.269,16.097,56.629c0,19.642-6.058,45.128-18.008,75.755c-0.038,0.098-0.074,0.196-0.109,0.295     l-17.388,48.972L303.83,158.48z"/><path d="M480.631,133.175c-2.361-4.308-7.461-6.319-12.133-4.786c-4.669,1.538-7.577,6.188-6.917,11.059     c1.038,7.665,1.566,15.707,1.566,23.901c0,26.824-5.711,53.594-17.971,84.247c-0.06,0.15-0.116,0.302-0.169,0.454l-75.07,217.056     c-1.393,4.031-0.132,8.504,3.164,11.213c1.868,1.534,4.166,2.319,6.479,2.319c1.765,0,3.539-0.458,5.132-1.388     c38.017-22.163,69.889-53.921,92.171-91.842c22.969-39.088,35.109-83.839,35.109-129.417     C511.991,213.087,501.147,170.617,480.631,133.175z M399.158,443.029l65.051-188.086c9.331-23.375,15.137-44.781,17.736-65.726     c6.365,21.591,9.65,44.116,9.65,66.774C491.595,329.489,456.798,398.762,399.158,443.029z"/></g></g></g><g><g><path d="M262.286,369.734c-5.342-1.782-11.119,1.108-12.901,6.451l-1.36,4.079c-1.781,5.343,1.108,11.119,6.451,12.901    c1.07,0.357,2.157,0.526,3.226,0.526c4.27,0,8.25-2.703,9.675-6.977l1.36-4.079C270.518,377.292,267.629,371.516,262.286,369.734z    "/></g></g><g><g><path d="M249.707,407.472c-5.344-1.786-11.119,1.108-12.901,6.45l-16.999,50.996c-1.781,5.343,1.108,11.119,6.451,12.9    c1.07,0.358,2.157,0.527,3.226,0.527c4.27,0,8.25-2.703,9.675-6.977l16.998-50.996    C257.939,415.029,255.05,409.253,249.707,407.472z"/></g></g><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/><g/></symbol></svg>
</div>
<!-- svg sprite linking     -->
      


      <script src="main.js"></script>

        <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>

   </body>
</html>
 
