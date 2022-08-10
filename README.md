# dom_formulario

<!-- Dado el código HTML a continuación termina de rellenarlo para tras rellenar los campos de nombre y apellido y hacer clic en enviar, estos datos aparezcan en la pantalla «hola nombre apellidos, gracias por rellenar el formulario de LarnU». -->

<script>
    const $nombre = document.getElementById("nombre");
    const $apellido = document.getElementById("apellido");
    const $saludo = document.getElementById("saludo");
    function enviarSaludo() {
      let saludo = `Hola ${$nombre.value} ${$apellido.value}, gracias por rellenar el formulario de LarnU`;
      $saludo.innerHTML = saludo;
    }
  </script>
