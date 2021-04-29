<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>
      Frontend Mentor | Fylo landing page with dark theme and features grid
    </title>

    <!-- googel font  -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <!-- font aowsme -->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.3/css/all.css"
      integrity="sha384-SZXxX4whJ79/gErwcOYf+zWLeJdY/qpuqC4cAa9rOGUstPomtqpuNWT9wdPEn2fk"
      crossorigin="anonymous"
    />
    <!-- bootstrap css   -->
    <link rel="stylesheet" href="style/bootstrap.min.css" type="text/css" />
    <!-- bootstrap reboot -->
    <link
      rel="stylesheet"
      href="style/bootstrap-reboot.min.css"
      type="text/css"
    />
    <!-- style sheet  -->
    <link rel="stylesheet" href="style/sytle.css" type="text/css" />
  </head>
  <body>
    <header class="container-fluid text-center pb-3">
      <div
        class="nav container d-flex my-3 justify-content-between align-items-center"
      >
        <img src="images/logo.svg" class="logo" alt="" />
        <nav class="d-flex align-items-center">
          <ul class="m-0">
            <a class="mx-lg-2 mx-1" href="#">Features</a
            ><a class="mx-lg-2 mx-1" href="#">Team</a
            ><a class="mx-lg-2 mx-1" href="#">Sign In</a>
          </ul>
        </nav>
      </div>
      <div class="container d-flex my-5 justify-content-center">
        <img
          src="images/illustration-intro.png"
          class="col-lg-8 col-10"
          alt=""
        />
      </div>
      <div class="col-lg-4 col-md-8 mx-auto">
        <h2>All your files in one secure location, accessible anywhere.</h2>

        <p>
          Fylo stores all your most important files in one secure location.
          Access them wherever you need, share and collaborate with friends
          family, and co-workers.
        </p>
      </div>
      <button class="btn">Get Started</button>
    </header>
    <main class="container my-4 text-center">
      <section class="ft my-4">
        <div class="row d-flex align-items-center justify-content-around my-4">
          <div
            class="col-lg-4 my-4 col-md-8 d-flex align-items-center justify-content-center flex-column"
          >
            <img src="images/icon-access-anywhere.svg" class="mb-4" alt="" />
            <h4>Access your files, anywhere</h4>
            <p>
              The ability to use a smartphone, tablet, or computer to access
              your account means your files follow you everywhere.
            </p>
          </div>
          <div
            class="col-lg-4 my-4 col-md-8 d-flex align-items-center justify-content-center flex-column"
          >
            <img src="images/icon-security.svg" class="mb-4 mt-n3" alt="" />
            <h4>Security you can trust</h4>
            <p>
              2-factor authentication and user-controlled encryption are just a
              couple of the security features we allow to help secure your
              files.
            </p>
          </div>
        </div>
        <div class="row d-flex align-items-center justify-content-around my-4">
          <div
            class="col-lg-4 col-md-8 my-4 d-flex align-items-center justify-content-center flex-column"
          >
            <img src="images/icon-collaboration.svg" class="mb-4" alt="" />
            <h4>Real-time collaboration</h4>
            <p>
              Securely share files and folders with friends, family and
              colleagues for live collaboration. No email attachments required.
            </p>
          </div>
          <div
            class="col-lg-4 my-4 col-md-8 d-flex align-items-center justify-content-center flex-column"
          >
            <img src="images/icon-any-file.svg" class="mb-4" alt="" />
            <h4>Store any type of file</h4>
            <p>
              Whether you're sharing holidays photos or work documents, Fylo has
              you covered allowing for all file types to be securely stored and
              shared.
            </p>
          </div>
        </div>
      </section>
      <section
        class="stayp d-flex flex-wrap justify-content-between align-items-center"
      >
        <div class="col-lg-6 mb-5">
          <img
            src="images/illustration-stay-productive.png"
            class="img-fluid"
            alt=""
          />
        </div>
        <div class="col-lg-6 text-left">
          <h2>Stay productive, wherever you are</h2>
          <p>
            Never let location be an issue when accessing your files. Fylo has
            you covered for all of your file storage needs.
          </p>
          <p>
            Securely share files and folders with friends, family and colleagues
            for live collaboration. No email attachments required.
          </p>
          <div class="link">
            <a href="#"
              >See how Fylo works <i class="fas fa-arrow-circle-right"></i
            ></a>
          </div>
        </div>
      </section>
      <section
        class="testmine container d-flex flex-wrap justify-content-between"
      >
        <div class="con-flex col-12 col-lg-4 my-3">
          <div class="card-test p-3 rounded text-left">
            <p>
              Fylo has improved our team productivity by an order of magnitude.
              Since making the switch our team has become a well-oiled
              collaboration machine.
            </p>
            <div class="con-testmine d-flex align-items-start">
              <img
                class="mr-3 rounded-circle img-fluid"
                src="images/profile-1.jpg"
                alt=""
              />
              <div class="titles align-self-end">
                <h3>Satish Patel</h3>
                <h4>Founder & CEO, Huddle</h4>
              </div>
            </div>
          </div>
        </div>
        <div class="con-flex col-lg-4 my-3">
          <div class="card-test p-3 rounded text-left">
            <p>
              Fylo has improved our team productivity by an order of magnitude.
              Since making the switch our team has become a well-oiled
              collaboration machine.
            </p>
            <div class="con-testmine d-flex align-items-start">
              <img
                class="mr-3 rounded-circle"
                src="images/profile-2.jpg"
                alt=""
              />
              <div class="titles align-self-end">
                <h3>Bruce McKenzie</h3>
                <h4>Founder & CEO, Huddle</h4>
              </div>
            </div>
          </div>
        </div>
        <div class="con-flex col-lg-4 my-3">
          <div class="card-test p-3 rounded text-left">
            <p>
              Fylo has improved our team productivity by an order of magnitude.
              Since making the switch our team has become a well-oiled
              collaboration machine.
            </p>
            <div class="con-testmine d-flex align-items-start">
              <img
                class="mr-3 rounded-circle"
                src="images/profile-3.jpg"
                alt=""
              />
              <div class="titles align-self-end">
                <h3>Iva Boyd</h3>
                <h4>Founder & CEO, Huddle</h4>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="contact">
        <div class="col-lg-8 mx-auto position-absolute half">
          <h3>Get early access today</h3>
          <p>
            It only takes a minute to sign up and our free starter tier is
            extremely generous. If you have any questions, our support team
            would be happy to help you.
          </p>
          <form action="">
            <div
              class="form-row col-lg-11 align-items-center mx-auto d-flex justify-content-between"
            >
              <div class="col-lg-8 col-md-8 my-2">
                <input
                  type="email"
                  required
                  class="form-control rounded-pill border-0"
                  placeholder="email@example.com"
                />
              </div>
              <div class="col-lg-4 col-md-4 my-2">
                <button
                  type="submit"
                  class="btn btn-secondary border-0 w-100 rounded-pill btn-clr"
                >
                  Get Started For Free
                </button>
              </div>
            </div>
          </form>
        </div>
      </section>
    </main>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-lg-3">
            <img src="images/logo.svg" alt="" />
          </div>
        </div>

        <div class="row my-4 d-flex justify-content-lg-between">
          <div class="col-lg-4">
            <div class="con">
              <div class="conflex d-flex justify-content-between">
                <i class="fas fa-map-marker-alt mr-3 ml-2 my-1"></i>
                <p class="d-inline align-self-stretch">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-2 col-md-3">
            <div class="con">
              <div class="d-flex">
                <i class="fas fa-phone my-1 mr-3 ml-2"></i>
                <p>+1-543-123-4567</p>
              </div>
              <div class="d-flex">
                <i class="fas fa-envelope my-1 mr-3 ml-2"></i>
                <p>example@fylo.com</p>
              </div>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-6 mx-2">
            <div class="con">
              <div class="d-flex flex-wrap justify-content-between">
                <p>About Us</p>
                <p>Jobs</p>
              </div>
              <div class="d-flex flex-wrap justify-content-between">
                <p>Press</p>
                <p>Blog</p>
              </div>
              <div class="d-flex flex-wrap justify-content-between">
                <p>Contact Us</p>
                <p>Terms</p>
              </div>
              <div class="d-flex flex-wrap justify-content-between">
                <p>Privacy</p>
              </div>
            </div>
          </div>
          <div class="col-lg-2 col-md-3">
            <div class="con soical">
              <div class="d-flex justify-content-lg-end justify-content-center">
                <i class="mx-2 p-2 rounded-circle fab fa-facebook-f"></i>

                <i class="mx-2 p-2 rounded-circle fab fa-twitter"></i>

                <i class="mx-2 p-2 rounded-circle fab fa-instagram"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <div style="display: none">
      Founder & CEO, Huddle Fylo has improved our team productivity by an order
      of magnitude. Since making the switch our team has become a well-oiled
      collaboration machine. Get early access today L About Us Jobs Press Blog
      Contact Us Terms Privacy
    </div>
    <div>
      <p class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by <a href="#">Your Name Here</a>.
      </p>
    </div>
  </body>
</html>
