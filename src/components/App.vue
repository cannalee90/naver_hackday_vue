<template>
    <div id="app">
        <div class="container">
            <img src="../assets/logo.png">
            <h2>Cloud Picker</h2>
            <form>
                <div class="custom-file" style="width:initial;">
                    <input type="file" class="custom-file-input" id="customFile">
                    <label class="custom-file-label" for="customFile">Choose file</label>
                </div>
            </form>
            <form>
                <div class="form-group">
                    <div>
                        미리보기
                    </div>
                    <div class="preview">
                    </div>
                </div>
                <button type="submit" class="btn btn-primary">클라우드에 저장</button>        
            </form>        
        </div>
    </div>
</template>

<script>

export default {
    name: "App"
};
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

.preview {
    width:300px;
    height:300px;
    border:1px solid #ced4da;
    display:inline-block
}

</style>
