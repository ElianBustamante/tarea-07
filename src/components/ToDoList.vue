<template>
  <div class="row">
    <div class="col-md-6 offset-md-3">
      <nav class="navbar navbar-dark bg-primary">
        <div class="container-fluid">
          <a href="#" class="navbar-brand">ToDoer</a>
        </div>
      </nav>
      <div class="container" id="div-body">
        <div class="row">
          <div class="col-1"></div>
          <div class="col-10">
            <form method="POST" class="form-inline">
              <div class="row">
                <div class="col-10 mb-4">
                    <input
                    type="text"
                    class="form-control mb-2 mr-sm-2 to-do"
                    placeholder="¿Qué quieres hacer hoy?..."
                    required
                    />
                </div>
                <div class="col-2">
                  <button class="btn btn-success btn-circle" type="submit">
                    +
                  </button>
                </div>
              </div>
            </form>
            <div class="mb-4">
              //LISTADO AQUI
            </div>
            <div>
              //TAREAS COMPLETADAS
            </div>
          </div>
          <div class="col-1"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
#div-body {
  background-color: rgb(194, 225, 255 );
  height: auto;
  padding-bottom: 40px;
  border-radius: 20px;
  width: 100%;
}

.btn-circle {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  text-align: center;
  font-size: 15px;
  font-weight: bold;
  line-height: 1.42857;
}

.to-do {
  border-radius: 10px;
  height: 40px;
}

nav {
  height: 70px;
  border-radius: 20px;
}

form {
  margin-top: 50px;
}
</style>
