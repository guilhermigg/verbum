<template>
    <b-navbar type="is-primary">
        <template #brand>
            <b-navbar-item id="title" tag="router-link" :to="{ path: '/' }">
                <h1> Verbum </h1>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300&family=IBM+Plex+Sans+Arabic:wght@100;200&display=swap');

#title {
    font-family: 'Cormorant Garamond', serif;
    font-family: 'IBM Plex Sans Arabic', sans-serif;
    font-family: 'Playfair Display', serif;
}
</style>