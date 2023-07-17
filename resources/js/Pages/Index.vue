<template>
    Hy {{ name }}
    <Link href="nextPage"> askdj
    </Link>
</template>

<script>
import { Link } from '@inertiajs/vue3'
export default {
    components: {
        Link
    },
    props: {
        name: String
    },
    data() {
        return {};
    },
};
</script>