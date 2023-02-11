
<template>
    <div class="container login-box">
        <div class="row justify-content-center align-items-center">
            <div class="col-md-5">
                <div class="card">
                    <div class="card-body">
                        <div class="text-center py-2">
                            <img class="img-fluid login-logo" src="@/assets/imgs/logo.png" />
                        </div>
                        <div>
                            <form>
                                <div class="form-group" style="padding-left: 5rem;">
                                    <label for="txt-username">เลขบัญชี</label><br>
                                    <input type="text" class="form-control form-control" id="txt-username"
                                        name="username"  maxlength="10">
                                </div>
                                <br>
                                <div class="form-group" style="padding-left: 5rem;">
                                    <label for="txt-password">รหัสผ่าน</label><br>
                                    <input type="password" class="form-control form-control" id="txt-password"
                                     name="password" maxlength="32">
                                </div>
                                <br>
                                <button type="submit" class="btn btn-cdg-primary my-2 w-100"
                                    style="font-size:1.5rem;" action="Homme.vue"> Sign in</button>
                                    <br>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.login-logo {
    width: 10%;
}

.login-box {
    margin: 20rem 25rem;
    
}

.login-box .card {
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
}

.login-box .card {
    border-radius: 10px;
}

#txt-username,
#txt-password {
    font-size: 1.2em;
    line-height: 0px;
}
 .card{
    background-color: aliceblue;
 }
</style>
<style>
body {
    background-image: url("@/assets/imgs/bg.jpg");
    background-size: cover;
    background-position: top center;
}
</style>