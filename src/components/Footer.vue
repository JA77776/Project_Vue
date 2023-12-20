<template>
    <div class="container">
        <div class="row">
            <p class="lead">
                Jay-donn's Portfolio &copy;
                <span>{{ currentYear }}</span>
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        name: ' FooterComp ',
        data() {
            return {
                currentYear: new Date().getFullYear()
            }
        }
    }
</script>