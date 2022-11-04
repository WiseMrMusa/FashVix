<template>
    <div class="background">
        <h1>Fash Vix Marketplace</h1>

        <div>
            <h2>Fashion Attires</h2>

            <div>
                <div v-for="attire in attires.sort((a,b) => b.likes - a.likes)" :key="attire.id">
                    <h4>{{attire.name}}</h4>
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
                    likes: 2
                },

                {
                    id: 2,
                    name: "Babydoll dress",
                    likes: 4
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








