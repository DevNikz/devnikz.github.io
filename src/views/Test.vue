<template>
    <div style="margin-bottom: 80px;">
        <h1>Test!</h1>
    </div>
</template>

<style scoped>
.paragraph {
    max-width: 700px;
    margin-bottom: 20px;
}

.photo {
    margin-top: 50px;
    text-align: center;
}

@media only screen and (min-width: 620px) {
    .paragraph {
        float: left;
    }

    .photo {
        float: left;
        padding: 10px;
        padding-left: 80px;
    }
}
</style>