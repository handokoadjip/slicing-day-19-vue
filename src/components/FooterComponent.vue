<template>
  <footer class="pb-5 px-4">
    <div class="container-fluid border-top">
      <div class="row align-items-center py-5">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center">
              <div class="mb-5 mb-lg-0">
                <p class="mp-0">&copy; Quadra Collective</p>
              </div>
              <ul class="d-inline mp-0">
                <li class="d-inline">
                  <router-link class="nav-link fs-7 d-lg-inline d-block" to="#">Instagram</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 d-lg-inline d-block" to="#">Facebook</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 d-lg-inline d-block" to="#">Tumblr</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 d-lg-inline d-block" to="#">Pinterest</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>