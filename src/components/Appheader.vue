<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light mb-5">
      <div class="container">
        <a class="navbar-brand" href="#">Food<span class="logotxt">Ko</span></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto me-5">
            <li class="nav-item active">
              <a class="nav-link me-4" href="#landingpagesection">Home </a>
            </li>

            <li class="nav-item">
              <a class="nav-link me-4" href="#aboutsection">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-4" href="#productsection">Product</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#contactsection">Contact</a>
            </li>
          </ul>
        </div>
      </div>

      <button
        type="button"
        class="searchiconbtn"
        data-toggle="modal"
        data-target="#exampleModalCenter"
      >
        <i class="fas fa-search"></i>
      </button>

      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModalCenter"
        tabindex="-1"
        role="dialog"
        aria-labelledby="exampleModalCenterTitle"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-dialog-centered" role="document">
          <div class="modal-content">
            <div class="modal-header">
              <div class="input-group mb-3">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Recipient's username"
                  aria-label="Recipient's username"
                  aria-describedby="button-addon2"
                />
                <button
                  class="btn btn-outline-secondary"
                  type="button"
                  id="button-addon2"
                >
                  <span><i class="iconmodal fas fa-search"></i></span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div
        data-bs-spy="scroll"
        data-bs-target="#navbar-example2"
        data-bs-offset="0"
        class="scrollspy-example"
        tabindex="0"
      ></div>
    </nav>
  </header>
</template>
