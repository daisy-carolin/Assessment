<template>
    <div class="vue-tempalte">
        <form>
            <h3>Sign Up</h3>
 
            <div class="form-group">
                <label>First Name</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>

            <div class="form-group">
                <label>Last Name</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>
 
            <div class="form-group">
                <label>Phone Number</label>
                <input type="email" class="form-control form-control-lg" />
            </div>
 
            <div class="form-group">
                <label>Password</label>
                <input type="password" class="form-control form-control-lg" />
            </div>
 
            <button type="submit" class="btn btn-dark btn-lg btn-block">Register</button>
 
            <p class="forgot-password text-right">
                Already registered 
                <router-link :to="{name: 'login'}">sign in?</router-link>
            </p>
        </form>

        </div>
</template>
 
<script>
    export default {
        data() {
            return {}
        }
    }
</script>