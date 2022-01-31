<template>
  <section class="landingpage padding" id="landingpagesection">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="main">
            <h1 class="mainheader">
              <quote
                >All you need to <span class="h1spantext">feel better</span> is
                coffee <i class="coffeeicon fas fa-mug-hot"></i
              ></quote>
            </h1>
            <div class="flavornreview d-flex">
              <p class="flavorname">Vinegar Flavored</p>
              <button class="reviewbtn">
                <i class="star fas fa-star me-2"></i>4.8
              </button>
            </div>
            <p class="maintxt">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor
              praesentium asperiores, optio nobis repudiandae consequatur
              blanditiis ipsa eaque sint illum delectus, debitis beatae. Dolor,
              corporis!
            </p>
            <p class="salerate">$3.99<span class="prevrate"> $5.99</span></p>

            <div class="counterbtn">
              <ul>
                <li>
                  <div class="number">
                    <span class="minus">-</span>
                    <input type="text" value="1" />
                    <span class="plus">+</span>
                  </div>
                </li>

                <li>
                  <div class="btnnewcontainer">
                    <button class="addtocartbtn btn btn-outline-dark">
                      <i class="fas fa-shopping-cart"></i>Add to cart
                    </button>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="col-md-6">
          <div class="container-slidercarouselwiththumbnail">
            <div class="row">
              <div class="col-md-12">
                <div
                  id="custCarousel"
                  class="carousel slide"
                  data-ride="carousel"
                  align="center"
                >
                  <!-- slides -->
                  <div class="carousel-inner">
                    <div class="carousel-item active">
                      <img
                        src="https://images.unsplash.com/photo-1578583112957-2dcf6878aeae?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8c3BpbHQlMjBjb2ZmZWV8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60"
                        alt="Hills"
                      />
                    </div>
                    <div class="carousel-item">
                      <img
                        src="https://images.unsplash.com/photo-1495774856032-8b90bbb32b32?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fHNwaWx0JTIwY29mZmVlfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                        alt="Hills"
                      />
                    </div>

                    <div class="carousel-item">
                      <img
                        src="https://media.istockphoto.com/photos/barista-preparing-to-test-and-inspecting-the-quality-of-coffee-picture-id1284116251?b=1&k=20&m=1284116251&s=170667a&w=0&h=W3bkq3BplVPXWoCaSQnZ41iAaNLA1004Jj0R02B0kFo="
                        alt="Hills"
                      />
                    </div>

                    <div class="carousel-item">
                      <img
                        src="https://media.istockphoto.com/photos/mug-on-plate-filled-with-coffee-surrounded-by-coffee-beans-picture-id157528129?b=1&k=20&m=157528129&s=170667a&w=0&h=8DLweTb1F3_rJFKpHn9ha8aIiQQDAJKdX5y2pR63VsA="
                        alt="Hills"
                      />
                    </div>
                  </div>
                  <!-- Left right -->
                  <a
                    class="carousel-control-prev"
                    href="#custCarousel"
                    data-slide="prev"
                  >
                    <span class="carousel-control-prev-icon"></span>
                  </a>
                  <a
                    class="carousel-control-next"
                    href="#custCarousel"
                    data-slide="next"
                  >
                    <span class="carousel-control-next-icon"></span>
                  </a>
                  <!-- Thumbnails -->
                  <ol class="carousel-indicators list-inline">
                    <li class="list-inline-item active">
                      <a
                        id="carousel-selector-0"
                        class="selected"
                        data-slide-to="0"
                        data-target="#custCarousel"
                      >
                        <img
                          src="https://images.unsplash.com/photo-1578583112957-2dcf6878aeae?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8c3BpbHQlMjBjb2ZmZWV8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60"
                          class="img-fluid"
                        />
                      </a>
                    </li>
                    <li class="list-inline-item">
                      <a
                        id="carousel-selector-1"
                        data-slide-to="1"
                        data-target="#custCarousel"
                      >
                        <img
                          src="https://images.unsplash.com/photo-1495774856032-8b90bbb32b32?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fHNwaWx0JTIwY29mZmVlfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                          class="img-fluid"
                        />
                      </a>
                    </li>
                    <li class="list-inline-item">
                      <a
                        id="carousel-selector-2"
                        data-slide-to="2"
                        data-target="#custCarousel"
                      >
                        <img
                          src="https://media.istockphoto.com/photos/barista-preparing-to-test-and-inspecting-the-quality-of-coffee-picture-id1284116251?b=1&k=20&m=1284116251&s=170667a&w=0&h=W3bkq3BplVPXWoCaSQnZ41iAaNLA1004Jj0R02B0kFo="
                          class="img-fluid"
                        />
                      </a>
                    </li>
                    <li class="list-inline-item">
                      <a
                        id="carousel-selector-2"
                        data-slide-to="2"
                        data-target="#custCarousel"
                      >
                        <img
                          src="https://media.istockphoto.com/photos/mug-on-plate-filled-with-coffee-surrounded-by-coffee-beans-picture-id157528129?b=1&k=20&m=157528129&s=170667a&w=0&h=8DLweTb1F3_rJFKpHn9ha8aIiQQDAJKdX5y2pR63VsA="
                          class="img-fluid"
                        />
                      </a>
                    </li>
                  </ol>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="about padding" id="aboutsection">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <img
            src="https://ceremonycoffee.com/wp-content/uploads/cranberry-redf1a1a2-756x1080.jpg"
            alt=""
          />
          <div class="coffee-body">
            <p>SINGLE ORIGIN</p>
            <h6>Ecuador Los Eucaliptos</h6>
            <span>$12.50</span>
          </div>
        </div>
        <div class="col-md-3">
          <img
            src="https://ceremonycoffee.com/wp-content/uploads/ceremony-product-clementine-2020-756x1080.jpg"
            alt=""
          />
          <div class="coffee-body">
            <p>SINGLE ORIGIN</p>
            <h6>Colombia La Finlandia</h6>
            <span>$20.00</span>
          </div>
        </div>

        <div class="col-md-6">
          <div class="about-body">
            <h6>NEW ARRIVALS</h6>
            <h4>Freshest Of the Fresh</h4>
            <p>
              Featuring the freshest in our beautiful range of seasonal coffees
              sourced throughout the year
            </p>
            <div class="btnnewcontainer">
              <button class="addtocartbtn btn btn-outline-dark">
                <i class="fas fa-shopping-bag"></i>Shop Now
              </button>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-md-6">
          <div class="about-body-two">
            <h6>NEW ARRIVALS</h6>
            <h4>Freshest Of the Fresh</h4>
            <p>
              Featuring the freshest in our beautiful range of seasonal coffees
              sourced throughout the year
            </p>
            <div class="btnnewcontainer">
              <button class="addtocartbtn btn btn-outline-dark">
                <i class="fas fa-shopping-bag"></i>Shop Now
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-5">
          <img
            src="https://ceremonycoffee.com/wp-content/uploads/ceremony-product-clementine-2020-756x1080.jpg"
            alt=""
          />
          <div class="coffee-body">
            <p>SINGLE ORIGIN</p>
            <h6>Colombia La Finlandia</h6>
            <span>$20.00</span>
          </div>
        </div>

        <div class="col-md-3 mt-5">
          <img
            src="https://ceremonycoffee.com/wp-content/uploads/cranberry-redf1a1a2-756x1080.jpg"
            alt=""
          />
          <div class="coffee-body">
            <p>SINGLE ORIGIN</p>
            <h6>Ecuador Los Eucaliptos</h6>
            <span>$12.50</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="product padding" id="productsection">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <i class="fab fa-instagram-square"></i>
          <div class="productbody">
            <h3><span>Coffee</span> Products</h3>
            <p>Follow along for new events,products and more.</p>
          </div>

          <div class="alert alert-secondary" role="alert">CAFFÈ LATTE</div>
          <div class="alert alert-success" role="alert">CAFFÈ MOCHA</div>
          <div class="alert alert-danger" role="alert">CAPPUCCINO</div>
          <div class="alert alert-warning" role="alert">
            DOUBLE ESPRESSO (DOPPIO)
          </div>
          <div class="alert alert-info" role="alert">CAFÈ AU LAIT</div>
          <div class="alert alert-light" role="alert">AFFOGATO</div>
        </div>

        <div class="col-md-9">
          <div class="container">
            <div class="product-grid">
              <div class="img1">
                <img
                  src="https://media.istockphoto.com/photos/a-man-and-a-woman-clinking-coffee-mugs-in-cafe-picture-id1323637777?b=1&k=20&m=1323637777&s=170667a&w=0&h=ALyFdW7e5ohTN0XHp-EARbZu8as4eSOfRowr4v7ScZU="
                  alt=""
                  class="imgcof"
                />
              </div>
              <div class="img1">
                <img
                  src="https://cdn.pixabay.com/photo/2016/05/11/13/47/good-morning-1385750__340.jpg"
                  alt=""
                  class="imgcof"
                />
              </div>
              <div class="img1">
                <img
                  src="https://media.istockphoto.com/photos/mug-on-plate-filled-with-coffee-surrounded-by-coffee-beans-picture-id157528129?b=1&k=20&m=157528129&s=170667a&w=0&h=8DLweTb1F3_rJFKpHn9ha8aIiQQDAJKdX5y2pR63VsA="
                  alt=""
                  class="imgcof"
                />
              </div>
              <div class="img1">
                <img
                  src="https://cdn.pixabay.com/photo/2015/12/06/09/15/maple-1079235__340.jpg"
                  alt=""
                  class="imgcof"
                />
              </div>
              <div class="img1">
                <img
                  src="https://media.istockphoto.com/photos/barista-preparing-to-test-and-inspecting-the-quality-of-coffee-picture-id1284116251?b=1&k=20&m=1284116251&s=170667a&w=0&h=W3bkq3BplVPXWoCaSQnZ41iAaNLA1004Jj0R02B0kFo="
                  alt=""
                  class="imgcof"
                />
              </div>
              <div class="img1">
                <img
                  src="https://cdn.pixabay.com/photo/2016/02/13/17/40/coffee-1198273__340.jpg"
                  alt=""
                  class="imgcof"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact padding" id="contactsection">
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <img
            src="https://embed.filekitcdn.com/e/bvA5v4FqSaWiuK7ysVxFTa/iNJjzAczvnom3RDT7NhDx5"
            alt="3 cups of coffee cheers image"
          />
        </div>
        <div class="col-md-4">
          <h4>WE'VE FOUND THE BEST <span>COFFEE</span> DISCOUNTS...</h4>

          <h5>They're Inside Our Free Newsletter</h5>
          <span
            ><i class="far fa-hand-point-down"></i>
            <i class="fas fa-mug-hot"></i> <i class="far fa-hand-point-down"></i
          ></span>
          <br />
          <input
            type="textfield"
            placeholder="Email Address"
            class="emailfield"
          />
          <div class="btnnewcontainer">
            <button class="addtocartbtn btn btn-outline-dark">
              <i class="fas fa-key"></i>Sign In
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
