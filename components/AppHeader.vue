<template>
    <header class="header">
        <ul>
            <li><nuxt-link to='/'>Home</nuxt-link></li>
            <li><nuxt-link to='/product'>Products</nuxt-link></li>
            <li><nuxt-link to='/product/detail'>Product Detail</nuxt-link></li>
            <li><nuxt-link to='/career'>Careers</nuxt-link></li>
            <li><nuxt-link to='/about'>About Us</nuxt-link></li>
            <li><nuxt-link to='/contact'>Contact Us</nuxt-link></li>
        </ul>
    </header>
</template>
<script>
export default {
    name: 'AppHeader'
}
</script>

<style scoped>
    .header{
        display: flex;
        justify-content: space-between;
        align-items: center; 
        padding: 1rem;
        border-bottom: 1px dotted #ccc;
    }

    .header .title{
        font-size: 3rem;
        color: #f26488;
    }
    .header ul {
        display: flex;
    }
    .header a{
        display: inline-block;
        background: #333;
        color: #fff;
        padding: .3rem 1rem;
        margin-right: .5rem;
    }
</style>