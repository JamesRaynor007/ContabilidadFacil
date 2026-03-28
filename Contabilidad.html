<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<title>Contabilidad de Diez</title>
<style>
  body { 
    background-color: #46826D; 
    color: white; 
    font-family: Arial, sans-serif; 
    margin: 0;
    padding: 20px;
    text-align: center; /* Centra el contenido del body */
  }
  /* Títulos principales */
  h1, h2 {
    font-size: 18px; /* Tamaño 18 para títulos */
    margin: 10px 0;
  }
  /* Texto general en botones y palabras */
  .texto-peque {
    font-size: 15px;
  }
  /* Fuente para los valores (inputs) y resultados */
  .valor-input {
    font-size: 15px; /* Tamaño 15 para inputs de valores */
  }
  /* Fuente para resultados */
  #resultados {
    font-size: 18px; /* Tamaño 18 en resultados */
    white-space: pre-wrap; /* Para mantener saltos de línea en resultados */
  }

  /* Contenedor para centrar la tabla */
  .tabla-container {
    display: inline-block; /* Hace que el contenedor tenga ancho ajustado a su contenido */
    text-align: left; /* Para que el contenido interno (la tabla) se alinee a la izquierda dentro del contenedor */
    width: 100%; /* Para que ocupe todo el ancho en pantallas pequeñas */
    max-width: 700px; /* Limitar ancho máximo */
  }
  table {
    margin: 0 auto; /* Centra la tabla dentro del contenedor */
    border-collapse: collapse;
    background-color: #fff; /* Fondo de la tabla */
    width: 100%; /* La tabla ocupa todo el ancho del contenedor */
  }
  th, td {
    padding: 8px 12px;
    border: 1px solid #ccc;
    color: black; /* Texto visible en la tabla */
    text-align: left;
  }

  /* Intercalado de colores en filas */
  table tr:nth-child(even) {
    background-color: #f0f0f0; /* Color gris claro para filas pares */
  }
  table tr:nth-child(odd) {
    background-color: #ffffff; /* Color blanco para filas impares */
  }

  /* Otros estilos */
  button {
    margin-top: 10px;
    padding: 8px 16px;
    cursor: pointer;
    font-size: 15px; /* Fuente en botón */
  }

  /* Media Queries para responsividad */
  @media (max-width: 600px) {
    body {
      padding: 10px;
    }
    h1, h2 {
      font-size: 16px;
    }
    .texto-peque {
      font-size: 14px;
    }
    .valor-input {
      font-size: 14px;
      width: 60px; /* Reduce ancho en pantallas pequeñas */
    }
    button {
      padding: 8px 12px;
      font-size: 14px;
    }
    table {
      font-size: 14px;
    }
  }
  @media (max-width: 400px) {
    h1, h2 {
      font-size: 14px;
    }
    .texto-peque {
      font-size: 13px;
    }
    .valor-input {
      font-size: 13px;
      width: 50px;
    }
    button {
      padding: 6px 10px;
      font-size: 13px;
    }
  }
</style>
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
      <!-- Generar 10 filas -->
      <script>
        for(let i=0; i<10; i++){
          document.write('<tr>');
          document.write('<td><input type="number" id="valor'+i+'" class="valor-input" style="width:80px; font-size:15px;"></td>');
          document.write('<td>');
          document.write('<select id="tipo'+i+'" class="texto-peque">');
          document.write('<option value="Ingreso">Ingreso</option>');
          document.write('<option value="Gasto">Gasto</option>');
          document.write('</select>');
          document.write('</td>');
          document.write('<td><input type="text" id="comentario'+i+'" style="width:120px; font-size:15px;" placeholder="Opcional"></td>');
          document.write('</tr>');
        }
      </script>
    </table>
    <button type="button" onclick="calcular()">Calcular Totales</button>
  </form>
</div>

<h2>Resultados</h2>
<pre id="resultados"></pre>

<script>
  // Función para formatear números con separadores
  function formatearNumero(numero) {
    const numStr = numero.toFixed(2).replace('.', ',');
    const partes = numStr.split(',');
    let entero = partes[0];
    const decimal = partes[1];

    entero = entero.replace(/\B(?=(\d{3})+(?!\d))/g, '.');

    return entero + ',' + decimal;
  }

  function calcular() {
    let totalIngresos = 0;
    let totalGastos = 0;
    let hayEntradaValida = false;

    for(let i=0; i<10; i++){
      const valorStr = document.getElementById('valor'+i).value.trim();
      const tipo = document.getElementById('tipo'+i).value;
      // Comentario no afecta en cálculo, pero se obtiene si se necesita
      // const comentario = document.getElementById('comentario'+i).value.trim();

      if(valorStr !== ''){
        const valor = parseFloat(valorStr);
        if(isNaN(valor) || valor < 0){
          alert('Por favor ingrese un número válido y no negativo en el campo ' + (i+1));
          return;
        }
        if(tipo === 'Ingreso'){
          totalIngresos += valor;
        } else {
          totalGastos += valor;
        }
        hayEntradaValida = true;
      }
    }

    if(!hayEntradaValida){
      alert('Debe ingresar al menos un campo numérico.');
      return;
    }

    const diferencia = totalIngresos - totalGastos;

    const totalIngresosFormateado = formatearNumero(totalIngresos);
    const totalGastosFormateado = formatearNumero(totalGastos);
    const diferenciaFormateada = formatearNumero(diferencia);

    document.getElementById('resultados').textContent =
      `Total Ingresos: ${totalIngresosFormateado}\n` +
      `Total Gastos: ${totalGastosFormateado}\n` +
      `Diferencia (Ingresos - Gastos): ${diferenciaFormateada}`;
  }
</script>

</body>
</html>
