<template>
    <nb-container>


        <nb-header/>
        <nb-grid>
            <nb-col :style="{ backgroundColor: '#f00'}"></nb-col>
            <nb-col :style="{ backgroundColor: '#0f0'}">

                    <nb-row :style="{backgroundColor: '#fff'}">
                        <nb-text :style="styles.text_merah">{{ styles.text_merah }}</nb-text>
                        <nb-text class="text-biru">test biru</nb-text>
                    </nb-row>
                    <nb-row :style="{backgroundColor: '#f0f'}"></nb-row>
               
            </nb-col>
        </nb-grid>
        
        <!--
        <nb-content class="container">
            <nb-button transparent class="btn-login">
                <nb-text class="blue-text">Masuk</nb-text>
            </nb-button>
        
            <nb-text class="register-text">Daftar</nb-text>
            <nb-text class="register-description-text">{{description}}</nb-text>
            <nb-button class="btn-success">
                <nb-text>Daftar dengan Nomor Handphone</nb-text>
            </nb-button>
             <nb-text class="register-description-text-2nd">Atau Daftar dengan akun social media</nb-text>

            <nb-button class="btn-facebook">
                <nb-text>Daftar dengan Akun Facebook</nb-text>
            </nb-button>
            
             <nb-button class="btn-google">
                <nb-text>Daftar dengan Akun GMail</nb-text>
            </nb-button>
        </nb-content>
        -->
    </nb-container>
</template>

<style>
@import "css/style.css";



.text-merahxxx {
    color: #f0f;
}

.container{
    padding: 5%;
}

.header-white{
    background-color: white;
}
.blue-text{
     color: #00ADE7;
     font-weight: bold;
}

.btn-login{
    justify-content: flex-end;
}
.register-text{
    color: black;
    font-size: 38px;
    font-weight: bold;
    padding-left: 5%;
    padding-top: 38%;
    padding-bottom: 4%;
}

.register-description-text{
    color: darkred;
    font-size: 12px;
    padding-left: 5%;
    line-height: 12px;
    padding-bottom: 20%;   
}

.register-description-text-2nd{
    color: black;
    font-size: 16px;
    line-height: 12px;  
    padding-top: 15%;
    font-weight: bold;
    text-align: center;
    padding-bottom: 10%;
}

.btn-success{
    background-color: #00ADE7;
    border-radius: 8px;
    justify-content: center;
    height: 60px;
    marginBottom: 20px
}

.btn-facebook{
    background-color: #3B5998;
    border-radius: 8px;
    justify-content: center;
    height: 60px;
    marginBottom: 30px;
    
}

.btn-google{
    background-color: #F34A38;
    border-radius: 8px;
    justify-content: center;
    height: 60px;
}

</style>

<script>
import { Col, Row, Grid } from 'react-native-easy-grid';  
// import test2 from './test2'
import xxx from './test.js'

export default {
    computed: {
        styles: function(){
            return xxx;
        }
    },
    data(){
        return{
            description: "Ada beberapa cara bagi Anda untuk mendaftar, \n\npilih salah satu opsi dibawah ini."
        }
    },
    mounted(){
        console.log(this.styles);
    }
}
</script>