<template>
    <div class="background">
        <h1>Fash Vix Marketplace</h1>

        <div>
            <h3>Fashion Attire</h3>

            <div>
                <div v-for="attire in attires" :key="attire.id">
                    <h3>{{attire.name}}</h3>
                    <p>{{attire.likes}}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
* {
    font-family: Inter, Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

h1 {
    font-size: 2em;
}
</style>

<script>
export default {
    data() {
        return {
            attires: [
                {
                    id: 1,
                    name: "Culotte dress",
                    likes: 0
                },

                {
                    id: 2,
                    name: "Babydoll dress",
                    likes: 0
                },
                {
                    id: 3,
                    name: "Wrap around dress",
                    likes: 0
                },
                {
                    id: 4,
                    name: "Kimono dress",
                    likes: 0
                },
                {
                    id: 5,
                    name: "Bubble dress",
                    likes: 0
                },
                {
                    id: 6,
                    name: "Tutu dress",
                    likes: 0
                },
                {
                    id: 7,
                    name: "Polo dress",
                    likes: 0
                },
                {
                    id: 8,
                    name: "Agbada Dress",
                    likes: 0
                },
                {
                    id: 9,
                    name: "Buba dress",
                    likes: 0
                },
                {
                    id: 10,
                    name: "Gele dress",
                    likes: 0
                },
            ]
        }
    }
}
</script>








