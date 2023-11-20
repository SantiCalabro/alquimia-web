<template>
    <div class="container">
        <div class="sub-container">
            <img :src=logoSrc alt="Logo de Alquimia" class="logo">
            <ul>
                <li>Inicio</li>
                <li>Nosotrxs</li>
                <li>Trenzas</li>
                <li>Piercing</li>
                <li>Tattoo</li>
            </ul>
        </div>
    </div>
</template>

<style src="./Navbar.css" scoped></style>
<script>
import logo from "../../../../assets/Alquimia_white.png"
export default {
    data() {
        return {
            logoSrc: logo,
        }
    },
    name: 'Navbar',
}
</script>