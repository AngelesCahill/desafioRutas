<template>
    <div>
        <form bg-dark>
            <div class="container">
                <div class="row bg-light my-5 py-5 border">
                    <div class="form-group col-12">
                        <label for="fname" class="col-sm-2 col-form-label d-inline-block">Nombre</label>
                        <div class="col-sm-4 d-inline-block">
                        <input type="text" class="form-control-plaintext pl-2" id="fname">
                        </div>
                    </div>

                    <div class="form-group col-12">
                        <label for="staticEmail" class="col-sm-2 col-form-label d-inline-block">Email</label>
                        <div class="col-sm-4 d-inline-block">
                        <input type="text" class="form-control-plaintext pl-2" id="staticEmail" value="email@example.com">
                        </div>
                    </div>

                    <div class="form-group col-12">
                        <label for="inputPassword" class="col-sm-2 col-form-label d-inline-block">Password</label>
                        <div class="col-sm-4 d-inline-block">
                        <input type="password" class="form-control" id="inputPassword">
                        </div>
                    </div>
                    <button>Registrar</button>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        name: 'Contacto',
        props: ['contacto']
    }
</script>

<style>

</style>