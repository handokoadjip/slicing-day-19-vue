<template>
  <header class="position-relative mb-5 pb-5">
    <nav class="navbar navbar-light px-4">
      <div class="container-fluid">
        <router-link class="navbar-brand text-center d-none d-lg-block mp-0" to="#">
          Quadra Collective
        </router-link>

        <div class="btn bg-white border rounded-circle ms-auto me-3">
          0
        </div>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse mt-3" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">home</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">about</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="px-4">
      <div class="container-fluid">
        <div class="row align-items-end min-vh-60 pt-5">
          <div class="col-lg-10">
            <div class="wrapper d-flex align-items-end h-100">
              <div class="w-100">
                <h1 class="fw-normal display-3 mp-0 text-border-top">
                  Quadra Collective is a Brazilian design shop presenting minimalist art prints.
                </h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

