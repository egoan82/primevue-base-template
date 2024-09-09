<script setup>
import { useLayout } from '@/layouts/composables/layout';

import Card from 'primevue/card';
import Fieldset from 'primevue/fieldset';
const { isDarkTheme } = useLayout();



</script>

<template>
    <h1>Hello World</h1>

    <Card>
        <template #title>Simple Card</template>
        <template #content>
            <p class="m-0">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore sed consequuntur error
                repudiandae numquam deserunt quisquam repellat libero asperiores earum nam nobis, culpa ratione quam
                perferendis esse, cupiditate neque
                quas!
            </p>

            

        <Fieldset legend="Header" class="mt-6">
            <p class="m-0">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>
        </Fieldset>


        </template>
    </Card>
</template>
