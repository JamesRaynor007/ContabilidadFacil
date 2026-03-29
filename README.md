<h1> Contabilidad Facil </h1>

<h2> Calcule sus ingresos y gastos en su móvil</h2>

<h3> Proyecte sus resultados</h3>


<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<title>Contabilidad de Diez</title>
<!-- Enlace al archivo CSS externo -->
<link rel="stylesheet" href="style.css" />
</head>
<body>
<h1 style="text-align: center;">Contabilidad de Diez</h1>

<div class="tabla-container">
  <form id="formulario">
    <table>
      <tr>
        <th class="texto-peque">Valor</th>
        <th class="texto-peque">Tipo</th>
        <th class="texto-peque">Comentario</th>
      </tr>
    </table>
  </form>
</div>

<!-- Carga el script justo antes de cerrar el body -->
<script src="JavaScript/JavaScript.js"></script>

<!-- Alternativamente, puedes usar un evento DOMContentLoaded para asegurar que el script se ejecute cuando el DOM esté listo -->
<script>
  document.addEventListener('DOMContentLoaded', function() {
    // Aquí puedes llamar a funciones o inicializar tu código si es necesario
    if (typeof init === 'function') {
      init();
    }
  });
</script>
</body>
</html>
