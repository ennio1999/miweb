index.html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Luxury Cars</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="css/estilos.css" rel="stylesheet">
  <style>
    .custom-img {
      height: 500px;
      object-fit: cover;
      object-position: center;
    }
  </style>
</head>
<body style="background-color: black; background-size: cover; background-repeat: no-repeat; background-position: center;">

  <!-- Menú de navegación -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-transparent py-3">
    <div class="container justify-content-between">
      <a class="navbar-brand text-uppercase fw-bold" href="#">Luxury Cars</a>
      <div class="d-flex gap-4 text-uppercase">
        <a href="reserva.html" class="text-white text-decoration-none">Reservar</a>
        <a href="index.html" class="text-white text-decoration-none fw-bold">Home</a>
        <a href="contacto.html" class="text-white text-decoration-none">Contacto</a>
      </div>
    </div>
  </nav>

  <!-- Buscador -->
  <div class="container text-center my-4">
    <input type="text" class="form-control mx-auto w-50 rounded-pill shadow" placeholder="Buscar..." />
  </div>

  <!-- Botón principal -->
  <div class="text-center my-3">
    <a href="imagenes.html" class="btn btn-secondary px-5 py-3 text-uppercase fw-bold">Ver Imagenes</a>
  </div>

  <!-- Galería de marcas -->
  <div class="container my-5">
    <div class="row justify-content-center g-4">
      <div class="col-md-5">
        <div class="card bg-dark text-white border-0">
          <img src="https://images.unsplash.com/photo-1662929733813-ff9b3cc202bf?q=80&w=987&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img custom-img" alt="Ferrari">
          <div class="card-img-overlay d-flex align-items-center justify-content-center bg-black bg-opacity-50">
            <h3 class="card-title text-center text-uppercase">Ferrari</h3>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <div class="card bg-dark text-white border-0">
          <img src="https://images.unsplash.com/photo-1737026340946-2a09aa0590d9?q=80&w=1065&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img custom-img" alt="Lamborghini">
          <div class="card-img-overlay d-flex align-items-center justify-content-center bg-black bg-opacity-50">
            <h3 class="card-title text-center text-uppercase">Lamborghini</h3>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
