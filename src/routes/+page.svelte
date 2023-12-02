<script>
    let imgUrl = 'src/lib/assets/bg-img.jpeg';
    //Changing this to 'src/lib/assets/bg img.jpeg' breaks it.
</script>

<div class="back" style="background-image: url({imgUrl});">
    <h1>Hello world!</h1>
</div>

<style>
    .back{
        min-height:100vh;
    }
</style>