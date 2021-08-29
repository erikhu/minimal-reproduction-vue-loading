<template>
    <div>
        <loading :active="true"/>
    </div>
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Loading from 'vue-loading-overlay';
import 'vue-loading-overlay/dist/vue-loading.css';

@Component({
    components: {
        Loading
    }
})
export default class Spinner extends Vue {
}
</script>
