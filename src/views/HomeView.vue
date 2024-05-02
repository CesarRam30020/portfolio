<template>
  <div class="row p-5">
    <div class="col-md-2">
      <div class="card">
        <img src="../assets/images/porfile.jpg" class="card-img-top" :alt="no">
        <div class="card-body">
          <div class="card-title">
            <div class="row text-center">
              <div class="col-md-12">César Ramírez</div>
              <section class="col-md-12">
                <ul class="list-unstyled d-flex justify-content-between">
                  <li>
                    <a href="https://www.linkedin.com/in/cesar-oswaldo-ramírez-rodríguez-3a49b7247" target="_blank" class="linkedin">
                      <i class="fa-brands fa-linkedin fa-2x"></i>
                    </a>
                  </li>
                  <li>
                    <a href="#" class="github">
                      <i class="fa-brands fa-github fa-2x"></i>
                    </a>
                  </li>
                  <li>
                    <a href="#" class="npm">
                      <i class="fa-brands fa-npm fa-2x"></i>
                    </a>
                  </li>
                </ul>
              </section>
            </div>
          </div>
          <div class="card-text">Texto</div>
        </div>
      </div>
    </div>

    <div class="col-md-10">
      <div class="card">
        <div class="card-body">
          <div class="card-title">Titulo</div>
          <div class="card-text">Texto</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style>
.linkedin {
  color: #000;
  text-decoration: none;
}
.linkedin:hover {
  color: #378FE9;
}

.github {
  color: #000;
  text-decoration: none;
}
.github:hover {
  color: #000;
}

.npm {
  color: #000;
  text-decoration: none;
}
.npm:hover {
  color: red;
  transform: scale(10%);
}
</style>