<script setup>
const config = useRuntimeConfig()
</script>

<template>
    <v-app>
        <v-main>
            <v-container>
                <v-card>
                    <v-card-title>
                        NUXT 4 + STRAPI CONNECTION CHECK
                    </v-card-title>
                    <v-card-text>
                        setup is working: {{ config.public.strapiUrl }}
                    </v-card-text>
                </v-card>
            </v-container>
        </v-main>
    </v-app>
</template>

































































