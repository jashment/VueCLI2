<template>

    <v-layout column align-center>
        <v-flex>
            <v-card>
                <v-img
                src="https://images.pexels.com/photos/175773/pexels-photo-175773.jpeg"
                aspect-ratio="2.75"
                ></v-img>

                <v-card-title primary-title>
                    <div>
                        <h3 class="headline mb-0">{{ newMsg }}</h3>
                        <div></div>
                    </div>
                </v-card-title>

                <v-card-actions>
                    <v-btn flat color="#7DC5FF">Button1</v-btn>
                    <v-btn flat color="#7DC5FF">Button2</v-btn>
                </v-card-actions>
            </v-card>
        </v-flex>
    </v-layout>
</template>

<script>
export default {
    name: 'Hello',
    props: {
        newMsg: String
    },
    data: {
        imgLink: 'https://images.pexels.com/photos/175773/pexels-photo-175773.jpeg'
    }
}
</script>

<style>
    p{
        color: #1D67BD;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
</style>
