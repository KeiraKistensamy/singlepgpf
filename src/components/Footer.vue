<template>
  <footer class="container-fluid">
    <div class="row">
        <p class="lead">Keira's Portfolio &copy;  <span class="shadow">{{cYear}}</span>
        </p>
    </div>
  </footer>
</template>

<script>
export default {
    name: "FooterComp",
    data() {
        return {
            cYear: new Date().getUTCFullYear()
        }
    }
}
</script>

<style>

</style>