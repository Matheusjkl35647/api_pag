<script scoped>
    export default {
        data() {
            return {
                mensagem: 'Dados do Cartão'
            }
        }
    }
</script>

<template>
    <!-- Precisa virar um componente -->
    <div class="cartaoUsuario"> 
        <div class="card rounded-4 text-white mb-3 mx-3 shadow cartaoFundo">
            <div class="card-body container">
                <div class="row">
                    <div class="col empresaCartao">
                        <img src="../assets/img/Visa-branco.png" alt="chipCartao">
                    </div>
                </div>
                <div class="row">
                    <div class="col chipCartao">
                        <img src="../assets/img/chip.png" alt="chipCartao">
                    </div>
                </div>
            </div>
            <div class="card-body">
                <div class="row">
                    <div class="col">
                      <h2>00000-00000-00000-00000 </h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                      <h5>MATHEUS J SANTOS</h5>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        00/00
                    </div>
                    <div class="col">
                       000
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Precisa virar componente também -->
    <div class="fundoForm">
        <h3 class="text-center">
            <b>{{ mensagem  }}</b>
        </h3>
        
    </div>
     
 </template>