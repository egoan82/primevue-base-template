<script setup>
import { useLayout } from '@/layouts/composables/layout';

import Card from 'primevue/card';
const { isDarkTheme } = useLayout();



</script>

<template>
    <h1>Hello Test</h1>
    <Card>
            <template #title>Simple Card Test</template>
            <template #content>

                <p class="m-0">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                </p>

            </template>
        </Card>
</template>
