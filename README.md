### Hi there 👋 Cambadaaaaa
<h4 class=".digitando">Hello World</h4>


<script>
  function ativaLetra(elemento){
    const arrTexto = elemento.innerHTML.split('');
    elemento.innerHTML = '';
    arrTexto.forEach((letra, i)=>{
        setTimeout(()=>{
            elemento.innerHTML += letra;
        }, 70 * i);
    });
}
const titulo = document.querySelector('.digitando');
ativaLetra(titulo);
</script>
